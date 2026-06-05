---
name: analise-metricas
description: >
  Analisa métricas de campanha (CTR, CPC, CPA, ROAS) e gera diagnóstico com causa provável
  e ação corretiva. Vai além do relatório: explica o porquê e diz o que fazer. Use quando
  pedirem analisar métricas, diagnosticar campanha, entender por que o CPA subiu, otimizar
  resultados, ou avaliar performance.
---

# Análise de Métricas com IA

Recebe métricas de campanha e gera diagnóstico inteligente: o que está acontecendo, por que está acontecendo, e o que fazer. Vai além do relatório (que mostra números) — esta skill interpreta os números e sugere ação.

## Contexto da Agência Asher

Consulte `references/projecao-cpl-cpa.md` para benchmarks de CPA por nicho.

**Agvel Veículos:**
- Budget: R$2.000/mês
- CPL benchmark: R$10/lead
- Meta: 200+ leads/mês
- Plataformas: Meta Ads + Google Ads

**Clincog:**
- Budget: R$3.000/mês
- CPA benchmark (saúde/psicologia): R$54
- Produtos com tickets diferentes (Clube R$97/mês, cursos R$147-697, Integra R$1.000+)
- Plataformas: Meta Ads

---

## Fluxo

### 1. Receba as métricas

Peça ao usuário (ou receba diretamente):

```
Me passe as métricas da campanha:

- Plataforma (Meta, Google)
- Período (datas)
- Investimento (R$)
- Impressões
- Cliques
- CTR (%)
- CPC (R$)
- Leads ou conversões
- CPL ou CPA (R$)
- Faturamento atribuído (se tiver)
- ROAS (se tiver)

Se tiver métricas do período anterior pra comparar, melhor ainda.
```

### 2. Calcule o que faltar

```
CTR = (Cliques / Impressões) × 100
CPC = Investimento / Cliques
CPL = Investimento / Leads
CPA = Investimento / Vendas
ROAS = Faturamento / Investimento
Frequência = Impressões / Alcance (se tiver alcance)
```

### 3. Compare com benchmarks

Busque os benchmarks em `references/projecao-cpl-cpa.md`:

| Métrica | Resultado | Benchmark | Status |
|---------|-----------|-----------|--------|
| CTR | X% | 1-3% (Meta) | ✅ / ⚠️ / ❌ |
| CPC | R$ X | R$ 0,40-1,80 (nicho) | ✅ / ⚠️ / ❌ |
| CPL/CPA | R$ X | R$ X (nicho) | ✅ / ⚠️ / ❌ |
| ROAS | Xx | >2x (mínimo) | ✅ / ⚠️ / ❌ |
| Frequência | X | <3 (ideal) | ✅ / ⚠️ / ❌ |

### 4. Diagnostique cada métrica fora do padrão

Para cada métrica com ⚠️ ou ❌, gere:

```
DIAGNÓSTICO: [Métrica] está [acima/abaixo] do esperado

Valor atual: X
Benchmark: Y
Diferença: Z%

CAUSA PROVÁVEL:
[Explicação em 2-3 linhas do que provavelmente está causando.
Não chutar. Usar lógica de funil: se CTR está baixo mas CPC está
alto, o problema é no criativo, não no público.]

AÇÃO CORRETIVA:
[O que fazer na prática. Ser específico: "Testar 3 novos ganchos
nos criativos com a skill copy-anuncio" é melhor que "melhorar os
criativos".]
```

### 5. Árvore de diagnóstico (referência interna)

Use esta lógica para diagnosticar:

**CTR baixo (< 1%):**
- Criativo não para o scroll → testar novos ganchos visuais
- Público muito amplo → refinar segmentação
- Fadiga de criativo → trocar peças (frequência alta confirma)

**CPC alto (acima do benchmark):**
- Pouca concorrência mas público pequeno → expandir interesse
- Muita concorrência no leilão → testar horários e posicionamentos
- Relevância baixa → score de relevância do Meta confirma

**CPL/CPA alto:**
- CTR bom mas CPL alto → problema na landing page (não na campanha)
- CTR ruim e CPL alto → problema no criativo + público
- Landing page lenta → testar velocidade
- Formulário longo → reduzir campos

**ROAS baixo (< 2x):**
- CPA aceitável mas ROAS baixo → ticket muito baixo para o CPA
- CPA alto → resolver CPA primeiro
- Muitas vendas mas faturamento baixo → upsell ou ticket maior

**Frequência alta (> 3):**
- Público saturado → expandir ou trocar audiência
- Budget alto para público pequeno → redistribuir

### 6. Gere o diagnóstico completo

```markdown
# Diagnóstico de Campanha: [Cliente] — [Período]

## Resumo em 1 linha
[Frase direta: "O CPA está 2x acima do benchmark porque o criativo saturou e a frequência bateu 4,2."]

## Métricas vs Benchmark
[tabela da etapa 3]

## Diagnósticos
[lista de diagnósticos da etapa 4]

## Plano de Ação (próximos 7 dias)
| Prioridade | Ação | Responsável | Impacto esperado |
|-----------|------|-------------|-----------------|
| 1 (urgente) | [ação] | [nome] | [resultado] |
| 2 | [ação] | [nome] | [resultado] |
| 3 | [ação] | [nome] | [resultado] |

## Quando reavaliar
[Data sugerida para checar se as ações funcionaram. Geralmente 7 dias.]
```

### 7. Entrega

```
1. Aprovar diagnóstico e executar plano
2. Detalhar um diagnóstico específico
3. Gerar novos criativos/copy com base no diagnóstico (chama copy-anuncio)
4. Comparar com mês anterior
```

---

## Regras

- Diagnóstico sem ação é inútil. Toda métrica fora do padrão precisa de ação concreta.
- Nunca culpar o algoritmo. Sempre buscar causa no criativo, público, oferta ou página.
- Uma métrica isolada não diz nada. Sempre cruzar (CTR + CPC + frequência contam uma história).
- Ação "melhorar o criativo" é proibida. Ser específico: "testar gancho X com formato Y para público Z".
- Benchmarks são referência, não lei. Se o CPA está acima do benchmark mas o ROAS é 5x, está tudo bem.
- Sempre conectar ação com skill da agência (para o time saber qual ferramenta usar).

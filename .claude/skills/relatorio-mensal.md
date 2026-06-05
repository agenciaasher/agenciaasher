---
name: relatorio-mensal
description: >
  Gera relatório mensal de resultados para apresentar ao cliente com métricas de tráfego,
  leads, conversões, ROI e próximos passos. Formato visual em HTML ou Markdown. Use quando
  pedirem relatório mensal, relatório de resultado, relatório de performance, apresentação
  pro cliente, ou fechamento do mês.
---

# Relatório Mensal de Resultados

Gera o relatório completo do mês para apresentar ao cliente na reunião mensal. Consolida métricas de tráfego, leads, conversões, ROI e entregas realizadas. Entrega em Markdown (para uso interno) ou HTML (para apresentar ao cliente).

## Contexto da Agência Asher

Consulte o briefing em `clientes/<nome>/projeto.md` para metas e KPIs do cliente.

**Agvel Veículos:**
- Meta: faturar R$5M/mês (hoje R$3M)
- Meta de leads: aumentar expressivamente (base: 200/mês)
- Budget mídia: R$2.000/mês
- Benchmark CPL: R$10/lead (ref: projecao-cpl-cpa.md)
- Sucesso: avaliado a cada 90 dias

**Clincog:**
- Meta: 1.600 assinantes no Clube
- Meta Integra: 500 inscritos até fev/2027
- Budget mídia: R$3.000/mês
- Benchmark CPA saúde/psicologia: R$54 (ref: projecao-cpl-cpa.md)
- Sucesso: Clube lotado + Integra esgotado com antecedência

Consulte `references/projecao-cpl-cpa.md` para benchmarks de CPA por nicho.

---

## Fluxo

### 1. Coleta de dados

Pergunte (ou receba) as métricas do mês:

**Tráfego pago:**
- Investimento total do mês (R$)
- Impressões
- Cliques
- CTR (%)
- CPC médio (R$)
- Leads gerados
- CPL (R$)
- Vendas atribuídas ao tráfego
- CPA (R$)
- Faturamento atribuído (R$)
- ROAS

**Orgânico (Instagram):**
- Seguidores (início e fim do mês)
- Alcance total
- Impressões
- Engajamento médio (%)
- Post com melhor performance (qual e por quê)
- Stories views média

**Comercial (se disponível):**
- Total de leads atendidos
- Taxa de resposta
- Taxa de agendamento (visita/call)
- Taxa de fechamento
- Tempo médio de resposta

Se o usuário não tiver todos os dados, gere o relatório com o que houver e marque os campos faltantes com `[DADO PENDENTE]`.

### 2. Calcule as métricas derivadas

```
CPL = Investimento / Leads
CPA = Investimento / Vendas
ROAS = Faturamento / Investimento
Lucro = Faturamento - Investimento
Crescimento de seguidores = ((Final - Início) / Início) × 100
```

Compare com:
- Meta do cliente (do briefing)
- Mês anterior (se informado)
- Benchmark do nicho (de `references/projecao-cpl-cpa.md`)

### 3. Gere o relatório

Estrutura obrigatória:

```markdown
# Relatório Mensal: [Cliente] — [Mês/Ano]

**Período:** DD/MM a DD/MM/AAAA
**Elaborado por:** Agência Asher

---

## Resumo Executivo

[3 a 5 linhas com os principais resultados do mês em linguagem simples.
O cliente precisa entender o cenário em 30 segundos.
Destaque o número mais importante primeiro.]

---

## Tráfego Pago

| Métrica | Resultado | Meta | Benchmark | Status |
|---------|-----------|------|-----------|--------|
| Investimento | R$ X | R$ X | — | — |
| Impressões | X | — | — | — |
| Cliques | X | — | — | — |
| CTR | X% | >1% | X% (nicho) | ✅ ou ⚠️ |
| CPC | R$ X | < R$ X | R$ X (nicho) | ✅ ou ⚠️ |
| Leads | X | X | — | ✅ ou ⚠️ |
| CPL | R$ X | < R$ X | R$ X (nicho) | ✅ ou ⚠️ |
| Vendas | X | X | — | ✅ ou ⚠️ |
| CPA | R$ X | < R$ X | R$ X (nicho) | ✅ ou ⚠️ |
| Faturamento | R$ X | R$ X | — | ✅ ou ⚠️ |
| ROAS | Xx | >Xx | — | ✅ ou ⚠️ |

### Análise

[2 a 3 parágrafos explicando os resultados. O que funcionou, o que não funcionou,
por que o CPA subiu ou desceu, qual campanha performou melhor.
Linguagem clara, sem jargão técnico desnecessário.]

---

## Orgânico (Instagram)

| Métrica | Resultado | Mês anterior | Variação |
|---------|-----------|-------------|----------|
| Seguidores | X | X | +X% |
| Alcance | X | X | +X% |
| Engajamento | X% | X% | +X% |
| Melhor post | [descrição] | — | — |

### Análise

[1 a 2 parágrafos sobre o orgânico. Qual formato performou melhor,
o que gerar mais no próximo mês.]

---

## Entregas Realizadas

- [x] [Entrega 1]
- [x] [Entrega 2]
- [x] [Entrega 3]
- [ ] [Entrega pendente, se houver]

---

## Diagnóstico do Mês

### O que funcionou
- [Item 1 com dado concreto]
- [Item 2]

### O que precisa melhorar
- [Item 1 com sugestão de ação]
- [Item 2]

### Oportunidade identificada
- [Oportunidade com base nos dados]

---

## Plano para o Próximo Mês

| Ação | Responsável | Prazo | Impacto esperado |
|------|-------------|-------|-----------------|
| [Ação 1] | [Nome] | [Data] | [Resultado esperado] |
| [Ação 2] | [Nome] | [Data] | [Resultado esperado] |
| [Ação 3] | [Nome] | [Data] | [Resultado esperado] |

---

*Agência Asher — Relatório gerado em DD/MM/AAAA*
```

### 4. Formato de entrega

Pergunte:
```
Como quer o relatório?
1. Markdown (para uso interno ou copiar pro Google Docs)
2. HTML visual (para apresentar ao cliente no navegador)
```

Se escolher HTML, gere uma página HTML limpa com a mesma estrutura, estilo profissional, tabelas formatadas e cores que indiquem status (verde = meta batida, amarelo = atenção, vermelho = abaixo da meta).

### 5. Aprovação

```
1. Aprovar relatório
2. Ajustar dados ou análise
3. Gerar em outro formato
```

---

## Regras

- Linguagem simples. O cliente não é marketeiro. "CPL" precisa de explicação na primeira vez.
- Nunca esconder resultado ruim. Se o CPA estourou, mostrar e explicar por quê com plano de correção.
- Sempre comparar com benchmark do nicho (de `references/projecao-cpl-cpa.md`).
- Sempre terminar com plano de ação. Relatório sem próximo passo é inútil.
- Se faltar dado, marcar como `[DADO PENDENTE]` em vez de inventar.
- Resumo executivo é para o dono/decisor. Deve ser compreensível sem ler o resto.

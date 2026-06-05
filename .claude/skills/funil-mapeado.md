---
name: funil-mapeado
description: >
  Mapeia o funil completo do cliente (awareness → consideração → conversão → retenção),
  identifica gargalos e sugere ações por etapa. Gera diagrama visual do funil em texto.
  Use quando pedirem mapear funil, analisar funil, identificar gargalo, jornada do cliente,
  ou pipeline de vendas.
---

# Funil Mapeado

Mapeia o funil completo do cliente de ponta a ponta: de onde o lead entra até onde vira cliente recorrente. Identifica gargalos (onde está perdendo gente) e sugere ações específicas para cada etapa.

## Contexto da Agência Asher

Consulte `clientes/<nome>/projeto.md` para dados do funil atual.

**Agvel Veículos:**
- Entrada: Instagram, Facebook, Webmotors, Mobiauto, Napista, site, presencial
- Funil: Lead chega → Grazi atende no WhatsApp → fotos e negociação → visita presencial → proposta → fechamento
- Gargalo provável: conversão de lead digital em visita presencial
- Pós-venda: ligação D+30, garantia 3 meses

**Clincog:**
- Funil Clube: Instagram → ManyChat → WhatsApp → Lili/Ingrid fecham
- Funil Integra: Instagram (orgânico) → link → inscrição autônoma no site
- Funil Cursos: WhatsApp groups + Instagram → site → compra
- Gargalo provável: furar a bolha (público sempre o mesmo há 3 anos) + conversão WhatsApp→fechamento
- Base ativa: 3.000 pessoas em grupos de WhatsApp

---

## Fluxo

### 1. Coleta

- Qual o cliente?
- Qual o produto principal a mapear?
- De onde vêm os leads hoje? (canais)
- Qual o processo de venda atual? (etapas)
- Tem dados de cada etapa? (quantos entram, quantos passam, quantos fecham)
- Tem pós-venda estruturado?

Se for cliente da agência, puxe do briefing e pergunte apenas os dados que faltam.

### 2. Mapeie as etapas do funil

Estrutura padrão (adaptar ao cliente):

```
TOPO (Awareness)
├── [Canal 1] → [volume estimado/mês]
├── [Canal 2] → [volume estimado/mês]
└── [Canal 3] → [volume estimado/mês]
    ↓
MEIO (Consideração)
├── [Etapa 1: o que acontece] → [taxa de passagem]
├── [Etapa 2: o que acontece] → [taxa de passagem]
    ↓
FUNDO (Conversão)
├── [Etapa 1: o que acontece] → [taxa de fechamento]
├── [Etapa 2: o que acontece] → [taxa de fechamento]
    ↓
PÓS-VENDA (Retenção)
├── [Ação 1]
├── [Ação 2]
    ↓
RECOMPRA / INDICAÇÃO
├── [Mecanismo de recompra]
└── [Mecanismo de indicação]
```

### 3. Calcule as taxas de conversão entre etapas

Para cada transição, calcule:

```
Taxa = (saem da etapa / entram na etapa) × 100
```

Se não tiver dados exatos, use benchmarks:
- Impressão → Clique: 1-3% (Meta Ads)
- Clique → Lead (formulário): 5-15%
- Lead → Resposta WhatsApp: 40-60%
- Resposta → Agendamento: 20-40%
- Agendamento → Fechamento: 30-50%
- Cliente → Recompra (12 meses): 10-30%

### 4. Identifique os gargalos

Gargalo = etapa onde a taxa de conversão está significativamente abaixo do benchmark ou onde o maior volume absoluto de leads é perdido.

Para cada gargalo, entregue:

```
GARGALO: [Etapa X → Etapa Y]
Taxa atual: X% (benchmark: Y%)
Perda estimada: Z leads/mês
Causa provável: [hipótese baseada nos dados]
Ação sugerida: [ação específica com skill ou ferramenta da agência]
```

### 5. Sugira ações por etapa

| Etapa | Problema | Ação | Skill da agência |
|-------|----------|------|-----------------|
| Topo | Pouco alcance | Aumentar budget ou orgânico | `pauta-mensal`, `copy-reels` |
| Topo | Público saturado | Testar lookalike ou interesse novo | `trafego-meta-ads` |
| Meio | Lead não responde | Script de primeiro contato | `script-whatsapp` |
| Meio | Lead esfria | Sequência de follow-up | `script-whatsapp` |
| Fundo | Objeção de preço | Mapa de objeções + argumento de valor | `mapa-objecoes` |
| Fundo | Não fecha online | Landing page com oferta clara | `landing-page` |
| Pós-venda | Sem retenção | Sequência de reativação | `reativacao-base` |
| Recompra | Sem mecanismo | Programa de indicação ou upsell | — |

### 6. Gere o documento do funil

```markdown
# Funil Mapeado: [Cliente] — [Produto]

**Data:** DD/MM/AAAA

---

## Diagrama do Funil

[diagrama em texto conforme etapa 2]

---

## Taxas de Conversão por Etapa

[tabela com entrada, saída, taxa, benchmark, status]

---

## Gargalos Identificados

[lista de gargalos conforme etapa 4]

---

## Plano de Ação

[tabela de ações conforme etapa 5]

---

## Métricas para Acompanhar

[lista de KPIs que o time deve monitorar mensalmente para validar se as ações estão funcionando]
```

### 7. Entrega

```
1. Aprovar funil mapeado
2. Ajustar uma etapa
3. Detalhar um gargalo específico
4. Gerar plano de ação expandido
```

---

## Regras

- Funil é diagnóstico, não achismo. Se não tem dado, dizer que é estimativa.
- Cada gargalo precisa de ação concreta, não conselho genérico.
- Sempre conectar ação com skill da agência (mostra ao time qual ferramenta usar).
- Funil sem pós-venda está incompleto. Sempre mapear retenção e recompra.
- Atualizar o funil todo mês com dados reais (usar junto com `relatorio-mensal`).

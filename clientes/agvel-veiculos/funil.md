# Funil Mapeado: Agvel Veículos

**Atualizado em:** Junho/2026
**Gerado por:** skill `funil-mapeado`

---

## Diagrama do Funil

```
TOPO (Awareness)
├── Instagram / Facebook (orgânico + pago) → ~X impressões/mês
├── Webmotors / Mobiauto / Napista (marketplaces) → leads diretos
├── Google Ads (search) → leads de intenção alta
├── Site próprio (agvelveiculos.com.br) → tráfego orgânico + pago
└── Presencial (vitrine física) → walk-in
    ↓
MEIO (Consideração)
├── Lead chega no WhatsApp → Grazi atende em até 10min
├── Envio de fotos e informações do veículo
├── Negociação por WhatsApp (preço, financiamento, troca)
    ↓
FUNDO (Conversão)
├── Visita presencial na loja
├── Ver o carro pessoalmente → proposta
├── Fechamento (financiamento ou à vista)
    ↓
PÓS-VENDA (Retenção)
├── Ligação D+30 (como está o carro?)
├── Garantia de 3 meses inclusa
    ↓
RECOMPRA / INDICAÇÃO
├── Sem mecanismo formal de indicação (oportunidade)
└── Sem programa de recompra estruturado (oportunidade)
```

---

## Taxas de Conversão Estimadas

| Etapa | Entrada | Saída | Taxa | Benchmark | Status |
|-------|---------|-------|------|-----------|--------|
| Impressão → Clique (Meta) | — | — | A medir | 1-3% | ⏳ |
| Clique → Lead (formulário/WhatsApp) | — | — | A medir | 5-15% | ⏳ |
| Lead → Resposta WhatsApp | 200/mês | ~160 | ~80% | 40-60% | ✅ |
| Resposta → Visita presencial | ~160 | A medir | A medir | 20-40% | ⏳ |
| Visita → Fechamento | A medir | A medir | A medir | 30-50% | ⏳ |

**Nota:** Dados de topo de funil serão preenchidos após primeiro mês de campanha.

---

## Gargalos Identificados

### Gargalo 1: Lead digital → Visita presencial
- **Taxa atual:** A medir (estimativa: abaixo de 20%)
- **Causa provável:** Lead conversa por WhatsApp, pede foto, mas não se desloca até a loja. Distância (cidades vizinhas e outros estados) é barreira real.
- **Ação sugerida:**
  - Vídeo personalizado do carro pedido (Wenderson edita, Grazi grava no celular)
  - Follow-up D+1/D+3/D+7 com skill `script-whatsapp`
  - Landing page por veículo com fotos, ficha técnica e CTA direto pro WhatsApp (`landing-page`)
  - Para leads de outros estados: processo de compra remota com documentação assistida (diferencial Agvel)

### Gargalo 2: Fechamento por preço
- **Taxa atual:** Objeção #1 reportada pelo time
- **Causa provável:** Cliente compara preço de semi-novo com tabela FIPE sem considerar qualidade, procedência e garantia.
- **Ação sugerida:**
  - Mapa de objeções focado em preço (`mapa-objecoes`)
  - Argumento: documentação 100% limpa há 20 anos + garantia 3 meses + laudo cautelar
  - Copy que vende valor antes de mostrar preço (`copy-anuncio`)

### Gargalo 3: Sem mecanismo de recompra/indicação
- **Taxa atual:** Inexistente
- **Causa provável:** Pós-venda existe (D+30) mas não tem programa de indicação nem incentivo de recompra.
- **Ação sugerida:**
  - Criar programa "Indique e Ganhe" (desconto na próxima compra ou bônus de avaliação)
  - Sequência de reativação para base de clientes antigos (`reativacao-base`)
  - WhatsApp D+180: "Seu carro está bem? Conhece alguém procurando?"

---

## Plano de Ação

| Prioridade | Ação | Responsável | Skill |
|-----------|------|-------------|-------|
| 1 | Medir taxas reais de cada etapa no primeiro mês | Júlio + Grazi | `analise-metricas` |
| 2 | Script de atendimento + follow-up para Grazi | Wiliam | `script-whatsapp` |
| 3 | Landing pages por veículo prioritário | Wenderson | `landing-page` |
| 4 | Mapa de objeções de preço | Wiliam | `mapa-objecoes` |
| 5 | Programa de indicação (definir mecânica) | Maicon | — |
| 6 | Campanha de reativação de leads frios | Wiliam | `reativacao-base` |

---

## Métricas para Acompanhar (mensal)

- Leads totais por canal (WhatsApp, site, marketplaces, presencial)
- Taxa de resposta do WhatsApp
- Taxa de conversão lead → visita
- Taxa de conversão visita → fechamento
- CPL por canal
- Ticket médio por venda
- Leads perdidos por objeção de preço (pedir pra Grazi marcar)
- Indicações recebidas (quando programa existir)

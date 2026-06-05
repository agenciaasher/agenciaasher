---
name: projecao-financeira
description: Gera projeção financeira completa de 12 meses para infoprodutores ou clientes da agência. Sugere 4 produtos por faixa de ticket e projeta faturamento, investimento, ROAS e lucro líquido. Use quando pedir projeção financeira, simulação de faturamento, planejamento de receita, ou "quanto posso faturar".
---

# Projeção Financeira para Infoprodutores

## Contexto da Agência Asher

Esta skill pode ser usada de duas formas:
1. **Para clientes da agência**: consulte `clientes/<nome>/projeto.md` para usar budget real, produtos existentes e metas definidas no onboarding. Adapte as faixas de produto ao contexto do cliente.
2. **Para novos prospects**: use como ferramenta de venda na apresentação comercial da agência, mostrando o potencial de faturamento com tráfego pago.

## Fluxo de Execução

1. Pergunte ao usuário: **qual o nicho** e **se já tem alguma ideia de produto**
2. Sugira **4 produtos** (um por faixa de ticket) com nome, preço, tipo, promessa e descrição
3. Gere a projeção completa de 12 meses

## As 4 Faixas de Produto

| Faixa | Formato | Preço |
|---|---|---|
| Low-ticket | E-book, planilha, template, checklist | R$ 47 a R$ 97 |
| Curso Simples | Curso gravado, workshop | R$ 197 a R$ 297 |
| Curso Completo / Comunidade / SaaS | Curso + comunidade, programa, app | R$ 497 a R$ 2.500 |
| Mentoria | Mentoria individual ou em grupo | R$ 2.500 a R$ 7.000 |

**Nichos premium** (finanças, marketing digital, carreira, idiomas): preços tendem a ser maiores dentro de cada faixa.

## Lógica da Projeção

### Investimento e Reinvestimento
- Mês 1: R$ 5.000 por produto
- Reinveste uma % do lucro do mês anterior (varia por produto, entre 48% e 65%)
- Conforme o investimento se aproxima do **platô**, o reinvestimento desacelera (curva em S)
- Fórmula do platô: `fatorPlato = 1 - (investimento / plato)^2`

### ROAS por Faixa
O ROAS começa mais baixo (fase de aprendizado) e sobe até estabilizar.

- **Low-ticket**: começa 1,5x, estabiliza em 2,0x
- **Curso simples**: começa 1,8x, estabiliza em 2,5x
- **Curso completo**: começa 2,0x, estabiliza em 3,0x
- **Mentoria**: começa 2,5x, estabiliza em 4,2x (ticket alto compensa)

### Targets de Faturamento Anual (12 meses)

| Faixa | Faturamento 12m |
|---|---|
| Low-ticket | ~R$ 600.000 |
| Curso simples | ~R$ 700.000 |
| Curso completo | ~R$ 980.000 |
| Mentoria | ~R$ 985.000 |

Para nichos premium, os targets podem ser 20-40% maiores.

### Custos no Rodapé da Tabela
- **Impostos (Simples Nacional)**: alíquota dinâmica
  - Até R$ 180k: 7%
  - Até R$ 360k: 8,5%
  - Até R$ 720k: 9,5%
  - Acima de R$ 720k: 11%
- **Outros custos**: 13% do faturamento (equipe, ferramentas, operação)
- **Lucro líquido estimado**: lucro bruto menos impostos menos outros custos

### Mentoria: Início Tardio
Mentoria começa no mês 2 (precisa de mínima autoridade). ROAS mais alto pelo ticket.

## Estrutura da Entrega

### Projeção em tabela:
- Colunas: Mês, Investimento, ROAS, Faturamento, Lucro
- Rodapé: Impostos, Custos operacionais, Lucro líquido
- Resumo: Faturamento 12m, Lucro 12m, Total investido

### Design dos números:
- Números no padrão brasileiro: ponto como separador de milhar (R$ 125.992)
- Meses como "Mês 1", "Mês 2", etc.
- Lucro positivo em verde, negativo em vermelho
- ROAS >= 3 em verde, >= 2 na cor do produto, < 2 em cinza

## Regras

- Sem travessão, sem emoji
- Português do Brasil com acentuação correta
- Toda projeção vem com disclaimer: "Projeção baseada em médias de mercado. Resultados reais dependem de execução, nicho e otimização contínua."

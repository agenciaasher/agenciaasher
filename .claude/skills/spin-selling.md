---
name: spin-selling
description: Simula conversas realistas de venda no WhatsApp/DM usando o método SPIN Selling, com marcações didáticas, para treinar abordagem, contorno de objeções e fechamento. Use quando pedirem simular uma venda, treinar SPIN, criar diálogo de vendedor, praticar contorno de objeções, ou ver como seria uma conversa de venda.
---

# Simulador de Vendas SPIN Selling

Gera duas simulações realistas de conversa de venda (cliente vs vendedor) seguindo a metodologia SPIN Selling, com marcações didáticas em colchetes para que o usuário consiga ver, na prática, cada movimento da técnica.

## Contexto da Agência Asher

Antes de começar, verifique se a simulação é para um cliente da agência. Se for, consulte o briefing em `clientes/<nome>/projeto.md` para usar dados reais: produtos/serviços, preço, público-alvo, objeções já mapeadas e diferenciais. Isso torna a simulação muito mais útil para treinar o time de vendas do cliente.

Clientes atuais e seus contextos de venda:
- **Agvel Veículos**: 3 vendedores, ticket médio R$50-80K, objeções de financiamento, documentação, garantia. Wiliam coordena.
- **Clincog**: Lili/Ingrid/Yasmin no fechamento via WhatsApp, produtos de R$47 (curso) a R$2K+ (congresso). Funil: Instagram > ManyChat > WhatsApp > fechamento.

---

## Etapa 1. Coleta de informações

Peça ao usuário exatamente estas 5 informações:

> Vamos criar duas simulações realistas de venda para o seu produto. Me passa essas 5 informações:
>
> 1. Qual é o seu produto ou serviço?
> 2. Qual é o nicho ou segmento?
> 3. Quem é o público-alvo? (idade, profissão, dores, contexto)
> 4. Qual é o preço?
> 5. Quais os principais benefícios ou diferenciais?

Espere a resposta antes de prosseguir. Se faltar alguma informação crítica, pergunte uma vez, de forma direta e curta.

---

## Etapa 2. Geração das duas simulações

Gere DUAS simulações completas, claramente separadas:

- **Cenário 1. Cliente fecha a compra**
- **Cenário 2. Cliente diz que vai pensar**

Ambas seguem a mesma estrutura SPIN. O que muda é só o desfecho.

### Estrutura SPIN com marcações didáticas

Use estas marcações ao longo do diálogo, exatamente como escritas, em colchetes, no fim da fala que ilustra o movimento:

- `[SITUAÇÃO]` — perguntas que mapeiam o contexto do cliente
- `[PROBLEMA]` — perguntas que expõem a dor
- `[IMPLICAÇÃO]` — perguntas que aprofundam a consequência da dor
- `[NECESSIDADE DE SOLUÇÃO]` — perguntas que fazem o cliente verbalizar o desejo pela solução
- `[OBJEÇÃO]` — quando o cliente apresenta resistência
- `[CONTORNO DA OBJEÇÃO]` — quando o vendedor desmonta a objeção
- `[FECHAMENTO]` — quando o vendedor faz uma tentativa clara de fechar a venda

Marcações específicas do desfecho:
- `[LINK DE PAGAMENTO]`, `[PEDIDO DE COMPROVANTE]`, `[ENVIO DO COMPROVANTE]` — Cenário 1
- `[FOLLOW-UP]` — Cenário 2

### Regras de tom e estrutura

- O **cliente SEMPRE inicia a conversa**, com algo natural tipo: "Oi, vi seu conteúdo e me interessei em saber mais sobre o [produto]"
- O vendedor responde com uma pergunta de **[SITUAÇÃO]** específica do nicho, não genérica
- **Nunca** use a frase "posso te fazer umas perguntas?"
- O cliente precisa apresentar **pelo menos 2 objeções reais** ao longo do diálogo
- Cada objeção precisa de um **[CONTORNO DA OBJEÇÃO]** sólido usando: lógica direta, dado/estudo, analogia inteligente, ou prova social/história real
- O **tom é leve, humano, conversacional**, escrita de WhatsApp. Pode ter "kkk", "rsrs", contrações, frases curtas
- Use o **preço e os benefícios reais** que o usuário forneceu, não invente

### Cenário 1. Cliente fecha

Após o `[FECHAMENTO]`:
1. Cliente aceita
2. Vendedor envia o link > `[LINK DE PAGAMENTO]`
3. Vendedor pede o comprovante > `[PEDIDO DE COMPROVANTE]`
4. Cliente envia o comprovante > `[ENVIO DO COMPROVANTE]`
5. Vendedor confirma, dá boas-vindas, próximo passo

### Cenário 2. Cliente vai pensar

Após o `[FECHAMENTO]`:
1. Cliente responde que precisa pensar
2. Vendedor **respeita**, não força, mas **pede dia e horário específicos** para retornar
3. Cliente combina dia e horário
4. Marque a última fala com `[FOLLOW-UP]`

---

## Formato de saída

```
## Simulação 1. Cliente fecha a compra

**Cliente:** [fala]
**Vendedor:** [fala] [MARCAÇÃO]
**Cliente:** [fala] [MARCAÇÃO se aplicável]
...

---

## Simulação 2. Cliente diz que vai pensar

**Cliente:** [fala]
**Vendedor:** [fala] [MARCAÇÃO]
...
```

Cada simulação deve ter de **12 a 20 trocas de mensagens**.

Ao final das duas simulações, ofereça refazer com outro perfil de cliente, outras objeções, ou aprofundar uma parte específica.

---

## Anti-padrões a evitar

- Diálogo que parece roteiro de venda formal
- Vendedor que despeja benefícios sem perguntar
- Objeções fracas que o vendedor derruba em uma frase genérica
- Cliente que aceita tudo na primeira investida (precisa de pelo menos 2 objeções reais)
- Esquecer de marcar as etapas SPIN
- Inventar benefícios, preço ou diferenciais que o usuário não informou

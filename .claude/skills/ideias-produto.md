---
name: ideias-produto
description: Pesquisa o mercado de um nicho e entrega 50 ideias diversas de infoproduto em 15 formatos diferentes (curso, ebook, mentoria, agente GPT, mini-SaaS, planilha, checklist, desafio e outros), apresentadas em tabela agrupada por formato. Use quando pedirem ideias de produto digital, explorar o que criar para uma especialidade, ou lista de possíveis infoprodutos para um nicho.
---

# Ideias de Produto (50 ideias em 15 formatos)

A partir da especialidade do usuário, faz pesquisa de mercado do nicho e entrega 50 ideias diversas de infoproduto em 15 formatos, em tabela agrupada por formato.

> **Idioma:** português do Brasil com acentuação correta.
> **Travessão proibido.** Use vírgula, ponto ou dois pontos.

## Contexto da Agência Asher

Se a geração de ideias for para um cliente da agência, consulte `clientes/<nome>/projeto.md` para usar dados reais do nicho e público. Para a Clincog, por exemplo, os cursos gravados já existem (10-20 vendas/mês sem promoção), e essa skill pode gerar 50 ideias de novos produtos para o ecossistema educacional.

---

## Fluxo

### Passo 0. Abertura e pergunta única

```
Vou pesquisar o mercado do seu nicho e te entregar 50 ideias de infoproduto
em 15 formatos diferentes.

Qual é a sua especialidade? O que você ensina ou entrega para as pessoas?
```

Aguarde a resposta.

### Passo 1. Pesquisa de mercado

Acione a skill `pesquisa-mercado` passando a especialidade como nicho. Se não estiver disponível, faça a pesquisa você mesmo com busca real na web.

Antes da tabela, mostre ao usuário UM parágrafo curto (3-5 linhas) com os achados que guiam as ideias: dores dominantes, faixa de preço típica e 1-2 oportunidades de posicionamento.

### Passo 2. Tabela com 50 ideias

50 conceitos DISTINTOS entre si (ângulo, método, público ou promessa diferentes).

**Distribuição obrigatória por formato (15 categorias, mínimo 3 ideias cada):**
1. Mentoria em grupo
2. Mentoria individual
3. Curso gravado
4. Curso ao vivo (turma fechada)
5. Ebook
6. Template ou kit pronto
7. Consultoria
8. Comunidade paga (assinatura)
9. Workshop (evento curto e intensivo)
10. Serviço (feito para o cliente)
11. Agente GPT (assistente personalizado)
12. Mini-SaaS ou ferramenta web
13. Planilha pronta
14. Checklist
15. Desafio (jornada de 3, 7, 21 ou 30 dias)

As 5 categorias finais (Agente GPT, Mini-SaaS, Planilha, Checklist, Desafio) nunca podem ficar de fora.

Apresente agrupada por formato:

```
### Mentoria em grupo

| # | Nome | Público-alvo resumido | Faixa de preço |
|---|------|----------------------|----------------|
| 1 | ... | ... | R$ ... |
```

Numeração contínua de 1 a 50.

### Passo 3. Convite à escolha

```
Me diga o número (de 1 a 50) da ideia que mais te interessou. Se preferir
parar por aqui, é só dizer "encerrar".
```

### Passo 4. Encerramento

Quando o usuário escolher uma ideia válida:

```
Ok agora siga os próximos passos de acordo com a orientação do Leandro na aula.
```

Se o usuário disser "encerrar":

```
Sem problema. Se mudar de ideia, abra um novo chat e seguimos a partir dali.
```

---

## O que esta skill NÃO faz

- Não conduz concepção do produto
- Não gera arquivo de nenhum tipo
- Não repete o nome da ideia escolhida no encerramento
- Não oferece prosseguir para outra fase no mesmo chat

---
name: pesquisa-mercado
description: Faz pesquisa de mercado profunda e estruturada de um nicho em 9 eixos (tamanho de mercado, concorrentes, faixa de preço, público-alvo, objeções reais, assuntos quentes, YouTube Top 10, biblioteca de anúncios e riscos regulatórios), com busca real na web. Entrega relatório em markdown e opcionalmente página HTML visual com gráficos SVG. Use quando pedir pesquisa de mercado de um nicho, análise de concorrência, ou antes de criar estratégia para um cliente.
---

# Pesquisa de Mercado. 9 Eixos com Busca Real

Skill autossuficiente. Pesquisa um nicho a fundo e entrega um relatório estruturado de 9 eixos.

> **Idioma:** responda sempre em português do Brasil, com acentuação correta.
> **Travessão proibido** em qualquer texto gerado. Use vírgula, ponto ou dois pontos.
> **Emoji proibido** em qualquer texto gerado.

## Contexto da Agência Asher

Antes de começar, verifique se a pesquisa é para um cliente específico da agência. Se for, consulte o briefing em `clientes/<nome>/projeto.md` para já partir com os dados do nicho, concorrentes mapeados no onboarding e público-alvo definido. Isso acelera a pesquisa e evita redundância.

Clientes atuais:
- **Agvel Veículos** (nicho: veículos seminovos, Pato Branco/PR)
- **Clincog** (nicho: neuropsicologia, educação continuada para profissionais)

---

## OBRIGATÓRIO. Buscas reais, eixo por eixo

Esta skill só tem valor se fizer buscas reais na ferramenta de busca da web. É proibido escrever qualquer eixo a partir só do seu conhecimento interno.

Anuncie ao usuário antes de começar:

```
Vou pesquisar o mercado de {nicho} agora. Leva alguns minutos.
```

### Plano de buscas obrigatório

Você DEVE executar, no mínimo, as 13 buscas abaixo, uma a uma:

1. Eixo 1. `{nicho} mercado Brasil tamanho crescimento dados`
2. Eixo 2. `curso {nicho} online concorrentes`
3. Eixo 2. `{nicho} infoproduto Hotmart Kiwify`
4. Eixo 3. `{nicho} curso online quanto custa preço`
5. Eixo 4. `{nicho} público perfil idade quem busca`
6. Eixo 5. `{nicho} reclame aqui reclamação curso`
7. Eixo 5. `{nicho} curso não funcionou opinião negativa`
8. Eixo 6. `{nicho} assuntos em alta tendências 2025`
9. Eixo 7. `{nicho} youtube vídeos mais vistos canal`
10. Eixo 7. `{nicho} youtube tutorial iniciante mais assistido`
11. Eixo 8. `biblioteca de anúncios Meta {nicho}` ou `{nicho} anúncios Facebook Instagram`
12. Eixo 9. `{nicho} regras anúncio promessa proibida`
13. Eixo 9. `{nicho} polêmica processo crítica`

Se um eixo vier fraco depois da busca, faça uma busca extra com outros termos.

### Aprofundar abrindo as páginas reais (obrigatório)

- **Concorrentes (eixos 2 e 3).** Para cada concorrente, abra a página de vendas real e pegue o preço real, os entregáveis e os bônus. Só escreva "preço não divulgado" se a página realmente não mostrar o preço.
- **Reclame Aqui (eixo 5).** Abra o reclameaqui.com.br e procure pelos nomes dos concorrentes e por termos do nicho.
- **YouTube (eixo 7).** Abra ou inspecione os vídeos do Top 10 para pegar título exato, canal, visualizações e comentários reais.

Abra no mínimo 5 páginas reais por pesquisa.

### Trava antes de escrever o relatório

Antes de montar o relatório, confira: cada um dos 9 eixos teve busca real própria? Você abriu as páginas de vendas dos concorrentes? Os eixos 8 (biblioteca de anúncios) e 9 (riscos) tiveram busca dedicada? Se algo faltou, faça agora.

---

## Os 9 eixos

1. **Tamanho e saúde do mercado.** Estimativa de tamanho no Brasil, tendência de crescimento, sazonalidade.
2. **Concorrentes (mínimo 10).** Diretos, indiretos e referências aspiracionais. Para cada: nome, link real, promessa, entregáveis, bônus, preço, diferencial. Monte tabela.
3. **Faixa de preço.** Menor preço, maior preço e faixa mais comum. Relação preço x formato. Sugestão de preço para produto novo.
4. **Público-alvo real.** Demografia, comportamento, situações de vida, nível de consciência (escala de Schwartz).
5. **Objeções reais (mínimo 10).** Investigue o Reclame Aqui, fóruns e comentários. Cada objeção com evidência de fonte.
6. **Assuntos quentes e ângulos virais.** Termos de busca em alta, conteúdos virais recentes, ganchos que performam.
7. **YouTube Top 10.** Os 10 vídeos mais relevantes do nicho com título, canal, views, comentários, thumbnail descrita, ângulo do título e lacuna.
8. **Biblioteca de anúncios.** Anúncios ativos há mais de 30 dias. Padrões de headline, gancho, oferta e CTA.
9. **Riscos regulatórios.** Regras específicas do nicho, palavras/promessas que dão problema, histórico de polêmicas.

---

## Regras de rigor

- Nunca invente dado nem fonte. Se não achou, escreva "sem dados disponíveis".
- Todo número tem origem em uma busca real.
- Sem travessão, sem ponto de exclamação e sem emoji no relatório.

---

## Estrutura do relatório

```markdown
# Pesquisa de Mercado. {Nicho}

**Data:** {data}
**Nicho:** {nicho}

## 1. Tamanho e saúde do mercado
## 2. Concorrentes
## 3. Faixa de preço praticada
## 4. Público-alvo real
## 5. Objeções reais
## 6. Assuntos quentes
## 7. YouTube Top 10
## 8. Biblioteca de anúncios
## 9. Riscos regulatórios

## Oportunidades e lacuna de posicionamento
## Cuidados e riscos
## Confiança geral da pesquisa
```

---

## Como entregar

### Caso 1. Acionada por outra skill

Produza o relatório em markdown e devolva o controle para a skill que chamou. **Não gere HTML neste caso.**

### Caso 2. Acionada diretamente pelo usuário (fluxo de 2 etapas)

**Etapa 1.** Apresente resumo conversacional dos achados. Salve o relatório completo em `pesquisa-mercado-{nicho}.md`.

**Etapa 2.** Ofereça o HTML:

```
Pesquisa concluída. Posso gerar também uma página HTML visual com esse
relatório, com gráficos em todos os 9 eixos?

1. Sim, gerar o HTML
2. Não, só o markdown está ótimo
```

Se sim, carregue o template em `.claude/skills/references/template-relatorio-pesquisa.html`, preencha cada placeholder com os dados da pesquisa e salve como `pesquisa-mercado-{nicho}.html`.

### Regras do HTML

- **Light Copy.** Sem travessão, sem ponto de exclamação, sem emoji.
- **Dados ausentes.** Escreva "sem dados disponíveis", não invente.
- **HTML self-contained.** Não adicione bibliotecas externas.
- Gráficos obrigatórios por eixo em SVG inline (sem JavaScript, sem biblioteca externa).

### Paleta de gráficos

| Variável | Hex | Quando usar |
|---|---|---|
| chart-1 | #0EA5E9 | Cor principal de barras |
| chart-2 | #10B981 | Positivos, crescimento |
| chart-3 | #F59E0B | Atenção, intermediário |
| chart-4 | #8B5CF6 | Segmento alternativo |
| chart-5 | #EF4444 | Riscos, valores críticos |
| border | #E5E7EB | Linhas de grid |
| muted-fg | #71717A | Rótulos de eixo |
| fg | #0A0A0A | Rótulos de destaque |

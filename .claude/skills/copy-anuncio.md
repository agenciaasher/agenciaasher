---
name: copy-anuncio
description: >
  Gera copy de anúncio para Meta Ads e Google Ads em múltiplos formatos (feed, stories,
  reels, search, display). Adapta por etapa do funil (topo, meio, fundo), aplica Light Copy
  e gera variações para teste A/B. Use quando pedirem copy de anúncio, texto de anúncio,
  criativo de texto, copy para campanha, ou variações de anúncio.
---

# Copy de Anúncio

Gera copy de anúncio pronta para subir no Meta Ads ou Google Ads. Entrega texto final formatado por plataforma, com variações para teste A/B. Não gera imagem, não gera vídeo, não sobe campanha. Só texto.

## Contexto da Agência Asher

Se o anúncio for para um cliente da agência, consulte o briefing em `clientes/<nome>/projeto.md` e a sazonalidade em `clientes/<nome>/sazonalidade.md`. Para a **Agvel Veículos**, use tom de seriedade e objetividade, foque em confiança, qualidade e diferenciais (20 anos sem pendência documental, dono fala com o cliente, garantia 3 meses). Para a **Clincog**, use tom de autoridade com proximidade, foque em raciocínio clínico aplicado, casos reais e pertencimento profissional.

Consulte também:
- `references/manual-copy.md` para os 15 princípios e 20 vícios proibidos
- `references/checklist-light-copy.md` para verificação rápida antes de entregar

---

## Referências obrigatórias de copy

Todo anúncio gerado por esta skill deve ser modelado segundo os três pilares abaixo. Antes de escrever uma linha, internalizar esses princípios.

**Eugene Schwartz — Nível de consciência e intensidade do desejo**
O desejo já existe no público. A copy não cria desejo: ela o canaliza. Antes de escrever, identifique o nível de consciência do público-alvo (inconsciente do problema, consciente do problema, consciente da solução, consciente do produto, ou completamente ciente). O gancho e o corpo mudam completamente dependendo desse nível. Intensidade emocional construída em camadas, não jogada de uma vez.

**David Ogilvy — Pesquisa de público antes da escrita**
Pesquise o público mais do que qualquer outra coisa. Ogilvy pesquisava semanas antes de escrever uma linha. Para cada anúncio, responda: o que essa pessoa pensa quando acorda, o que teme, o que deseja e o que já tentou antes de você. A copy específica supera a genérica sempre. Use dados reais, situações concretas, palavras que o público usa, não as que o anunciante prefere.

**Aristóteles — Ethos, Pathos, Logos**
Todo anúncio eficaz equilibra os três. Ethos (credibilidade do emissor) abre a porta. Pathos (emoção ativada pela situação do público) prende a atenção. Logos (argumento lógico com dado concreto) justifica a decisão. Falta de ethos: a pessoa não confia. Falta de pathos: a pessoa não se importa. Falta de logos: a pessoa não decide. Os três precisam estar presentes.

---

## Fluxo

### 1. Coleta (pergunte o que faltar)

- Qual o produto ou serviço anunciado?
- Qual a etapa do funil? (Topo: awareness / Meio: consideração / Fundo: conversão)
- Qual a plataforma? (Meta Feed, Meta Stories, Meta Reels, Google Search, Google Display)
- Qual o público-alvo?
- Tem oferta específica? (desconto, condição, prazo)
- Qual o CTA desejado? (WhatsApp, landing page, formulário, compra direta)

Se for cliente da agência, puxe os dados do briefing e da sazonalidade automaticamente. Pergunte apenas o que não puder deduzir.

### 2. Verifique o mês atual e a sazonalidade

Consulte `clientes/<nome>/sazonalidade.md` e verifique se há oportunidade sazonal no mês. Se houver, adapte o ângulo do anúncio.

### 3. Escolha o tipo de anúncio (Mandala VTSD)

Com base no funil e no público, defina o tipo:

- **Ultra Segmentado (fundo):** fala direto com quem já conhece o problema. Específico, direto, CTA forte.
- **Problema-Solução (meio):** mostra a dor e apresenta a saída. Cena real + virada.
- **Pesquisa Científica (topo/meio):** dado ou fato que surpreende. Educa e gera curiosidade.
- **Atualidades / Trend (topo):** conecta o produto a algo que está acontecendo agora (notícia, data, evento).

Informe ao usuário qual tipo escolheu e por quê.

### 4. Gere a copy

Para cada plataforma solicitada, entregue:

#### Meta Ads (Feed)

```
GANCHO (primeira linha, até 125 caracteres):
O gancho é o momento em que a pessoa para de scrollar. É um choque. Uma afirmação que ela não esperava,
que ativa curiosidade intensa ou medo imediato sobre algo que ela já sente mas nunca ouviu nomeado com
precisão. O gancho preenche a atenção: a pessoa para o que está fazendo porque aquela frase atingiu algo
real nela. Para construir esse choque, conheça o público a fundo (use o briefing e os dados de pesquisa):
qual a maior dor não dita, o maior medo silencioso, a situação mais específica da rotina desse público.
Sem pergunta. Sem exclamação. Afirmação direta com dado concreto ou provocação que nomeia o que o público
vive mas não sabe como dizer.

CORPO (palavras suficientes para 60 a 90 segundos de leitura em voz alta):
Não poupar palavras. O corpo precisa ter densidade para prender quem parou pelo gancho e levá-lo até o CTA.
Desenvolvimento em camadas: cena real que o público reconhece, causa do problema (a que ninguém fala), virada
ou revelação, consequência concreta. Light Copy: ensina ou avisa, não vende.

CTA:
{Frase de transição + ação clara. Ex: "Veja como funciona. Link na bio." ou "Fale com a gente no WhatsApp."}
```

#### Meta Ads (Stories / Reels)

```
TEXTO NA TELA (até 3 linhas curtas):
Linha 1: {gancho visual, 5-7 palavras}
Linha 2: {benefício ou dado}
Linha 3: {CTA curto}

LEGENDA (se aplicável):
{2 a 3 linhas complementares}
```

#### Google Search

```
TÍTULO 1 (até 30 caracteres): {benefício principal}
TÍTULO 2 (até 30 caracteres): {diferencial ou oferta}
TÍTULO 3 (até 30 caracteres): {CTA ou urgência real}
DESCRIÇÃO 1 (até 90 caracteres): {argumento + prova curta}
DESCRIÇÃO 2 (até 90 caracteres): {benefício secundário + CTA}
```

#### Google Display

```
TÍTULO CURTO (até 25 caracteres): {gancho}
TÍTULO LONGO (até 90 caracteres): {promessa com dado concreto}
DESCRIÇÃO (até 90 caracteres): {argumento + CTA}
```

### 5. Gere variações A/B

Para cada formato, entregue **3 variações**:
- **Variação A:** ângulo principal (o mais forte)
- **Variação B:** ângulo alternativo (muda o gancho, mantém a promessa)
- **Variação C:** ângulo emocional (muda o tom, apela para consequência pessoal)

### 6. Revisão obrigatória antes de mostrar

Aplique o checklist de `references/checklist-light-copy.md`:

- Zero travessões
- Zero exclamação
- Zero "Não é X. É Y."
- Zero pergunta no gancho
- Zero "mesmo que" / "sem precisar"
- Zero emojis
- Zero lero-lero
- Toda promessa tem dado concreto
- Copy tem tese (explica o porquê)
- Especificidade presente

Informe: `Revisão concluída. [N] ajuste(s) aplicado(s).`

### 7. Entrega

Apresente todas as variações organizadas por plataforma. Pergunte:

```
1. Aprovar e usar
2. Quero ajustar uma variação específica
3. Gerar mais variações com outro ângulo
```

---

## Regras

- Gancho nunca começa com pergunta. Sempre afirmação.
- Gancho é construído a partir do público, não do produto. Sem conhecer o nível de consciência e a dor real do público, o gancho não funciona.
- Corpo do anúncio deve ter palavras suficientes para 60 a 90 segundos de leitura em voz alta. Não poupar palavras. Anúncio raso não converte.
- Ao corrigir, ajustar ou revisar um criativo, manter a densidade e a extensão originais. Reduzir o corpo sem instrução explícita do usuário é proibido. Corrigir não significa encurtar.
- Nunca mencionar preço no anúncio de topo de funil.
- Anúncio de fundo pode ter preço e condição.
- Urgência só se for real (data, estoque, vagas). Urgência falsa é proibida.
- Cada variação precisa ter um ângulo genuinamente diferente, não só trocar sinônimos.
- Respeitar limites de caracteres de cada plataforma.
- Português do Brasil com acentuação correta.

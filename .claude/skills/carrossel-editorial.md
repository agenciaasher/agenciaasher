---
name: carrossel-editorial
description: Cria carrosseis editoriais de 6 slides pra Instagram com narrativa aprofundada baseada em notícias reais, pesquisas científicas, dados, polêmicas e contas malucas do nicho. Estilo newsletter/Twitter de especialista. Use sempre que o usuário pedir um carrossel editorial, carrossel com dados, carrossel estilo tweet, carrossel de notícia, carrossel de pesquisa, ou disser coisas como "cria um carrossel com dados", "faz um carrossel editorial", "carrossel estilo newsletter", "carrossel de polêmica", "carrossel com pesquisa". Também dispara quando o contexto for criação de carrossel com narrativa aprofundada baseada em fatos e dados do nicho.
---

# Carrossel Editorial

Formato de carrossel de 6 slides pra Instagram com narrativa aprofundada de especialista. Baseado em notícias reais, pesquisas científicas, dados concretos, polêmicas e contas malucas do nicho. O slide 1 (capa) já abre com uma notícia/dado impactante.

O objetivo NÃO é vender. É construir uma narrativa tão interessante que a pessoa passa todos os slides. A venda aparece só no slide 6.

O entregável final tem DUAS partes na mesma resposta: (A) os prompts slide a slide, cada um pronto pra colar sozinho no ChatGPT, e (B) um prompt único completo com as instruções dos 6 slides juntos. Nos dois caminhos o usuário depois pede "cria o 1", "cria o 2" até o 6.

## Contexto da Agência Asher

Antes de começar, verifique se o usuário especificou para qual cliente é o carrossel. Se não especificou, pergunte. Consulte o briefing do cliente em `clientes/<nome>/projeto.md` para usar dados reais do nicho, público-alvo e tom de comunicação.

## O que você está criando

Carrosseis que parecem:
- thread de Twitter de especialista
- newsletter visual de nicho
- reportagem editorial em formato Instagram
- conteúdo que a pessoa salva e compartilha pela qualidade da informação

## O que você NUNCA cria

- Texto raso ou genérico (cada slide precisa ter substância, dados, nomes, números)
- Slides comerciais (a venda é só no slide 6)
- Dados inventados (usar pesquisas reais, instituições reais, números plausíveis)
- Apelo pra medo de doença ou morte
- Menção a remédios, medicamentos, condições de saúde mental
- Texto todo em bold (só dados específicos ficam em negrito)

## Estrutura dos 6 slides

TODOS os slides têm texto + imagem/gráfico de apoio. Nenhum slide é só texto.

- **Slide 1 (capa):** notícia/dado impactante + foto jornalística editorial. TÍTULO grande + subtítulo menor
- **Slide 2:** contexto/outro lado da história + foto jornalística editorial
- **Slide 3:** dado científico/prova + gráfico ou infográfico que visualiza o dado
- **Slide 4:** a virada/o que realmente funciona + infográfico comparativo ou gráfico
- **Slide 5:** reflexão/arremate + foto editorial ou ilustração conceitual
- **Slide 6:** CTA. Fundo escuro com destaque

Tipos de imagem de apoio por slide:
- Fotos jornalísticas editoriais (reportagem, flagrante, cenário real)
- Gráficos simples (barra, linha, pizza) com dados do texto
- Infográficos comparativos (X vs Y, lado a lado)
- Recortes estilo jornal/revista
- Mapas ou diagramas quando fizer sentido

## Regras de tipografia (CRÍTICAS)

- TÍTULO: fonte SANS-SERIF BOLD, preto puro, tamanho GRANDE
- CORPO/SUBTÍTULO: fonte SANS-SERIF REGULAR (NÃO bold), grafite escuro (#333333), tamanho 50% MENOR que o título
- Só DADOS NUMÉRICOS específicos ficam em negrito dentro do corpo (R$1.200, 30%, 3.800 corredores)
- O corpo do texto NUNCA é todo bold. É fonte regular, peso normal
- Se o título e o corpo ficarem do mesmo tamanho, está errado

## Fluxo da conversa

Siga os 5 passos abaixo em ordem.

### PASSO 1 — Briefing

Pergunte:

- Qual o produto/serviço?
- Qual o público?

Pare e espere a resposta.

### PASSO 2 — Tipo de CTA

Pergunte qual CTA o usuário quer no slide 6:

- **ManyChat** (comente X e receba isca no direct)
- **Seguir o perfil**
- **Engajar** (pedir opinião nos comentários)
- **Salvar o post**

Pare e espere a resposta.

### PASSO 3 — 10 ideias de Carrossel Editorial

Gere 10 ideias. Cada ideia deve conter:

- **TEMA:** título da narrativa
- **ÂNGULO:** tipo (notícia real, polêmica, conta maluca, pesquisa científica, comparação)
- **RESUMO:** em 2 linhas, o arco da narrativa dos 6 slides
- **CTA:** a palavra-gatilho do ManyChat ou a ação pedida

Regras:
- Variar os ângulos (não fazer 10 do mesmo tipo)
- Pelo menos 2 com pesquisa científica real (nome da instituição, ano, publicação)
- Pelo menos 2 polêmicas
- Pelo menos 2 contas malucas
- Todas com nicho claro
- Tom de especialista que manja, não de vendedor

Depois de listar as 10, escreva: **"Escolha uma ideia."**

### PASSO 4 — Texto completo dos 6 slides

Quando o usuário escolher, escreva o TEXTO COMPLETO de todos os 6 slides pra aprovação. Sem prompt de imagem ainda. Só o texto.

Cada slide deve ter:
- Texto substancial com dados reais, nomes de instituições, números concretos
- Tom de especialista/newsletter, não de vendedor
- Narrativa que constrói de slide em slide (não slides soltos)
- O slide 6 com o CTA escolhido pelo usuário

Junto com os 6 slides, entregue também:

**LEGENDA DO INSTAGRAM** — desenvolve a narrativa completa em texto corrido. Tom de especialista. CTA no final consistente com o tipo escolhido.

Depois de entregar, escreva:

**"Aprovou os textos? Se sim, eu gero os prompts pra criar as imagens no ChatGPT."**

### PASSO 5 — Prompts pro ChatGPT (slide a slide + prompt único)

Quando o usuário aprovar, entregue as DUAS partes abaixo, na MESMA resposta e nesta ordem.

#### Parte A — Prompts slide a slide

Gere 6 blocos SEPARADOS em código, cada um com título em H2 fora do bloco e linha horizontal `---` entre eles. Cada bloco precisa ser AUTOSSUFICIENTE: contém as regras gerais + a instrução daquele slide, pra poder ser colado sozinho no ChatGPT sem depender dos outros.

#### Parte B — Prompt único completo (6 slides juntos)

Logo após os blocos slide a slide, entregue UM ÚNICO prompt pra colar no ChatGPT que contém as instruções de todos os 6 slides.

#### Mensagem final ao usuário

Depois de mostrar as duas partes, escreva:

> Você tem dois caminhos.
>
> **Caminho 1. Slide a slide**
> Use os 6 blocos da Parte A. Cada um já vem completo e pode ser colado sozinho no ChatGPT pra gerar aquele slide.
>
> **Caminho 2. Prompt único**
> Cole o prompt da Parte B uma vez no ChatGPT. Depois é só pedir "cria o 1", "cria o 2" até o 6.

## Regras críticas consolidadas

### Sobre as ideias:
- O objetivo é ser GENUINAMENTE INTERESSANTE, não comercial
- Variar tipos: notícia real, polêmica, conta maluca, pesquisa científica, comparação
- Dados reais com nomes de instituições, publicações, anos
- Tom de especialista que manja, não de vendedor
- Venda APENAS no slide 6

### Sobre a narrativa:
- Os 6 slides constroem uma NARRATIVA (não são slides soltos)
- Slide 1: abre com impacto (notícia/dado)
- Slides 2-3: contextualiza e prova
- Slide 4: a virada
- Slide 5: arremate
- Slide 6: CTA

### Sobre tipografia:
- TÍTULO: sans-serif bold, preto, grande
- CORPO/SUBTÍTULO: sans-serif REGULAR (NÃO bold), grafite escuro, 50% menor que título
- Só DADOS NUMÉRICOS em negrito dentro do corpo
- Corpo NUNCA todo bold
- Título e corpo SEMPRE tamanhos diferentes

### Compliance:
- Sem menção a doenças, remédios, medicamentos, saúde mental
- Sem apelar pra medo de doença ou morte
- Tom inteligente e respeitoso
- PROIBIDO travessão. Use vírgula ou ponto final

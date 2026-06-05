---
name: ugc-persona-creator
description: Cria personagens UGC ultra-realistas e brasileiros para qualquer produto digital ou físico, gerando para cada cena DOIS prompts prontos, um pro ChatGPT (imagem estática) e um pro Magnific (animação em vídeo). Use sempre que o usuário pedir para criar um personagem UGC, avatar UGC, persona UGC, ou mencionar "UGC" no contexto de marketing, anúncios, criativos, ou conteúdo gerado por usuário.
---

# UGC Persona Creator

Cria personagens UGC ultra-realistas, brasileiros, com prompts prontos. Para cada cena, sempre entrega DOIS prompts:
1. **Prompt do ChatGPT/DALL-E** para gerar a imagem estática
2. **Prompt do Magnific** para animar essa imagem em vídeo

## Contexto da Agência Asher

Antes de começar, verifique se o usuário especificou para qual cliente é o UGC. Se não especificou, pergunte. Consulte o briefing do cliente em `clientes/<nome>/projeto.md` para usar dados reais do nicho, público-alvo, tom de comunicação e classe social do público. Isso calibra automaticamente cenário, vestimenta e objeto-âncora.

---

## Filosofia central

O UGC funciona porque gera identificação. A pessoa que vê o anúncio precisa pensar: "essa pessoa é igual a mim". Cada personagem é construído a partir do PÚBLICO, não do produto. O produto define o público, e o público define o personagem.

Três pilares:

1. **Ultra-realismo**: pele com textura real (poros, manchas sutis, marcas de expressão), cabelo natural (fios soltos, raízes), unhas reais, iluminação ambiente natural. Ninguém pode duvidar que é um ser humano real.

2. **Identificação brasileira**: tons de pele, traços, cabelo, vestimenta, cenário, tudo calibrado para o Brasil real, não para um Brasil de novela nem para um padrão americano/europeu.

3. **Coerência socioeconômica**: a classe social do público-alvo define TUDO no cenário. Cozinha, móveis, decoração, roupas, acessórios, iluminação. Classe C tem geladeira simples, azulejo básico, luz fluorescente. Classe A tem ilha de cozinha, acabamento premium, luz natural por janelão. O público precisa ver o cenário e pensar "essa é a minha casa".

---

## Fluxo completo

### Etapa 1. Coleta de informações

Pergunte ao usuário, de forma conversacional e direta:

1. **Qual é o produto?** (nome, o que faz, qual a transformação que entrega, qual o formato, curso, e-book, app, produto físico, etc.)
2. **Qual é o público-alvo?** (gênero, faixa etária, dor principal, desejo principal)
3. **Qual é o preço?** (isso calibra a classe social)

Se o usuário já tiver dado alguma dessas informações no contexto, não repita a pergunta.

A partir das respostas, deduza:

- **Classe social predominante** (A, B, C, D), baseado no preço, tipo de produto e público
- **Perfil psicográfico**, o que essa pessoa valoriza, como se veste, que tipo de ambiente doméstico tem
- **Formato do produto**, isso é crucial para a Cena 2 (como o personagem interage com o produto)

### Etapa 2. Apresentação dos 5 perfis

Gere exatamente **5 perfis de personagens UGC** diversificados. A diversificação deve cobrir:

- **Faixas etárias diferentes** dentro do range do público
- **Tons de pele variados** (do mais claro ao mais escuro, representando o Brasil real)
- **Tipos de cabelo diferentes** (liso, ondulado, cacheado, crespo, grisalho quando couber)
- **Contextos de vida diferentes** (solteira vs. mãe, CLT vs. autônoma, etc.)

Nesta etapa, apresente APENAS o resumo dos perfis. Seja breve e escaneável:

```
PERFIL 1, [Nome]
[Idade] anos | [Tom de pele resumido] | [Tipo de cabelo] | Classe [X]
[Uma frase sobre quem ela é e por que compraria o produto]

PERFIL 2, [Nome]
...

(até o 5)
```

Depois pergunte: **"Qual você quer criar primeiro?"**

### Etapa 3. Geração dos prompts (DUAL OUTPUT por cena)

Quando o usuário escolher um perfil, gere os prompts para 3 cenas obrigatórias. **Para cada cena, sempre entregue DOIS prompts em sequência:**

1. **Prompt do ChatGPT/DALL-E** (imagem estática)
2. **Prompt do Magnific** (animação em vídeo a partir da imagem)

As 3 cenas obrigatórias são:

---

#### CENA 1, Talking Head (para HeyGen)

A pessoa de frente para a câmera, enquadramento de busto (do peito pra cima), olhando direto para a lente, como se estivesse gravando um depoimento em vídeo. Esse prompt vai virar avatar de vídeo no HeyGen, então o enquadramento é crítico:

- Centralizado, cabeça com espaço acima, corte na metade do peito
- Fundo do cenário coerente com a classe social (parede da sala, cozinha ao fundo desfocada, etc.)
- Expressão natural de quem está falando, boca levemente entreaberta ou sorriso suave
- Iluminação frontal suave, sem sombras pesadas no rosto
- A pessoa precisa parecer acessível e confiável, como alguém de quem você ouviria um conselho

**REGRA DO OBJETO-ÂNCORA**: a pessoa SEMPRE deve estar segurando ou ter em contato visível um objeto que remeta ao universo do produto. Esse objeto aparece na parte inferior do enquadramento (na mão, no colo, encostado no corpo). Ele funciona como âncora visual, antes da pessoa abrir a boca, quem vê a imagem já entende do que se trata.

Exemplos de objeto-âncora por tipo de produto:

| Tipo de produto | Objeto na mão / no colo |
|---|---|
| Skincare / beleza | Potinho de creme genérico, pincel de maquiagem, espelho de mão |
| Cabelo / capilar | Frasco de máscara capilar, pente largo, borrifador |
| Violão / música | Violão apoiado no corpo, braço do violão visível, palheta na mão |
| Tráfego / marketing digital | Tablet mostrando gráficos genéricos, notebook semi-aberto |
| Curso online / e-book | Celular na mão mostrando tela (sem texto legível), tablet |
| Emagrecimento / fitness | Garrafa d'água, toalha de treino no ombro, fita métrica |
| Culinária | Colher de pau, avental, prato com comida |
| Finanças | Calculadora, caderninho de anotações, celular com app de banco |
| Relacionamento / autoajuda | Xícara de chá/café, livro, almofada abraçada |
| Costura / artesanato | Tecido, tesoura, linha e agulha |
| Idiomas | Caderno com anotações, fone de ouvido no pescoço |
| Veículos (Agvel) | Chave de carro na mão, tablet com fotos de veículos |
| Neuropsicologia (Clincog) | Prancheta, bloco de notas, caneta na mão |

O objeto deve ser genérico (sem marca legível) e aparecer de forma natural, como se a pessoa estivesse usando ou tivesse acabado de usar.

#### CENA 1B, Cenários extras de Talking Head

Logo depois de entregar o prompt da Cena 1 (talking head básico), sugira **5 variações de cenário** para o mesmo personagem, ainda no formato talking head (busto, olhando pra câmera, pronto pro HeyGen). Cada cenário deve ser uma **situação real e criativa** onde essa pessoa poderia estar falando sobre o produto ou sobre o problema que o produto resolve.

As variações devem ser pensadas a partir do produto e do perfil da pessoa. A ideia é dar opções de contexto visual que tornam o UGC mais interessante, variado e crível.

Apresente os 5 cenários de forma resumida:

```
CENÁRIO A, [Nome curto]
[Uma frase descrevendo a situação e por que ela estaria falando do produto ali]

CENÁRIO B, [Nome curto]
...

(até o E)
```

Depois pergunte: **"Quer gerar algum desses cenários?"**

Cada cenário deve:
1. Fazer sentido pro produto e pro perfil do personagem
2. Ser uma situação onde alguém realmente gravaria um relato/depoimento
3. Trazer diversidade visual (não repetir ambientes parecidos)
4. Manter o enquadramento de busto e o olhar direto pra câmera (é pra HeyGen)
5. Adaptar a roupa, a iluminação e os objetos ao cenário
6. **Manter o objeto-âncora** visível

#### CENA 2, Usando o produto

A pessoa interagindo com o produto de forma natural no cenário da casa dela.

| Tipo de produto | Como aparece na cena |
|---|---|
| E-book / PDF / cartilha | Lendo no celular ou tablet, expressão de interesse |
| Curso online | Assistindo no notebook ou celular, talvez com fone |
| App | Mexendo no celular, tela visível mas sem texto legível |
| Skincare / cosmético | Aplicando no rosto, olhando no espelho, tocando a pele |
| Produto físico (suplemento) | Segurando produto genérico (sem marca), olhando embalagem |
| Veículos (test drive) | Sentada no banco do carro, segurando o volante, sorrindo |
| Neuropsicologia (estudo) | Estudando com notebook e livros, fazendo anotações |

O cenário deve mostrar o ambiente da casa com todos os detalhes de classe social. Enquadramento 3/4 ou corpo inteiro.

#### CENA 3, Demonstrando resultado

A pessoa mostrando (visual e emocionalmente) que teve resultado com o produto. A emoção precisa ser genuína. Não exagerada. Sorriso real com rugas de expressão. Olhos que brilham naturalmente.

---

### Estrutura do PROMPT 1, ChatGPT/DALL-E (imagem estática)

Todos os prompts em **inglês** e no **formato vertical 9:16** (padrão Reels/Stories do Instagram, 1080x1920px).

Toda imagem gerada deve incluir no início do prompt a instrução de formato vertical:

```
[FORMAT AND STYLE]
Ultra-realistic photograph in VERTICAL 9:16 aspect ratio (1080x1920 pixels, portrait orientation, taller than wide, like a smartphone screen). Professional DSLR quality, [lens, 50mm for talking head, 35mm for wider scenes], natural depth of field, no artificial filters, no HDR. Documentary editorial style, a spontaneous real-life moment.

[FRAMING, varies by scene]
- Scene 1 / 1B (talking head): "Bust shot, centered frame, head with breathing room above, cut at mid-chest. Subject looking directly into the camera lens. Vertical composition filling the tall frame."
- Scene 2: "Three-quarter body shot" or "Full body shot" depending on context, vertical composition
- Scene 3: Varies, bust or 3/4, always vertical composition

[PERSON, DETAILED PHYSICAL DESCRIPTION]
[Gender], [age] years old, Brazilian. Skin tone [precise with reference, e.g. "warm medium brown, like café com leite"]. Face [shape], [specific facial features, nose, mouth, eye color]. Hair [type], [color with nuances], [length], [state]. Eyebrows [description]. Real skin texture: [age-appropriate, pores, expression lines, sun spots, marks]. Nails [state]. [Makeup or lack thereof]. [Body type].

[CLOTHING]
Class-appropriate AND scene-appropriate.

[EXPRESSION AND POSE, varies by scene]

[SETTING, BRAZILIAN HOME ENVIRONMENT]
Class-calibrated details.

[LIGHTING AND PHOTOGRAPHY]
Consistent with environment. Low ISO, no grain. Realistic colors.

[MANDATORY RESTRICTIONS]
- MUST be vertical 9:16 aspect ratio, portrait orientation, taller than wide
- NO text, watermark, logo, or overlay
- NO fantasy or stylized elements
- NO studio lighting
- NO airbrushed skin, maintain real texture
- NO American/European home elements, this is a Brazilian home
- NO visible brand names on any product
```

---

### Estrutura do PROMPT 2, Magnific (animação em vídeo)

Esse prompt anima a imagem estática gerada pelo ChatGPT. **A lógica é completamente diferente do prompt de imagem**, porque a aparência da pessoa, a roupa e o cenário já estão definidos pela imagem. O prompt de animação descreve apenas **MOVIMENTO**.

Regras do prompt de animação:

1. **Em inglês**, prompt corrido, sem seções em colchetes
2. **Curto**, entre 80 e 180 palavras
3. **NÃO descrever aparência física, roupa ou cenário**, isso já está na imagem
4. **SIM descrever**: micro-movimentos da pessoa (cabeça, olhos, boca, mãos), fala (quando talking head), interação com o objeto-âncora ou produto, movimento de câmera (geralmente sutil push-in ou estático), atmosfera de movimento
5. **Movimento sempre realista e contido**, sem gestos exagerados, sem zooms agressivos
6. **Duração implícita de 5 a 10 segundos**

---

### REGRA CRÍTICA: Consistência entre todas as cenas

A descrição física da pessoa no prompt do ChatGPT deve ser COPIADA IDÊNTICA em TODOS os prompts, Cena 1, Cena 1B, Cena 2 e Cena 3. É o mesmo ser humano. Só mudam: roupa, expressão, pose, enquadramento e elementos do cenário.

### Etapa 4. Fluxo de entrega

A entrega segue esta ordem:

1. **Entrega a Cena 1** (talking head básico) com os DOIS prompts em sequência
2. **Logo em seguida, apresenta os 5 cenários extras** (Cena 1B) e junto com eles, sempre oferece também as opções de gerar a Cena 2 e a Cena 3

Cada cena nova que o usuário pedir, sempre entrega os DOIS prompts em sequência (ChatGPT primeiro, Magnific depois).

Depois de cada entrega, sempre pergunte:

**"O que você quer gerar agora? Responde com a letra ou número:"**

E apresente TODAS as opções como TEXTO na mensagem:

```
CENÁRIOS EXTRAS DE TALKING HEAD (HeyGen):
A, [nome do cenário]
B, [nome do cenário]
C, [nome do cenário]
D, [nome do cenário]
E, [nome do cenário]

OUTRAS CENAS:
F, Cena 2: Usando o produto
G, Cena 3: Demonstrando resultado

OU:
H, Próximo personagem
```

O usuário responde com a letra. À medida que for gerando, remova da lista o que já foi feito.

Cada bloco de cena entregue vem com as instruções:
- Para o prompt do ChatGPT: "Cola esse prompt no ChatGPT. Se não ficar bom de primeira, roda de novo, às vezes leva 2 a 3 tentativas."
- Para o prompt do Magnific: "Cola no Magnific junto com a imagem que o ChatGPT gerou. Duração 5 a 10 segundos, motion strength médio (não alto, senão distorce o rosto)."

---

## Calibragem de classe social, referência rápida

### Classe C (produto R$29 a R$97)
- Azulejo branco, bancada granito cinza simples, armários MDF marrom
- Geladeira branca uma porta, fogão 4 bocas branco, micro-ondas simples
- Luz fluorescente branca no teto

### Classe B (produto R$97 a R$497)
- Bancada granito preto, armários brancos planejados
- Geladeira duplex inox, cooktop, forno elétrico
- Spots no teto, alguma luz natural

### Classe A (produto R$497+)
- Ilha, bancada quartzo/mármore, marcenaria sob medida
- French Door, coifa, eletrodomésticos inox
- Luz natural abundante, pendentes decorativos

---

## Vestimenta, guia por classe e gênero

A roupa é um dos maiores geradores de identificação (ou rejeição). Mulher de UGC em casa NÃO é mulher "largada" de blousão largo e estampado. Mesmo em casa, a maioria das mulheres brasileiras usa roupa que tem um mínimo de intenção.

### Mulheres, Classe C
- Camiseta de malha lisa, cor sólida
- Legging preta ou bermuda jeans curta
- Chinelo de dedo simples
- NÃO usar: blousão estampado largo, vestido florido tipo "camisola de vó"

### Mulheres, Classe B
- Camiseta de algodão com bom caimento, ou blusa básica de malha fina
- Calça legging preta ou calça jogger, ou short jeans
- Tênis casual ou rasteirinha

### Mulheres, Classe A
- Blusa de tecido leve (viscose, algodão premium, linho) em cor neutra ou pastel
- Calça de alfaiataria leve ou pantalona
- Sandália de couro, sapatilha, ou descalça em piso bonito

### Homens, Classe C
- Camiseta lisa ou de time, bermuda de tactel ou jeans
- Chinelo de dedo ou tênis popular

### Homens, Classe B
- Camiseta polo ou camiseta de algodão com bom corte, bermuda jeans ou calça jogger
- Tênis casual

### Homens, Classe A
- Camisa de linho ou camiseta premium lisa, bermuda de sarja ou calça chino
- Mocassim, sapatênis ou descalço

---

## Regras gerais dos prompts

1. **Consistência visual**: descrição física IDÊNTICA nos prompts de ChatGPT de TODAS as cenas
2. **Dual output obrigatório**: cada cena sempre tem 2 prompts em sequência
3. **Sem marca visível**: produto aparece genérico, tubo branco, embalagem neutra
4. **Detalhamento extremo no prompt de imagem**: "cabelo castanho" é fraco. "Dark brown curly hair, type 3A, shoulder-length, darker roots with slightly dry lighter ends" é forte
5. **Concisão no prompt de animação**: o prompt do Magnific é CURTO, focado em movimento
6. **Objetos contam a classe social**: geladeira Consul branca uma porta vs. French Door inox
7. **Diversidade étnica brasileira real**: caboclo, pardo, negro retinto, branco italiano, descendente japonês, descendente indígena
8. **Prompts em inglês, conversa em português**
9. **Tamanho**: Prompt do ChatGPT entre 200 e 400 palavras. Prompt do Magnific entre 80 e 180 palavras

## Tom de comunicação

Direto, profissional, descontraído. Evite: explicações longas sobre UGC, justificativas, linguagem técnica de fotografia. Prefira: ir direto ao ponto, perfis visuais e escaneáveis, prompt pronto pra copiar, perguntar o mínimo.

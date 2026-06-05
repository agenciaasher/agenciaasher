---
name: producao-digital
description: Workflow completo para criar e lançar infoprodutos digitais (ebooks, cursos, apps SaaS) usando IA como motor de produção. Cobre desde o texto do material didático até integração com Hotmart. Use quando pedir para criar ebook, curso digital, material didático, app SaaS, ou qualquer infoproduto do zero.
---

# Produção Digital (Infoprodutos com IA)

Workflow completo para produzir infoprodutos digitais usando IA como motor. Cada etapa usa uma ferramenta diferente (Claude, ChatGPT, Lovable/Vercel) para entregar o produto final pronto para vender.

## Contexto da Agência Asher

Se o infoproduto for para um cliente da agência, consulte `clientes/<nome>/projeto.md` para alinhar o produto com a estratégia definida. Para a Clincog, por exemplo, os cursos gravados já são um produto existente (10-20 vendas/mês sem promoção), e essa skill pode ser usada para criar novos materiais do ecossistema.

## Fluxo de Produção (13 Etapas)

### Fase 1: Conteúdo do Material Didático

**Etapa 1. Estruturar o texto**
- Definir tema, público-alvo e estrutura do material (módulos, capítulos, seções)
- Usar Claude para gerar o conteúdo textual completo do ebook/curso
- O texto deve ser didático, organizado por tópicos, com exemplos práticos

**Etapa 2. Revisar e aprovar o texto**
- Revisar o conteúdo gerado
- Ajustar tom, profundidade e exemplos conforme o público
- Aprovar antes de seguir para a parte visual

### Fase 2: Design Visual (Imagens)

**Etapa 3. Gerar prompts de imagem**
- Para cada seção/capítulo, gerar prompt de imagem didática no ChatGPT
- Estilo: clean, profissional, didático (não publicitário)
- Formato: coerente com o material (slides, páginas de ebook, cards)

**Etapa 4. Gerar as imagens**
- Colar cada prompt no ChatGPT (DALL-E)
- Gerar imagem por imagem: "Cria a imagem 1", "Cria a imagem 2"...
- Se não gostar, dar feedback e pedir nova versão antes de avançar

**Etapa 5. Compilar em PDF**
- Após gerar todas as imagens, pedir ao ChatGPT para salvar tudo em PDF
- Revisar o PDF completo antes de prosseguir

### Fase 3: App/Plataforma (Opcional)

**Etapa 6. Gerar o código do app**
- Usar Claude para gerar o prompt/código do app baseado no conteúdo do material
- Especificar: funcionalidades, telas, fluxo do usuário, design

**Etapa 7. Construir no Lovable (ou Vercel)**
- Colar o prompt no Lovable para gerar a primeira versão do app
- Alternativa: usar Vercel via Claude Code para deploy direto

**Etapa 8. Ajustes de design**
- Pedir ajustes visuais e de UX no Lovable
- Garantir que o design esteja coerente com a identidade do produto

**Etapa 9. Ajustes de funcionamento**
- Testar cada funcionalidade
- Corrigir bugs e fluxos quebrados

**Etapa 10. Testes finais**
- Testar várias vezes em diferentes cenários
- Testar em mobile e desktop
- Corrigir últimos bugs

### Fase 4: Lançamento

**Etapa 11. Integrar com Hotmart**
- Configurar o produto na Hotmart (ou Kiwify, Eduzz)
- Definir preço, parcelas, checkout
- Configurar webhook/API se for app

**Etapa 12. Página de vendas**
- Criar landing page usando Vercel (via Claude Code) ou builder
- Aplicar copy usando as skills da agência (mapa-objecoes, problema-solucao)

**Etapa 13. Campanha de lançamento**
- Criar criativos usando skills da agência (ugc-rotina-real, ugc-persona-creator, problema-solucao)
- Subir campanha via skill trafego-meta-ads
- Monitorar e otimizar

## Ferramentas por Etapa

| Etapa | Ferramenta | Responsável |
|---|---|---|
| 1-2 | Claude Code | IA / Skill |
| 3-5 | ChatGPT (DALL-E) | Wenderson + IA |
| 6 | Claude Code | IA / Skill |
| 7-10 | Lovable ou Vercel | IA + Wenderson |
| 11 | Hotmart/Kiwify | Wiliam |
| 12 | Vercel + Claude Code | IA + Wenderson |
| 13 | Meta Ads + Skills | Júlio César + IA |

## Dicas

- Não pule a revisão do texto (Etapa 2). O conteúdo é o produto, não o design.
- Gere as imagens uma a uma, não em lote. Qualidade individual importa.
- Teste o app em mobile ANTES de lançar. A maioria dos compradores acessa pelo celular.
- A página de vendas é tão importante quanto o produto. Use as skills de copy.

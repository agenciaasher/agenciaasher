---
name: landing-page
description: >
  Cria landing page completa em HTML/CSS e faz deploy na Vercel. Recebe a copy aprovada
  (da skill copy-pagina-vendas ou input direto) e monta a página responsiva com design
  profissional. Use quando pedirem criar landing page, página de vendas, página de captura,
  montar página, ou fazer deploy de página.
---

# Landing Page — HTML + Deploy

Cria a landing page completa em HTML/CSS puro a partir da copy aprovada. Monta a página responsiva, profissional e otimizada para conversão. Faz deploy na Vercel quando autorizado.

## Contexto da Agência Asher

Consulte o briefing em `clientes/<nome>/projeto.md` para tom e identidade.

**Agvel Veículos:**
- Estilo: sério, premium, objetivo. Referências: Shift Car, TCar, Avantgarden.
- Cores sugeridas: preto, grafite, prata, branco. Detalhe em azul ou dourado.
- Tipografia: sans-serif bold moderna, estilo automotivo premium.
- Objetivo de LP: captação de leads (formulário ou WhatsApp).

**Clincog:**
- Estilo: profissional, acolhedor, autoridade científica.
- Cores sugeridas: azul profundo, branco, cinza claro. Detalhe em dourado.
- Tipografia: sans-serif clean científica.
- Objetivo de LP: inscrição (Clube, Integra, cursos).

---

## Fluxo

### 1. Receba a copy

A copy pode vir de 3 fontes:
- **Skill `copy-pagina-vendas`** (15 blocos já aprovados)
- **Input direto do usuário** (textos soltos que serão organizados)
- **Briefing mínimo** (produto, oferta, CTA — eu gero uma LP simples)

Pergunte:
```
De onde vem a copy?
1. Já tenho a copy dos 15 blocos aprovada (skill copy-pagina-vendas)
2. Vou colar os textos aqui
3. Só tenho o briefing — gera uma LP simples de captura
```

### 2. Defina o tipo de página

| Tipo | Blocos | Quando usar |
|------|--------|-------------|
| **Página de vendas completa** | 15 blocos (Hero→Oferta Final) | Produto digital, curso, mentoria |
| **Página de captura (lead)** | Hero + Formulário + Prova Social + FAQ | Captação de leads, iscas, eventos |
| **Página de evento** | Hero + Programação + Palestrantes + CTA | Congresso, webinário, live |

### 3. Construa o HTML

Regras de construção:

**Estrutura:**
- HTML5 semântico
- CSS inline ou `<style>` no `<head>` (arquivo único, sem dependências externas)
- Responsivo (mobile-first, funcionar bem de 320px a 1440px)
- Sem JavaScript obrigatório (formulários podem usar ação externa)
- Sem frameworks ou CDNs (a página precisa funcionar offline)

**Design:**
- Fundo escuro ou claro conforme o cliente
- Tipografia grande e legível (mínimo 18px corpo, 32px+ headlines)
- Espaçamento generoso (padding 60px+ entre seções)
- Botões de CTA com cor contrastante, visíveis sem scroll
- Máximo 2 fontes (1 headline, 1 corpo)
- Imagens como placeholder: usar `<div>` com background-color e texto indicando o que vai ali

**Conversão:**
- CTA acima da dobra (visível sem scroll)
- CTA repetido a cada 3-4 seções
- Botão de WhatsApp flutuante se o CTA for WhatsApp
- Formulário simples (nome + email + telefone, máximo 3 campos)
- Sem menu de navegação (LP não tem saída, só o CTA)

**SEO mínimo:**
- `<title>` com nome do produto
- `<meta description>` com a promessa principal
- `<meta viewport>` para mobile

### 4. Mostre o preview

Salve o arquivo HTML e mostre o caminho. Se possível, abra no navegador local para o usuário validar.

```
Página gerada. Abre no navegador para validar:
[caminho do arquivo]

1. Aprovar e fazer deploy
2. Ajustar cor, fonte ou layout
3. Ajustar textos
4. Trocar o tipo de página
```

### 5. Deploy na Vercel (só com autorização)

Quando aprovado:

1. Verifique se o Vercel CLI está configurado
2. Crie a estrutura de deploy (pasta com `index.html`)
3. Execute o deploy
4. Retorne a URL pública

```
Página publicada.
URL: [url da vercel]

A página está no ar. Para editar depois, rode essa skill novamente.
```

Se o Vercel não estiver disponível, entregue o arquivo HTML pronto para upload manual.

---

## Estrutura HTML de referência (Página de Captura)

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>[Nome do Produto]</title>
  <meta name="description" content="[Promessa principal]">
  <style>
    /* Reset + variáveis do cliente */
    /* Seções: hero, benefícios, prova social, formulário, FAQ */
    /* Mobile-first, breakpoint em 768px */
  </style>
</head>
<body>
  <section class="hero"><!-- Headline + Subheadline + CTA --></section>
  <section class="beneficios"><!-- 3-5 bullets --></section>
  <section class="prova-social"><!-- 2-3 depoimentos --></section>
  <section class="formulario"><!-- Nome + Email + Telefone + Botão --></section>
  <section class="faq"><!-- 3-5 perguntas --></section>
  <footer><!-- Termos + Privacidade --></footer>
</body>
</html>
```

---

## Regras

- Arquivo único (HTML + CSS no mesmo arquivo). Sem dependências externas.
- Mobile-first obrigatório. Testar em 375px antes de entregar.
- Sem popup, sem modal de saída, sem countdown falso.
- Formulário com action para ferramenta do cliente (se não tiver, usar `mailto:` ou WhatsApp).
- Cores e fontes devem seguir a identidade do cliente (consultar briefing).
- Imagens reais devem ser fornecidas pelo cliente. Usar placeholders indicativos, nunca imagens genéricas de banco.
- Tempo de carregamento: a página deve ser leve (< 100KB sem imagens).
- Não usar JavaScript para funcionalidade essencial (formulário, navegação).

# Sessão Fundadora — Junho 2026

Documento que registra tudo que foi construído, decidido e acordado na primeira sessão completa de estruturação da Agência Asher no Claude Code. Qualquer sessão futura pode usar isso como ponto de partida.

---

## O que foi construído nessa sessão

### Estrutura de repositório

```
agenciaasher/
├── CLAUDE.md                      ← regras globais de linguagem (obrigatório em toda sessão)
├── README.md                      ← visão geral, time e clientes ativos
├── operacao.md                    ← organograma, fluxos, responsabilidades por entregável
├── .claude/skills/                ← skills instaladas (27+)
│   └── escrita-humanizada.md     ← skill obrigatória de humanização de texto
├── clientes/
│   ├── _template/                 ← modelo para onboarding de novos clientes
│   ├── agvel-veiculos/
│   ├── clincog/
│   └── curso-passei/
└── historico/
    └── 2026-06-sessao-fundadora.md
```

### Clientes onboardados

| Cliente | Pacote | Status |
|---------|--------|--------|
| Agvel Veículos | Agência R$ 3k/mês | Onboarding |
| Clincog | Completo R$ 6k/mês | Onboarding |
| Curso Passei | Completo R$ 6k/mês | Onboarding |

---

## Decisões tomadas nessa sessão

### Time e organograma

- **Maicon** — Dono / Estratégia. Direção e aprovação final de copies.
- **Wiliam** — Coordenador Geral. Elo entre clientes e setores. Recebe demandas, distribui tarefas, cobra prazos, faz CS, gerencia comercial digital dos clientes. **Cliente nunca fala direto com o time, sempre via Wiliam.**
- **Wenderson** — Designer + Editor de Vídeo
- **Júlio César** — Gestor de Tráfego
- **Annick** — Social Media (nome correto: Annick, não Aniki)

### Como usar o Claude no dia a dia

1. Cada sessão começa do zero em memória de conversa.
2. O que persiste são os **arquivos no repositório** — CLAUDE.md, briefings, skills.
3. Para pedir algo, basta identificar o cliente: "Quero pauta mensal para o Clincog". O Claude puxa o contexto automaticamente.
4. Quando uma decisão importante for tomada em conversa, pedir para salvar em arquivo.

### Separação de sessões por área (ideia do Maicon)

O Maicon sinalizou interesse em abrir sessões separadas por área de trabalho:
- Uma sessão para **Design / Criativos**
- Uma sessão para **Copy**
- Uma sessão para **Tráfego / Comercial**
- Uma sessão para **Social Media**

Isso facilita o foco e evita contexto misturado. O repositório serve como base compartilhada para todas.

### Regras de linguagem (salvas no CLAUDE.md raiz)

- **Sem travessões (—)** em nenhum texto. Usar vírgula, ponto ou reescrever.
- **Sem linguagem de IA**: proibido "certamente", "vale ressaltar", "é fundamental", "neste sentido", "tendo em vista", "destaca-se que" e similares.
- **Skill `/escrita-humanizada` é obrigatória** em todo texto gerado para qualquer cliente.
- Frases curtas. Voz ativa. Sem intensificadores vazios.

### Drive de assets (a implementar)

Foi discutido criar um Google Drive com logos e artes dos clientes, linkado no repositório. Ainda não implementado — pedir ao Maicon para confirmar quando quiser avançar nisso.

---

## Identidade visual dos clientes (resumo)

### Agvel Veículos
- Paleta: Azul marinho `#1D1D1B`, prata/cromado, branco
- 4 versões de logo: cromado (fundo escuro), preto (fundo claro), branco (fundo escuro), símbolo isolado
- Tom: sério, premium, confiável
- Contato principal: Grazi (recebe leads)

### Clincog
- Paleta: Roxo `#7B2D8E`, verde menta `#A8E6CF`, marinho `#1A0A30`, branco
- Mascote IAIA (Integra + IA) para comunicação interna e lúdica
- 6 versões do logo Integra
- Atenção CRP: nunca prometer resultado clínico. "Desenvolvimento", não "tratamento".
- Contatos: Dra. Monica e Dra. Natalie Banaskiwitz

### Curso Passei
- Paleta: Azul marinho `#0D2B5E`, verde menta `#00C896`, branco, cinza claro
- Ramon Matos é o rosto e diferencial — aparece em toda peça
- Público confirmado por pesquisa (Mai/Jun 2026): 90%+ mulheres, pós-grad, 1-2h/dia de estudo
- Geo-segmentação prioritária: Saquarema + Araruama
- Discovery: Instagram > YouTube > Indicação
- Obstáculo principal: falta de tempo + cansaço + filhos

---

## Skills instaladas (.claude/skills/)

27 skills disponíveis, incluindo:

| Skill | Uso |
|-------|-----|
| `/escrita-humanizada` | Obrigatória. Remove 24 padrões de IA do texto |
| `/copy-anuncio` | Cria copy de anúncio para Meta/Google |
| `/copy-pagina-vendas` | Copy de página de vendas completa |
| `/copy-reels` | Script de reels com gancho + corpo + CTA |
| `/pauta-mensal` | Pauta de conteúdo para o mês |
| `/landing-page` | Estrutura de landing page |
| `/script-whatsapp` | Script de atendimento e fechamento |
| `/relatorio-mensal` | Relatório de resultados mensal |
| `/funil-mapeado` | Mapeamento de funil com gargalos |
| `/trafego-meta-ads` | Estratégia de campanhas Meta Ads |
| `/analise-metricas` | Análise de métricas e otimização |
| `/mapa-objecoes` | Mapa de objeções de venda |
| `/reativacao-base` | Campanha de reativação de leads frios |
| `/material-didatico` | Material didático para cursos |
| `/projecao-financeira` | Projeção financeira de campanha |

---

## Entregáveis já produzidos

### Clincog

**Landing Page — Jornada PCN**
- Arquivo: `clientes/clincog/entregas/landing-pages/jornada-pcn.html`
- Evento ao vivo, 25/06/2026, R$ 67, Dra. Natalie Banaskiwitz
- Cores: roxo `#7B2D8E`, verde menta `#A8E6CF`, marinho `#1A0A30`
- Hero com duas fotos iguais lado a lado (Dra. Monica + Dra. Natalie)
- Cards das professoras clicáveis com bio expansível
- Seção "Para Quem É" com 4 cards de público
- Copy Light (sem clichês, CTA específico, sem "Pare de sofrer")
- Garantia incondicional de 7 dias
- Zero travessões, linguagem humanizada

**Mockups de Criativos — Jornada PCN**
- Arquivo: `clientes/clincog/entregas/mockups/jornada-pcn-mockups.html`
- Dashboard interativo com 3 abas: Visão Geral, Estáticos, Vídeos
- 20 criativos estáticos (feed 1:1 + stories 9:16) com switch de formato
- 20 storyboards de vídeo (gancho + corpo + CTA + notas de produção)
- Distribuição de verba: R$ 10k (Meta Ads 70%, Google Ads 30%)
- Timeline: 08/06 a 25/06/2026
- Zero travessões, linguagem humanizada

### Curso Passei
- Briefing completo com dados de pesquisa de público (Mai/Jun 2026, 200+ respondentes)
- Sazonalidade mapeada (12 meses + bancas prioritárias)
- Funil atual com gargalos identificados

---

## Como onboarding de novo cliente funciona

1. Copiar pasta `clientes/_template/` com o nome do cliente
2. Preencher os 4 arquivos: `CLAUDE.md`, `projeto.md`, `sazonalidade.md`, `funil.md`
3. Criar subpastas: `identidade/`, `historico/`, `entregas/`
4. Adicionar cliente no `README.md` raiz
5. Commitar e pushar para a `main`

---

## Status do repositório

- Branch padrão: `main`
- Tudo commitado e disponível para qualquer sessão nova
- CLAUDE.md raiz é carregado automaticamente e define as regras globais
- CLAUDE.md de cada cliente é carregado automaticamente quando se trabalha naquele cliente

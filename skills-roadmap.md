# Skills e Agentes — Roadmap Completo

Cada skill e um comando que qualquer pessoa do time roda no Claude Code.
Cada agente e um fluxo automatizado que combina varias skills.

---

## Maicon (Estrategia / Dono)

| Skill | O que faz |
|-------|-----------|
| `/estrategia` | Gera diagnostico estrategico completo a partir do onboarding do cliente |
| `/planejamento-mensal` | Monta o plano de acoes do mes por cliente (campanhas, conteudo, entregas) |
| `/relatorio-mensal` | Gera relatorio de resultado com ROI para apresentar ao cliente |
| `/briefing-cliente` | Transforma formulario de onboarding em briefing estruturado |
| `/benchmark` | Analisa concorrentes e gera insights acionaveis |

---

## Wiliam (Coordenador / CS / Comercial)

| Skill | O que faz |
|-------|-----------|
| `/onboarding` | Checklist completo de onboarding de novo cliente (acessos, setup, metas) |
| `/status` | Gera visao geral do status de todos os clientes e entregas pendentes |
| `/reuniao` | Prepara pauta da reuniao mensal com cliente (metricas, proximos passos) |
| `/script-whatsapp` | Gera script de primeiro atendimento personalizado por cliente |
| `/follow-up` | Cria sequencia de follow-up D+1, D+3, D+7 |
| `/mapa-objecoes` | Monta mapa de objecoes com respostas prontas |
| `/treinar-comercial` | Gera material de treinamento para equipe de atendimento do cliente |

---

## Julio Cesar (Trafego Pago)

| Skill | O que faz | Integracao |
|-------|-----------|-----------|
| `/campanha-meta` | Cria campanha completa no Meta Ads (objetivo, publico, orcamento, criativos) | MCP Meta Ads |
| `/campanha-google` | Estrutura campanha de Google Ads (search, display) | — |
| `/otimizar` | Analisa metricas e sugere otimizacoes das campanhas ativas | MCP Meta Ads |
| `/negativar` | Pesquisa e sugere termos negativos para campanhas | — |
| `/relatorio-trafego` | Puxa metricas do Meta Ads e gera relatorio semanal/mensal | MCP Meta Ads |
| `/pixel-setup` | Guia de configuracao de pixel e conversoes | — |

---

## Wenderson (Design + Video)

| Skill | O que faz | Integracao |
|-------|-----------|-----------|
| `/briefing-design` | Gera briefing de design a partir da copy aprovada | — |
| `/landing-page` | Cria landing page completa em HTML/CSS e faz deploy | Vercel |
| `/criativos` | Gera briefing detalhado para criativos de anuncio (formatos, textos, CTA) | — |
| `/thumbnail` | Gera briefing de thumbnail com titulo, estilo e referencia | — |
| `/identidade-video` | Template de intro, logo placement e CTA final para videos | — |

---

## Aniki (Social Media)

| Skill | O que faz |
|-------|-----------|
| `/pauta-mensal` | Gera calendario de conteudo do mes (temas, formatos, datas) |
| `/copy-post` | Escreve copy de post para Instagram (carrossel, reels, stories) |
| `/copy-reels` | Roteiro de reels com gancho nos primeiros 3 segundos |
| `/hashtags` | Pesquisa hashtags relevantes por nicho e post |
| `/insight-conteudo` | Analisa o que esta funcionando no nicho e sugere conteudo |

---

## Skills Transversais (Todo o time)

| Skill | O que faz | Integracao |
|-------|-----------|-----------|
| `/copy-anuncio` | Gera copy de anuncio para Meta e Google (varios formatos) | — |
| `/copy-landing` | Escreve copy completa de landing page (headline, beneficios, CTA, FAQ) | — |
| `/copy-webinario` | Roteiro completo de webinario mensal | — |
| `/copy-email` | Sequencia de emails de campanha | — |
| `/copy-whatsapp-grupo` | Copy para disparo em grupos de WhatsApp | — |
| `/novo-cliente` | Fluxo completo de setup de novo cliente no repositorio | — |
| `/publicar-instagram` | Agenda e publica post no Instagram | MCP Instagram |

---

## Agentes Automatizados (Fluxos completos)

### Agente: Lancamento de Campanha
```
Maicon roda /copy-anuncio
    → Copy aprovada
    → /briefing-design (para Wenderson)
    → Wenderson cria criativos
    → /campanha-meta (Julio sobe no Meta Ads)
    → Campanha no ar
```

### Agente: Onboarding de Cliente
```
Cliente preenche formulario
    → /briefing-cliente (gera briefing)
    → /onboarding (gera checklist)
    → /estrategia (gera diagnostico)
    → /planejamento-mensal (primeiro mes)
    → /copy-anuncio (primeiras copies)
    → /landing-page (cria e publica)
    → /campanha-meta (sobe primeira campanha)
```

### Agente: Ciclo Mensal
```
Inicio do mes
    → /planejamento-mensal
    → /pauta-mensal (conteudo)
    → /copy-anuncio (novas copies)
    → /briefing-design (novos criativos)
Meio do mes
    → /otimizar (campanhas)
    → /insight-conteudo (ajustes)
Final do mes
    → /relatorio-trafego (metricas)
    → /relatorio-mensal (resultado)
    → /reuniao (pauta pro cliente)
```

---

## Integracoes Disponiveis

| Plataforma | O que faz | Status |
|------------|-----------|--------|
| **Meta Ads (MCP)** | Criar, otimizar e monitorar campanhas | Disponivel |
| **Vercel** | Deploy de landing pages | Disponivel |
| **Instagram (MCP)** | Publicar posts, stories | Disponivel |
| **GitHub** | Versionamento de tudo | Ativo |

---

## Prioridade de Construcao

### Fase 1 — Fundacao (semana 1)
Skills que desbloqueiam o trabalho imediato com os 2 clientes:
1. `/copy-anuncio` — gerar copies de anuncio
2. `/copy-landing` — copy de landing page
3. `/landing-page` — criar e publicar landing pages
4. `/script-whatsapp` — scripts de atendimento
5. `/mapa-objecoes` — mapa de objecoes

### Fase 2 — Trafego (semana 2)
6. `/campanha-meta` — subir campanhas no Meta Ads
7. `/otimizar` — otimizar campanhas
8. `/relatorio-trafego` — relatorio de performance

### Fase 3 — Conteudo (semana 3)
9. `/pauta-mensal` — calendario de conteudo
10. `/copy-post` — copy de posts Instagram
11. `/copy-reels` — roteiros de reels
12. `/benchmark` — analise de concorrentes

### Fase 4 — Gestao (semana 4)
13. `/planejamento-mensal` — plano mensal
14. `/relatorio-mensal` — relatorio de resultado
15. `/reuniao` — pauta de reuniao
16. `/status` — visao geral dos projetos

# Estrutura para Notion / Planilha — Agência Asher

Use este template para replicar a gestão de projetos no Notion ou Google Sheets.

---

## Database 1: Clientes

| Propriedade | Tipo | Valores |
|-------------|------|---------|
| Nome | Title | — |
| Segmento | Text | — |
| Pacote | Select | Agência (R$3K), Completo (R$6K) |
| Valor Mensal | Number (R$) | — |
| Início do Contrato | Date | — |
| Fim Mínimo | Date | — |
| Status | Select | Onboarding, Ativo, Pausado, Encerrado |
| Instagram | URL | — |
| Site | URL | — |
| Responsável Asher | Person | — |

---

## Database 2: Entregáveis (por cliente, por mês)

| Propriedade | Tipo | Valores |
|-------------|------|---------|
| Entregável | Title | — |
| Cliente | Relation → Clientes | — |
| Categoria | Select | Estratégia, Tráfego, Copy, Design, Vídeo, Inteligência, Comercial, Webinário |
| Mês Referência | Date | — |
| Status | Select | Pendente, Em andamento, Entregue, Aprovado |
| Responsável | Person | — |
| Prazo | Date | — |
| Observações | Text | — |

---

## Database 3: Cronograma Mensal

| Semana | Estratégia | Tráfego | Copy | Design | Vídeo | Inteligência |
|--------|-----------|---------|------|--------|-------|-------------|
| Sem 1 | Diagnóstico / Planejamento | Setup campanhas | Textos de anúncio | Criativos de anúncio | — | Mapeamento de temas |
| Sem 2 | — | Otimização | Copy landing page | Layout landing page | Edição reels | Pauta mensal |
| Sem 3 | — | Otimização + Negativação | Scripts WhatsApp | Artes webinário | Vídeos de anúncio | Benchmarks |
| Sem 4 | Reunião de resultado | Relatório mensal | Follow-up + Objeções | Thumbnails | Edição webinário | Insight mensal |

---

## Views sugeridas para o Notion

### Board (Kanban)
Agrupe por **Status**: Pendente → Em andamento → Entregue → Aprovado

### Calendar
Visualize por **Prazo** para acompanhar deadlines semanais

### Table filtrada por cliente
Uma view para cada cliente com todos os entregáveis do mês

### Timeline
Visualize o cronograma de entregas ao longo do mês

---

## Checklist Mês 1 — Onboarding

### Para todos os clientes:
- [ ] Reunião de kickoff / briefing completo
- [ ] Acesso às contas de anúncio (Google Ads, Meta Ads)
- [ ] Acesso ao Instagram e páginas
- [ ] Materiais da marca (logo, cores, fontes)
- [ ] Definição de metas do mês 1
- [ ] Setup de pixels e conversões
- [ ] Criação da landing page

### Adicional para pacote Completo (R$ 6K):
- [ ] Mapeamento do processo comercial atual
- [ ] Criação dos scripts de atendimento
- [ ] Desenho do funil de vendas digital
- [ ] Agendamento do treinamento da equipe
- [ ] Inclusão no Grupo de Novos Negócios

---

## Clientes Atuais — Dados Rápidos

### Agvel Veículos — Pacote Agência (R$ 3K)
- Segmento: Agência de veículos
- Local: Pato Branco - PR
- Público: Poder aquisitivo alto, maduro
- Entregáveis: 6 + Webinário
- Instagram: @agvel.veiculos

### Clincog — Pacote Completo (R$ 6K)
- Segmento: Clínica de reabilitação neurológica e psiquiátrica
- Público: Pacientes e familiares buscando tratamento individualizado
- Entregáveis: 6 + Webinário + Comercial Digital + Grupo de Negócios
- Instagram: @clincogmais

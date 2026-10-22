# segundo-cerebro-crm-jira-ia
AGENTE de Estudo para consolidar os fundamentos de Lean Startup, Business Model Canvas, Design Thinking e Metodologias Ágeis (Scrum/Kanban) para projetar fluxos de CRM educacionais e comerciais automatizados e integrados com IA dentro do Jira, baseando-se nos diferenciais de plataformas como RD Station, HubSpot e Kommo.
Segundo Cérebro: CRM & Metodologias Ágeis no Jira com Inteligência Artificial

Projeto prático desenvolvido como parte do Desafio da DIO (Digital Innovation One)
 para construção de um Segundo Cérebro no Google NotebookLM, combinando metodologias de gestão, arquitetura de CRM de mercado e automação com IA no Jira.

🎯 Tema e Objetivo
Tema

Arquitetura de CRM e Metodologias Ágeis aplicadas ao Jira com Automações e Inteligência Artificial.

Objetivo em Uma Frase

"Consolidar os fundamentos de Lean Startup, Business Model Canvas, Design Thinking e Metodologias Ágeis (Scrum/Kanban) para projetar fluxos de CRM educacionais e comerciais automatizados e integrados com IA dentro do Jira, baseando-se nos diferenciais de plataformas como RD Station, HubSpot e Kommo."

🔍 Critérios de Curadoria

Para garantir que o NotebookLM forneça respostas com alta fidelidade técnica e sem alucinações, foi estabelecido um filtro rigoroso de seleção de fontes:

Autoridade e Procedência: Fontes de documentação técnica oficial (Atlassian, RD Station, HubSpot, Kommo) e literaturas canônicas de processos ágeis e inovação (Scrum Guide, Lean Startup, Strategyzer).
Aplicabilidade Operacional: Materiais que expliquem a mecânica prática de pipeline, transição de status, modelagem de dados (contatos, negócios, tickets) e regras de negócio.
Foco em Automações e IA: Documentos detalhando APIs, Webhooks, triggers/actions (Smart Values do Jira) e orquestração de IA.
Isenção e Densidade Técnica: Eliminação de conteúdos superficiais, materiais estritamente de marketing comercial ou vídeos promocionais de vendas.
📚 Fontes Que Entraram no Caderno
Tipo	Fonte / Título	Origem / Autor	Justificativa de Confiança
Texto	Jira Automation & Smart Values Documentation	Atlassian Oficial	Documentação canônica sobre regras, condições, webhooks e IA nativa no ecossistema Atlassian.
Texto	CRM Architecture & Object Modeling Guide	HubSpot Academy	Referência global em modelagem de dados para pipelines de vendas, contatos e propriedades personalizadas.
Texto	Guia de Automação de Marketing e Event APIs	RD Station Developers	Documentação oficial líder no mercado nacional para Inbound Marketing, Lead Scoring e gatilhos de conversão.
Texto	Conversational CRM & Pipeline Architecture	Kommo Developers	Documentação técnica referência em pipelines conversacionais e automação de mensageria (WhatsApp/Direct).
Texto	Scrum Guide & Kanban Essential Guide	Scrum.org / David Anderson	Diretrizes oficiais sobre cadência, limites de WIP e fluxo de valor aplicados à gestão de processos.
Texto	Business Model Canvas & Value Proposition Design	Strategyzer (Osterwalder)	Framework oficial para modelagem de fluxos de jornada de valor em ecossistemas comerciais e educacionais.
Vídeo	Automation in Jira: Best Practices & Integrations	Atlassian Summit (YouTube)	Casos reais de engenharia de automação sem código e integrações via API com inteligência artificial.
Vídeo	CRM Pipeline Architecture Masterclass	HubSpot Academy (YouTube)	Aulas técnicas focadas em desenho de processos comerciais, automação e esteiras de vendas.
Vídeo	Building a CRM inside Jira Service Management	Atlassian Certified Admin (YouTube)	Estudo de caso prático demonstrando parametrização de tipos de itens, campos customizados e esteiras de leads.
🤖 Diretriz de Comportamento (Prompt do Caderno)

Para calibrar o comportamento do agente no NotebookLM, foi configurada a seguinte diretriz de sistema:

text
Você é um especialista sênior em Arquitetura de CRM, Metodologias Ágeis e Engenharia de Processos no Jira com Inteligência Artificial. Seu papel é analisar, comparar e estruturar arquiteturas de CRM (comercial e educacional) baseando-se estritamente nas fontes fornecidas. Ao propor soluções, demonstre como conectar os frameworks (Lean, BMC, Kanban, Scrum) à configuração prática do Jira (Issue Types, Campos Customizados, Automações e Smart Values) e compare com os diferenciais de mercado (HubSpot, RD Station e Kommo). Sempre cite as fontes de onde as regras e conceitos foram extraídos.
💬 Diálogo com as Fontes (Perguntas, Respostas e Citações)

Abaixo estão registradas as perguntas estratégicas feitas ao caderno, acompanhadas das sínteses das respostas e das respectivas fontes citadas:

1. Aplicação de Kanban e Lean no Pipeline do Jira
Pergunta: "Como os conceitos de Fluxo de Valor do Lean e limites de WIP do Kanban devem ser aplicados na criação das colunas e status de um pipeline de CRM no Jira?"
Resposta Resumida: O caderno correlacionou que, no Jira, cada coluna do quadro Kanban de CRM deve representar um estado de valor explícito no ciclo de vida do lead (ex: Qualificado, Diagnóstico, Proposta, Fechado). O limite de WIP (Work in Progress) impede que consultores acumulem oportunidades travadas, forçando a resolução de gargalos antes da entrada de novos leads.
Fontes Citadas: Scrum Guide & Kanban Essential Guide, Atlassian Jira Documentation.
2. Diferenciais de Mercado (RD, HubSpot, Kommo) adaptados ao Jira
Pergunta: "Quais são os principais diferenciais nativos de automação do RD Station (Lead Scoring), HubSpot (Pipelines de Vendas) e Kommo (Mensageria/WhatsApp) que podem ser adaptados dentro do Jira utilizando Jira Automation, Smart Values e Webhooks?"
Resposta Resumida:
RD Station: O lead scoring pode ser reproduzido no Jira criando um Custom Field numérico atualizado via webhook a cada interação do usuário.
HubSpot: A esteira de negócios com transições automáticas de estágio é implementada via triggers de eventos no Jira Automation.
Kommo: O pipeline conversacional pode ser emulado conectando a API do WhatsApp a um webhook do Jira que gera ou atualiza tickets em tempo real.
Fontes Citadas: RD Station Developers, HubSpot CRM Architecture, Kommo Developers, Jira Automation Guides.
3. CRM Educacional e Combate à Evasão com Design Thinking
Pergunta: "Como utilizar o Design Thinking e o Business Model Canvas para mapear a jornada de matrícula, onboarding e combate à evasão de alunos, traduzindo essa experiência em tickets e automações no Jira Service Management?"
Resposta Resumida: O Design Thinking estrutura o mapa de empatia e os pontos de dor do aluno na fase de adaptação. No Jira Service Management, criam-se tipos de chamado específicos (ex: Dúvida Pedagógica, Risco de Evasão). Se um aluno demonstrar inatividade ou registrar múltiplos chamados sem resolução, uma automação eleva o SLA e notifica o time de retenção.
Fontes Citadas: Strategyzer BMC, Atlassian Jira Service Management Guides.
4. Orquestração e Integração com Agentes de IA
Pergunta: "Como estruturar uma automação no Jira que receba eventos de novos leads via webhook, consulte um modelo de IA externa para qualificação e atualize o ticket com a recomendação da próxima ação?"
Resposta Resumida: O fluxo utiliza o gatilho Incoming Webhook do Jira Automation, despacha os dados via Send Web Request para o endpoint da IA com prompt contextualizado e, no retorno, utiliza Smart Values como {{webhookResponse.body.summary}} para preencher os campos do ticket e definir prioridade automática.
Fontes Citadas: Atlassian Jira Automation & Smart Values Documentation.
📂 Materiais Gerados e Evidências

Todos os artefatos produzidos no Estúdio do NotebookLM e as comprovações de citação estão salvos no repositório:

📊 Mapa Mental e Diagrama de Fluxo: Arquivo em assets/mapa-mental-crm-jira.png 
<img width="6319" height="5043" alt="NotebookLM Mind Map_1" src="https://github.com/user-attachments/assets/ff6f9e2d-0c89-4657-87e9-1102ca2893ca" />

📄 Guia de Estudos & Slides: Documento em assets/guia-de-estudo-e-slides.pdf
[Guia_AGENTE_Estudo_CRM_Jira_IA.pdf]
(https://github.com/user-attachments/files/33844553/Guia_AGENTE_Estudo_CRM_Jira_IA.pdf)

📸 Evidências de Citações do Chat: Capturas de tela demonstrando o suporte estrito das fontes salvas na pasta assets/prints/.
🔗 Link do Notebook Compartilhado https://notebook.google.com/notebook/012a4d6b-9222-4823-ac58-a6040833473f

O caderno de estudos pode ser acessado no link público abaixo (configurado como somente leitura e sem dados sensíveis):

👉 Acessar Caderno de Estudos no Google NotebookLM
 (https://notebook.google.com/notebook/012a4d6b-9222-4823-ac58-a6040833473f)

🛠️ Tecnologias e Frameworks Utilizados
Google NotebookLM (Curadoria e RAG de documentos)
Jira Software & Jira Service Management (Modelagem de processos e automações)
Frameworks: Lean Startup, Business Model Canvas (BMC), Scrum e Kanban
Plataformas de Referência: RD Station, HubSpot e Kommo
Engenharia de Automação: Jira Automation, Smart Values, Webhooks e APIs de Inteligência Artificial

Desenvolvido por Seu Nome
 durante o Bootcamp DIO.

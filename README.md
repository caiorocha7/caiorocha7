## Caio Rocha

**Engenheiro de Software · Backend Python & Full Stack · Integrações e IA aplicada**<br>
Teresina, Brasil · aberto a oportunidades remotas

16 meses de experiência em um SaaS multi-tenant em produção, com Python/FastAPI, Angular, MySQL e AWS.
Formação em Engenharia de Software e pós-graduação em Inteligência Artificial (iCEV).

**Portfólio:** [caiorocha7.github.io/caio-rocha-portfolio](https://caiorocha7.github.io/caio-rocha-portfolio/) ·
**LinkedIn:** [linkedin.com/in/caioroch](https://linkedin.com/in/caioroch) ·
**E-mail:** [caiovinicios82@gmail.com](mailto:caiovinicios82@gmail.com)

### Experiência profissional

**MetaMundi · Desenvolvedor de Software (Full Stack) · jul/2025 a nov/2026**<br>
CRMundi e ChatMundi: SaaS multi-tenant de gestão comercial, financeira e atendimento WhatsApp para agências de viagem.

- Atendimento WhatsApp dentro do CRM com Chatwoot e Evolution API, com provisionamento idempotente por tenant.
- Microsserviço FastAPI para conversas, trocando polling por WebSocket autenticado por tenant.
- Distribuição Round Robin transacional no MySQL, ativada por tenant em fases (OFF, SHADOW, ENFORCE).
- Controle de acesso legado migrado para uma matriz RBAC central em 11 módulos de duas aplicações.
- Assistente com LLM em que o modelo só classifica a intenção e os números vêm de consultas pré-definidas.
- Numeração de ordens de serviço sem colisões sob concorrência e faturamento com PDF em AWS Lambda.

Produto proprietário, sem repositório público. Detalhes no
[estudo de caso](https://caiorocha7.github.io/caio-rocha-portfolio/pt/experience/crmundi/).

### Projetos pessoais

| Projeto | O que faz | Stack |
|---|---|---|
| [**DocPilot AI**](https://github.com/caiorocha7/docpilot-ai) | Perguntas sobre documentos com citações verificáveis (RAG), extração estruturada e revisão humana. | Next.js · FastAPI · pgvector · Celery · Ollama |
| [**ConnectHub**](https://github.com/caiorocha7/connecthub-integrations) | Webhooks assinados com outbox transacional, idempotência, retentativas e reprocessamento. | Angular · FastAPI · PostgreSQL · Redis · Celery |
| [**RouteOps**](https://github.com/caiorocha7/routeops-fullstack) | Gestão logística com regras de negócio no servidor, mapa com rastreamento simulado e relatórios. | React · NestJS · Prisma · PostgreSQL |

Os três têm testes automatizados, CI no GitHub Actions e limitações documentadas no README.

### Tecnologias

- **Backend:** Python, FastAPI, SQLAlchemy, Alembic, MySQL, PostgreSQL, Pytest
- **Frontend:** Angular, TypeScript, PrimeNG; React e Next.js nos projetos pessoais
- **Integrações e IA:** Chatwoot, Evolution API, webhooks, WebSocket, n8n, LLMs; RAG e pgvector nos projetos pessoais
- **Cloud e segurança:** AWS (Lambda, S3, ECS, EventBridge), Docker, GitLab CI, GitHub Actions, JWT/JWKS, RBAC

---

<sub>English: Software Engineer (Python backend and full stack) with 16 months on a multi-tenant SaaS in production,
based in Teresina, Brazil, open to remote roles. See the [portfolio](https://caiorocha7.github.io/caio-rocha-portfolio/en/).</sub>

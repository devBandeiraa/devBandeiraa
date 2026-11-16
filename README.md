<!-- PERFIL · Jhordan Gabriel Bandeira · github.com/devBandeiraa -->

<div align="center">

<img src="./assets/header.svg" width="100%" alt="Jhordan Gabriel Bandeira — Desenvolvedor Backend Júnior · Node.js · TypeScript · NestJS"/>

<br/><br/>

<a href="https://www.linkedin.com/in/jhordan-bandeira"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:jhordanbandeira1@gmail.com"><img src="https://img.shields.io/badge/Email-161B22?style=for-the-badge&logo=gmail&logoColor=3FB950" alt="Email"/></a>
<a href="https://reconcilia-seven.vercel.app"><img src="https://img.shields.io/badge/Reconcilia-demo_ao_vivo-161B22?style=for-the-badge&labelColor=161B22&color=3FB950" alt="Reconcilia: demo ao vivo"/></a>
<img src="https://img.shields.io/badge/Aberto_a_vagas-remoto_%7C_h%C3%ADbrido_%7C_presencial-3FB950?style=for-the-badge" alt="Aberto a vagas: remoto, híbrido ou presencial"/>

<br/><br/>

<img src="https://skillicons.dev/icons?i=ts,nodejs,nestjs,express,postgres,prisma,docker,githubactions,react,nextjs&perline=10&theme=dark" alt="TypeScript, Node.js, NestJS, Express, PostgreSQL, Prisma, Docker, GitHub Actions, React, Next.js"/>

</div>

## Sobre

**Desenvolvedor Backend Júnior (Node.js, TypeScript e NestJS)** com experiência em pagamentos, integrações e IA aplicada; atuo também no frontend com React.

Passei 6 meses rastreando pedidos que travavam entre e-commerce, gateway de pagamento e ERP, com mais de 15 incidentes por semana em 5 lojas. Depois construí o sistema que eu queria ter naquela época: o **[Reconcilia](https://github.com/devBandeiraa/reconcilia)**.

| | |
|---|---|
| **Hoje** | Fullstack & AI Engineer na BNW: backend de uma plataforma SaaS em Node.js e TypeScript e agentes de IA com tool calling |
| **Busco** | Vagas de backend ou full stack em fintechs, empresas de IA e startups |
| **Onde** | Boituva, SP · remoto, híbrido ou presencial em Sorocaba e região |
| **Formação** | Ciência da Computação · UNIP · conclusão em 2027 |
| **Estudando** | RAG e IA com Python |

<div align="center">

| **15+** | **5** | **10–15** | **115** |
|:---:|:---:|:---:|:---:|
| incidentes por semana<br/>resolvidos em produção | lojas SFCC<br/>sustentadas em paralelo | consultas SQL otimizadas<br/>por semana | testes automatizados<br/>no Reconcilia |

</div>

## Projeto em destaque

### [Reconcilia](https://github.com/devBandeiraa/reconcilia) · conciliação de pagamentos com IA

[Demo ao vivo](https://reconcilia-seven.vercel.app) · [Documentação da API](https://reconcilia-api.onrender.com/docs) · [Código](https://github.com/devBandeiraa/reconcilia)

Encontra pagamentos que não batem entre loja, gateway e ERP. Um agente de IA investiga cada caso e a correção só é executada depois que uma pessoa aprova.

- **Quatro falhas detectadas:** webhook perdido, webhook duplicado, valor divergente e captura de pedido já cancelado
- **Idempotência no banco:** o mesmo webhook 50 vezes em paralelo vira 1 linha, 1 job e 1 aplicação
- **Ledger em partidas dobradas** que sempre fecha em zero, garantido por trigger no PostgreSQL
- **Agente de IA só de leitura:** as ferramentas rodam em transação `READ ONLY` e a ação só é executada após aprovação humana, com auditoria
- **115 testes automatizados**, 97 deles contra um PostgreSQL real, com CI no GitHub Actions e 14 decisões de arquitetura documentadas (ADRs)
- **No ar com custo zero:** web na Vercel, API e worker no Render, banco na Neon

`NestJS` `Next.js` `TypeScript` `Prisma` `PostgreSQL` `pg-boss` `Zod` `Vitest` `LLMs`

## Outros projetos

| Projeto | O que faz | Stack |
|---|---|---|
| **[Hash Financeiro](https://github.com/devBandeiraa/hash-financeiro)** | Finanças pessoais com um agente de IA que consulta os dados reais do usuário por um servidor MCP próprio com OAuth; dados isolados por RLS | TypeScript, React 19, TanStack Start, Supabase, MCP |
| **[ticket-platform](https://github.com/devBandeiraa/ticket-platform)** | Venda de ingressos em microsserviços sem overselling: `UPDATE` condicional no PostgreSQL, 356 testes com Testcontainers e 200 threads disputando o mesmo estoque | Java 17, Spring Boot 3, PostgreSQL, Redis, RabbitMQ, Kubernetes |
| **[backend-challenge](https://github.com/devBandeiraa/backend-challenge)** | Processador de transações financeiras via HTTP e SQS, correto com eventos duplicados, fora de ordem e 3+ instâncias concorrentes | Bun, TypeScript, NestJS, PostgreSQL |
| **[Help Desk Pro](https://github.com/devBandeiraa/help-desk)** | Sistema de chamados no ar, com JWT e refresh token, permissões por papel (RBAC) e dashboard analítico | Node.js, Express, Prisma, React |
| **[emporio-da-musica-agent](https://github.com/devBandeiraa/emporio-da-musica-agent)** | Agente de atendimento para uma loja fictícia, com function calling sobre ferramentas tipadas e evals | Python, Gemini |
| **[FlexAuction](https://github.com/devBandeiraa/flexauction-platform)** | Leilões online com lances em tempo real via WebSocket e anti-sniping | Node.js, Express, Prisma, React 19 |
| **Orlatech** · código privado | Site e gestão comercial para imobiliárias, em sociedade; sou o responsável técnico | Next.js, Payload CMS, PostgreSQL, Docker |

## Experiência

**Fullstack & AI Engineer · BNW** &nbsp;·&nbsp; `jul/2026 – atual` · remoto · PJ

- Desenvolvo o backend de uma plataforma SaaS multi-cliente e white-label para agências, em Node.js e TypeScript
- Construo agentes de IA com tool calling que pesquisam empresas e decisores, enriquecem dados via APIs e pontuam leads por perfil de cliente ideal (ICP)
- Integro LLMs para personalizar mensagens, classificar respostas e automatizar follow-ups de prospecção B2B

**Desenvolvedor Backend Jr B2C · Backlgrs** &nbsp;·&nbsp; `jan/2026 – jul/2026` · remoto

- Atendi mais de 15 incidentes por semana em produção em 5 lojas Salesforce Commerce Cloud, rastreando o pedido entre plataforma, ERP e gateway até a causa-raiz
- Mantive integrações com ERP, Anymarket, Intelipost e o gateway Braspag (Pix, cartão e parcelamento) e implementei o método de pagamento JS Card no checkout
- Automatizei jobs de sincronização de pedidos, pagamentos e estoque com o ERP

**Desenvolvedor de Software, Dados e Integrações · Guardian RH** &nbsp;·&nbsp; `jul/2024 – jan/2026` · estágio remoto

- Otimizei e corrigi de 10 a 15 consultas SQL por semana em Oracle e SQL Server
- Construí pipelines de ETL com Azure Data Factory em migrações entre sistemas corporativos (TOTVS RM, Protheus e SAP)

## Stack

| Área | Tecnologias |
|---|---|
| **Backend** | Node.js, TypeScript, JavaScript, NestJS, Express, APIs REST, webhooks, filas (pg-boss), idempotência, Swagger/OpenAPI |
| **Dados** | PostgreSQL, Prisma, SQL avançado (Oracle e SQL Server), Supabase, Azure Data Factory |
| **Testes e DevOps** | Vitest, Supertest, Testcontainers, Docker, CI/CD com GitHub Actions, Git |
| **IA aplicada** | Agentes com tool calling, integração de LLMs (Anthropic e Gemini), MCP com OAuth, Claude Code |
| **Frontend** | React, Next.js, TanStack Start, Vue.js, Tailwind CSS |
| **Também** | Java 17 e Spring Boot 3, Redis, RabbitMQ, Kubernetes, Salesforce Commerce Cloud (SFRA, ISML) |

## Formação e certificações

- **Ciência da Computação** · UNIP · conclusão em 2027
- **Oracle Cloud Infrastructure 2025 Foundations Associate** · Oracle
- **Claude Code** e **Claude** · Anthropic · 2026
- **Idiomas:** português nativo · inglês intermediário (leitura técnica e escrita)

## GitHub

<div align="center">

<img src="./profile-summary-card-output/github_dark/2-most-commit-language.svg" width="49%" alt="Linguagens mais usadas nos commits"/>

</div>

## Contato

Aberto a vagas de backend ou full stack. Fale comigo pelo [LinkedIn](https://www.linkedin.com/in/jhordan-bandeira) ou por [e-mail](mailto:jhordanbandeira1@gmail.com).

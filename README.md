<!-- PERFIL · Jhordan Gabriel Bandeira · github.com/devBandeiraa -->

<div align="center">

<img src="./assets/header.svg" width="100%" alt="Jhordan Gabriel Bandeira — Backend Developer · Java · Spring Boot"/>

<br/>

<a href="https://www.linkedin.com/in/jhordan-bandeira"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:jhordanbandeira1@gmail.com"><img src="https://img.shields.io/badge/Email-0F172A?style=for-the-badge&logo=gmail&logoColor=10B981"/></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0EA5E9,100:10B981&height=3&width=100%" width="100%"/>

## `> whoami`

```java
public class Jhordan {

    String cargo       = "Desenvolvedor Backend Júnior";
    String local       = "Boituva, SP · remoto, híbrido ou presencial (Sorocaba e região)";
    String formacao    = "Ciência da Computação · UNIP · dez/2026";
    int    experiencia = 2; // anos: e-commerce em produção + dados corporativos

    List<String> foco = List.of(
        "Java e Spring Boot",
        "concorrência e consistência entre microsserviços",
        "testes de integração com infraestrutura real"
    );

    String abordagem() {
        return "entender a arquitetura antes de mexer no código, "
             + "e seguir o problema até a causa, não só o sintoma";
    }
}
```

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:10B981,100:0EA5E9&height=3&width=100%" width="100%"/>

## `> projeto em destaque`

### 🎫 [ticket-platform](https://github.com/devBandeiraa/ticket-platform)

**Venda de ingressos em microsserviços, sem vender o mesmo assento duas vezes.**

- 🔒 Garantia no PostgreSQL: `UPDATE` condicional + `CHECK constraint`. O lock em Redis é só otimização
- 🧪 **356 testes** com PostgreSQL, Redis e RabbitMQ reais via Testcontainers, com **200 threads** disputando o mesmo estoque
- 📬 Transactional outbox, idempotência, DLQ, circuit breaker e retry com jitter
- 📈 Traces com OpenTelemetry e painéis Prometheus/Grafana
- ⚙️ CI no GitHub Actions · 89% de cobertura

<div align="center">

<img src="./assets/terminal.svg" width="90%" alt="Terminal executando o ticket-platform: 356 testes, zero overselling"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0EA5E9,100:10B981&height=3&width=100%" width="100%"/>

## `> outros projetos`

<div align="center">

<a href="https://github.com/devBandeiraa/ticket-platform"><img src="https://github-readme-stats.vercel.app/api/pin/?username=devBandeiraa&repo=ticket-platform&title_color=10B981&icon_color=0EA5E9&text_color=C9D1D9&bg_color=0D1117&border_color=1F2A48"/></a>
<a href="https://github.com/devBandeiraa/hash-financeiro"><img src="https://github-readme-stats.vercel.app/api/pin/?username=devBandeiraa&repo=hash-financeiro&title_color=10B981&icon_color=0EA5E9&text_color=C9D1D9&bg_color=0D1117&border_color=1F2A48"/></a>
<a href="https://github.com/devBandeiraa/flexauction-platform"><img src="https://github-readme-stats.vercel.app/api/pin/?username=devBandeiraa&repo=flexauction-platform&title_color=10B981&icon_color=0EA5E9&text_color=C9D1D9&bg_color=0D1117&border_color=1F2A48"/></a>
<a href="https://github.com/devBandeiraa/help-desk"><img src="https://github-readme-stats.vercel.app/api/pin/?username=devBandeiraa&repo=help-desk&title_color=10B981&icon_color=0EA5E9&text_color=C9D1D9&bg_color=0D1117&border_color=1F2A48"/></a>

</div>

| Projeto | O que é | Stack |
|---|---|---|
| 💰 **Hash Financeiro** | Gestor financeiro com agente de IA e servidor MCP próprio com OAuth | TanStack Start · Supabase · MCP |
| 🛰️ **FlexAuction** | SaaS para casas de leilão com lances em tempo real via WebSocket | Node.js · TypeScript · React · Prisma |
| 🎟️ **Help Desk Pro** | Sistema de chamados com JWT, RBAC e dashboard analítico | Node.js · TypeScript · React · Prisma |

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:10B981,100:0EA5E9&height=3&width=100%" width="100%"/>

## `> stack`

<div align="center">

<img src="https://skillicons.dev/icons?i=java,spring,postgres,redis,rabbitmq,docker,kubernetes,githubactions,prometheus,grafana&perline=10&theme=dark"/>
<br/>
<img src="https://skillicons.dev/icons?i=nodejs,ts,react,git,github,maven,postman,idea,vscode&perline=10&theme=dark"/>

</div>

```yaml
backend:        [Java 17, Spring Boot 3, Spring Data JPA, Hibernate, Spring Security/JWT, Spring Cloud Gateway, Node.js]
arquitetura:    [APIs RESTful, Microsserviços, Transactional Outbox, Idempotência, Resilience4j, OpenAPI]
dados:          [PostgreSQL, Oracle, SQL Server, Redis, RabbitMQ, Flyway, Azure Data Factory]
testes:         [JUnit 5, Mockito, Testcontainers, JaCoCo]
devops:         [Docker, Docker Compose, Kubernetes, GitHub Actions, OpenTelemetry, Prometheus, Grafana]
tambem:         [React, TypeScript, Salesforce Commerce Cloud, Claude Code, MCP]
cloud:          [OCI 2025 Foundations Associate]
```

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0EA5E9,100:10B981&height=3&width=100%" width="100%"/>

## `> stats`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=devBandeiraa&show_icons=true&count_private=true&title_color=10B981&icon_color=0EA5E9&text_color=C9D1D9&bg_color=0D1117&border_color=1F2A48"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=devBandeiraa&layout=compact&langs_count=6&hide=html,css,dockerfile,shell&title_color=10B981&text_color=C9D1D9&bg_color=0D1117&border_color=1F2A48"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=devBandeiraa&bg_color=0D1117&color=10B981&line=0EA5E9&point=F59E0B&area=true&hide_border=true" width="95%"/>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/devBandeiraa/devBandeiraa/output/github-contribution-grid-snake-dark.svg"/>
  <img alt="Snake animation" src="https://raw.githubusercontent.com/devBandeiraa/devBandeiraa/output/github-contribution-grid-snake.svg" width="95%"/>
</picture>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:10B981,100:0EA5E9&height=3&width=100%" width="100%"/>

## `> git log --experiencia`

<details>
<summary>📂 &nbsp;<b>Experiência Profissional</b> &nbsp;—&nbsp; <i>clique para expandir</i></summary>

<br/>

### Desenvolvedor Backend Júnior — Backlgrs
`jan/2026 – jun/2026` · Remoto · Sustentação e evolução de e-commerce B2C em Salesforce Commerce Cloud (SFCC)

- Mais de **15 incidentes por semana** em produção, distribuídos entre **cinco projetos simultâneos**, rastreando o pedido entre plataforma, ERP e gateway até o ponto de falha, com correção validada em sandbox antes do deploy
- Integrações com ERP, hub de marketplaces (Anymarket), plataforma de frete (Intelipost) e gateway Braspag, cobrindo Pix, cartão e parcelamento
- Automação de jobs de sincronização de pedidos, pagamentos e estoque com o ERP
- Funcionalidades e correções no back-end (JavaScript/SFRA e Node.js), validações de checkout e correção de timezone em pedidos
- Migração do front-end de Bootstrap 4 para 5 sem impacto na navegação
- Pull requests, code review e Scrum via Jira, com Claude Code e Cursor no debugging e na refatoração

### Desenvolvedor de Software, Dados e Integrações (Estágio) — Guardian RH
`jul/2024 – jan/2026` · Remoto · Dados corporativos com TOTVS RM, Protheus e SAP

- Consultas SQL em Oracle e SQL Server (joins complexos, subqueries, procedures, funções analíticas) para grandes volumes de dados
- Diagnóstico de queries com resultado incorreto ou gargalo de performance
- Pipelines de ETL com Azure Data Factory para migração de dados entre sistemas
- Suporte técnico em dados, relatórios e integrações; dashboards e documentação de rotinas

</details>

<details>
<summary>🌐 &nbsp;<b>Idiomas</b> &nbsp;—&nbsp; <i>clique para expandir</i></summary>

<br/>

- **Português:** nativo
- **Inglês:** intermediário (leitura de documentação técnica e comunicação escrita)

</details>

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:10B981,50:0EA5E9,100:0F172A&height=130&section=footer"/>

</div>

## Olá, eu sou o Mateus 👋

Desenvolvedor full stack em **C#/.NET** e **Angular**. Hoje sou estagiário de TI na **Vale**, onde desenvolvo e sustento um sistema interno usado por mais de 300 pessoas da operação ferroviária. Formando em Sistemas de Informação pela UVV (dez/2026).

Gosto de projeto que vai do primeiro commit até o deploy — arquitetura, testes, pipeline, e o que quebra em produção.

📍 Vila Velha, ES &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/mateus-sarmento-hora) &nbsp;·&nbsp; contato.sarmento@hotmail.com

---

### 🛠️ Stack

| | |
|---|---|
| **Back-end** | C#, .NET 8, ASP.NET Core, Entity Framework Core, APIs REST, Clean Architecture, FluentValidation, JWT |
| **Front-end** | Angular 18, Angular Material, TypeScript, SCSS, RxJS |
| **Bancos de dados** | SQL Server, MySQL, PostgreSQL |
| **Testes** | xUnit, Moq |
| **DevOps** | Docker, GitHub Actions, CI/CD, Fly.io, Azure, Git |
| **Também uso** | JavaScript, PHP, Python, Power BI, Power Apps |

---

### ☕ Caféscore

Plataforma para avaliar o café servido em clínicas médicas. Projeto autoral, construído de ponta a ponta — da modelagem ao deploy.

**🔗 Aplicação no ar:** **[cafescore-app.vercel.app](https://cafescore-app.vercel.app)**

| Repositório | Stack |
|---|---|
| [`cafescore-api`](https://github.com/sarmentin/cafescore-api) | .NET 8 · Clean Architecture · EF Core · JWT · xUnit |
| [`cafescore-app`](https://github.com/sarmentin/cafescore-app) | Angular 18 · Angular Material · TypeScript · SCSS |

O backend segue **Clean Architecture** em quatro camadas (Domain, Application, Infrastructure, API), com autenticação **JWT** e hash BCrypt, validação com **FluentValidation**, **rate limiting**, tratamento centralizado de exceções, documentação em **Swagger** e testes unitários em **xUnit + Moq**.

O frontend é **mobile-first**, com lazy loading em todas as rotas, interceptor de JWT e guards de autenticação.

#### 🐳 Sobre a infraestrutura

O primeiro deploy foi em **Azure App Service** com **Azure SQL**. Quando os créditos acabaram, a aplicação saiu do ar — e em vez de só trocar de provedor, empacotei a API em um **Dockerfile multi-stage** e migrei para o **Fly.io**, com deploy automático via **GitHub Actions**.

A conteinerização resolveu o problema imediato e deixou o projeto portátil: hoje ele sobe em qualquer lugar que rode container, sem depender de um provedor específico. Foi o aprendizado mais útil do projeto inteiro, e veio de uma coisa quebrando.

---

### 🏥 UVV Saúde

Plataforma de agendamento de consultas de nutrição e psicologia para o campus da UVV, construída em **equipe de 7 pessoas** na disciplina de Desenvolvimento Web 2.

Node.js, TypeScript, Express, PostgreSQL e Next.js, com repositório compartilhado, contrato de API definido antes da implementação e divisão de responsabilidades entre os integrantes.

[`UVV-Saude`](https://github.com/sarmentin/UVV-Saude)

---

### 🎯 No que estou trabalhando

- **Fase 2 do Caféscore** — geolocalização com check-in obrigatório (avaliar só estando na clínica) e upload de fotos
- Aprofundando testes automatizados e boas práticas de arquitetura em .NET
- Inglês, com foco em conversação

---

<sub>Aberto a oportunidades como desenvolvedor full stack júnior em .NET e Angular, na Grande Vitória.</sub>

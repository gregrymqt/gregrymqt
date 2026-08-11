<div align="center">
  <h1>Lucas Vicente</h1>
  <p><b>Desenvolvedor Back-End | .NET 8 (C#) · Python (FastAPI) · Go (Golang)</b></p>
  <p><i>Arquitetura de Software · Microsserviços · Resiliência & Processamento Distribuído</i></p>
  <p>
    <a href="https://www.linkedin.com/in/lucas-vicente-dev/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:lucasvicentedesouza021@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  </p>
</div>

---

### 👤 Sobre Mim
Estudante de Desenvolvimento de Software Multiplataforma na **FATEC Praia Grande**. Atuo focado na construção de sistemas Back-End de alta performance, microsserviços resilientes e pipelines de dados assíncronos.

Atuo principalmente com o ecossistema **.NET 8 (C#)**, **Python (FastAPI)** e **Go (Golang)**, aplicando padrões como *Clean Architecture*, *Vertical Slice Architecture*, *SOLID*, resiliência com *Polly* e *Padrão AAA* para testes unitários.

---

### 🛠️ Toolbox & Stack Técnica

| Categoria | Tecnologias |
|---|---|
| **Back-End** | `C# (.NET 8 / ASP.NET Core)` · `Python (FastAPI)` · `Go (Golang)` |
| **IA & Mensageria** | `RabbitMQ` · `LLM APIs (OpenAI, Gemini, DeepSeek, Groq)` · `SSE` · `SignalR` |
| **Bancos de Dados & Cache** | `PostgreSQL` · `SQL Server` · `MongoDB` · `Redis (Cache Aside / PubSub)` |
| **DevOps & Infra** | `Docker` · `Kubernetes (Kind)` · `GitHub Actions` · `Linux` |
| **Qualidade & Resiliência** | `xUnit / NUnit` · `Moq` · `Polly (Retry & Circuit Breaker)` |
| **Front-End (Complementar)** | `React` · `TypeScript` · `Tailwind CSS` · `Vite` |

---

### 🚀 Projetos em Destaque

#### 🤖 [E-commerce Bot](https://github.com/gregrymqt/ecomerce-bot)
> **Plataforma de Ingestão, Enriquecimento via IA (LLMs) & Processamento Assíncrono Multi-Tenant**
* **O Problema:** Automação de extração (scraping), enriquecimento contextual de produtos e sincronização de catálogos de e-commerce com suporte multi-tenant e alto volume de dados.
* **A Solução:** Arquitetura Monorepo Full-Stack (FastAPI + React 18). Arquitetei um pipeline assíncrono baseado em **Domain-Driven Design (DDD)** com pool de 3 workers desacoplados via **RabbitMQ** (`ScraperWorker`, `ProcessorWorker` e `ExporterWorker`). Implementei gateway com fallback para LLMs (DeepSeek, Llama 3.3, Gemini), criptografia **AES-256 GCM** para chaves de API por tenant (BYOK) e monitoramento em tempo real via **Server-Sent Events (SSE)**.
* **Tech Stack:** `Python` · `FastAPI` · `React 18` · `TypeScript` · `RabbitMQ` · `Redis` · `PostgreSQL` · `Docker`

#### 🛒 [Greg Company Ecosystem](https://github.com/gregrymqt)
> **E-commerce & Processamento de Pagamentos Resilientes em Tempo Real**
* **O Problema:** Tratar instabilidades em gateways de pagamento externos e garantir respostas em tempo real para o cliente.
* **A Solução:** Plataforma de e-commerce com **Checkout Transparente (Mercado Pago)**. Utilizei **.NET 8** com Clean Architecture, microsserviço em **Go** via RabbitMQ para processamento assíncrono, resiliência a falhas de API com **Polly** (Retry & Circuit Breaker) e atualizações reativas via **SignalR**.
* `.NET 8` · `C#` · `Go` · `RabbitMQ` · `Polly` · `MongoDB` · `Redis` · `React`

#### 🌊 [Bueiro Inteligente](https://github.com/gregrymqt/bueiro-inteligente)
> **Ecossistema IoT & Smart City para Monitoramento Preventivo de Enchentes**
* **O Problema:** Ausência de telemetria em tempo real para ações preventivas contra alagamentos em redes de drenagem urbana.
* **A Solução:** Arquitetura distribuída integrando sensores **ESP32**, backend em **.NET 8**, dashboard web e aplicativo Android em Kotlin. Implementei camada de cache no **Redis** com estratégia *Cache Aside* e políticas de *Exponential Retry*.
* `.NET 8` · `Kotlin` · `React` · `Redis` · `PostgreSQL` · `ESP32` · `Docker`

---

### 📈 Estatísticas do GitHub

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=gregrymqt&show_icons=true&theme=dark&include_all_commits=true&count_private=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gregrymqt&layout=compact&theme=dark&hide=html,css" />
</div>

<div align="center">
  <h1>Lucas Vicente</h1>
  <p><b>Desenvolvedor Back-End | C# (.NET 8) · Python (FastAPI) · Go (Golang)</b></p>
  <p><i>Arquitetura de Software · Sistemas Distribuídos · Resiliência & Processamento Assíncrono</i></p>
  <p>
    <a href="https://www.linkedin.com/in/lucas-vicente-dev/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:lucasvicentedesouza021@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  </p>
</div>

---

### 👤 Sobre Mim
Estudante de Desenvolvimento de Software Multiplataforma na **FATEC Praia Grande** (5º Semestre | Formatura: Julho/2027). Atuo focado na engenharia de sistemas Back-End escaláveis, microsserviços orientados a eventos e processamento concorrente de alta performance.

Minha prática de engenharia prioriza **Clean Architecture**, **Vertical Slice Architecture**, **SOLID**, resiliência a falhas com **Polly (Circuit Breaker / Retry)** e cobertura com **Testes Unitários (padrão AAA com xUnit e Moq)**.

---

### 🛠️ Toolbox & Stack Técnica

| Categoria | Tecnologias |
|---|---|
| **Back-End** | `C# (.NET 8 / ASP.NET Core)` · `Python (FastAPI)` · `Go (Golang - Concorrência)` |
| **Mensageria & Telemetria** | `RabbitMQ` · `Redis (Pub/Sub & Cache-Aside)` · `SignalR` · `Server-Sent Events (SSE)` |
| **Integração com LLMs** | `OpenAI API` · `Gemini API` · `DeepSeek` · `Groq` |
| **Bancos de Dados** | `SQL Server` · `PostgreSQL` · `MongoDB` · `Redis` |
| **DevOps & Infraestrutura** | `Docker` · `Kubernetes (Kind)` · `GitHub Actions` · `Linux` |
| **Qualidade & Resiliência** | `xUnit / NUnit` · `Moq` · `Polly (Retry & Circuit Breaker)` |
| **Front-End (Apoio)** | `React (TypeScript)` · `Tailwind CSS` · `Vite` |

---

### 🚀 Projetos em Destaque

#### 🤖 [E-commerce Bot](https://github.com/gregrymqt/ecomerce-bot)
> **Pipeline Assíncrono de Ingestão, Enriquecimento com LLMs e Exportação Multi-Tenant**
* **O Problema:** Alta latência e instabilidade ao processar raspagem, enriquecimento de atributos via IA e exportação em larga escala de catálogos de e-commerce.
* **A Solução:** Pipeline distribuído com pool de workers assíncronos via **RabbitMQ** (`ScraperWorker`, `ProcessorWorker` e `ExporterWorker`), fallback dinâmico entre provedores de IA, criptografia **AES-256 GCM** por tenant e geração de payloads CSV em streaming de memória (`io.StringIO`), reduzindo I/O de disco para integração com Shopify e Nuvemshop.
* **Tech Stack:** `Python (FastAPI)` · `RabbitMQ` · `Redis` · `PostgreSQL` · `Docker` · `React 18`

#### 🛒 [Greg Company Ecosystem](https://github.com/gregrymqt)
> **Plataforma E-commerce com Checkout Transparente e Resiliência Transacional**
* **O Problema:** Risco de inconsistência de estado em falhas transitórias de APIs de pagamento externas e necessidade de feedback em tempo real para o cliente.
* **A Solução:** Backend em **.NET 8** com Clean Architecture e políticas de resiliência com **Polly** (Wait & Retry com backoff exponencial e Circuit Breaker). Microsserviço assíncrono em **Go** integrado via **RabbitMQ**, persistência com transações atômicas e notificações reativas ao usuário via **SignalR**.
* **Tech Stack:** `.NET 8 (C#)` · `Go` · `RabbitMQ` · `Polly` · `MongoDB` · `Redis` · `React`

#### 🌊 [Bueiro Inteligente (SIMB)](https://github.com/gregrymqt/bueiro-inteligente)
> **Ecossistema IoT & Smart City para Monitoramento Preventivo de Enchentes**
* **O Problema:** Monitoramento manual ineficiente de redes pluviais urbanas sob risco crítico de alagamentos.
* **A Solução:** Ingestão contínua de séries temporais de sensores **ESP32**, backend em **.NET 8** com arquitetura em camadas, telemetria em tempo real via **SignalR** e camada de cache no **Redis** implementando **Cache-Aside** com política de retry e degradação suave (fallback para PostgreSQL).
* **Tech Stack:** `C# (.NET 8)` · `ESP32` · `Kotlin (Android)` · `React` · `Redis` · `PostgreSQL` · `Docker`

---

### 📈 Estatísticas do GitHub

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=gregrymqt&show_icons=true&theme=dark&include_all_commits=true&count_private=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gregrymqt&layout=compact&theme=dark&hide=html,css" />
</div>

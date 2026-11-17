### Hi there 👋
### This is Jorge Barbosa!

[![Portfolio](https://img.shields.io/badge/-Portfolio-ff4d00?style=flat&logo=githubpages&logoColor=white)](https://jo-barbosa.github.io/)
[![Github](https://img.shields.io/badge/-Github-000?style=flat&logo=Github&logoColor=white)](https://github.com/jo-barbosa)
[![Linkedin](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/jo-barbosa/)
[![Outlook](https://img.shields.io/badge/-Outlook-0078D4?style=flat&logo=microsoft-outlook&logoColor=white)](mailto:barbosa.jorge@outlook.pt)

Welcome to my GitHub page! I'm Jorge, a final-year Computer Engineering student at [ISEP](https://www.isep.ipp.pt/). I build web applications with **Java and Spring Boot** on the backend and **Angular with TypeScript** on the frontend, and I'm looking for a role in **backend** or **full-stack** development.

Before moving into software, I spent more than 8 years at IKEA Industry, where I used what I was learning in my degree to build internal tools in Python.

#### 🌱 Things I am currently working on:
- 🎓 Finishing my Computer Engineering degree at ISEP
- 🍕 Building **LaPrizza**, a full-stack ordering platform with **Spring Boot 4**, **Angular**, **Three.js** and **PostgreSQL**, tested end to end with **Playwright** and deployed with **Docker Compose** and **nginx**
- 📚 Building **citebook-ai**, a RAG service with **Spring AI** and **pgvector** that answers questions with checked citations
- 🏛️ Applying **Hexagonal Architecture**, **DDD** and **TDD** in my projects

---

## 🛠️ Technologies & Tools

### 💻 Languages & Frameworks

<p>
  <img height="70" src="https://www.vectorlogo.zone/logos/java/java-ar21.svg" alt="Java" />
  <img height="70" src="https://www.vectorlogo.zone/logos/springio/springio-ar21.svg" alt="Spring Boot" />
  <img height="70" src="https://www.vectorlogo.zone/logos/typescriptlang/typescriptlang-ar21.svg" alt="TypeScript" />
  <img height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angular/angular-original.svg" alt="Angular" />
  <img height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/threejs/threejs-original.svg" alt="Three.js" />
  <img height="70" src="https://www.vectorlogo.zone/logos/python/python-ar21.svg" alt="Python" />
  <img height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C" />
</p>

### 🗄️ Databases, Testing & Tools

<p>
  <img height="70" src="https://www.vectorlogo.zone/logos/postgresql/postgresql-ar21.svg" alt="PostgreSQL" />
  <img height="70" src="https://www.vectorlogo.zone/logos/oracle/oracle-ar21.svg" alt="Oracle" />
  <img height="70" src="https://www.vectorlogo.zone/logos/sqlite/sqlite-ar21.svg" alt="SQLite" />
  <img height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/playwright/playwright-original.svg" alt="Playwright" />
  <img height="70" src="https://www.vectorlogo.zone/logos/docker/docker-ar21.svg" alt="Docker" />
  <img height="70" src="https://www.vectorlogo.zone/logos/nginx/nginx-ar21.svg" alt="nginx" />
  <img height="70" src="https://www.vectorlogo.zone/logos/amazon_aws/amazon_aws-ar21.svg" alt="AWS" />
  <img height="70" src="https://www.vectorlogo.zone/logos/git-scm/git-scm-ar21.svg" alt="Git" />
  <img height="70" src="https://www.vectorlogo.zone/logos/github/github-ar21.svg" alt="GitHub" />
</p>

---

## 🚀 Featured Projects

#### [📚 citebook-ai - RAG Service with Checked Citations](https://github.com/jo-barbosa/citebook-ai)
*Personal project that answers questions about a course's PDFs with citations (Oct. 2026 – Present).*

- 🧠 **Key Concepts:** RAG with citations (file and page) checked against the retrieved excerpts, embeddings generated locally in Ollama.
- ⚙️ **Architecture:** Hexagonal Architecture with two inbound adapters: a REST API used by an Angular UI, and an MCP server with read-only tools for external assistants.
- 🎯 **Evaluation:** 25-question retrieval test on GitHub Actions (hit rate@5 of 0.88), 9 prompt-injection tests, rejected citations tracked in Prometheus and Grafana.
- 🛠️ **Stack & Practices:** Java 25, Spring Boot 4, Spring AI, PostgreSQL/pgvector, Ollama, MCP, Angular, Docker.

#### 🍕 LaPrizza - Full-Stack Pizza Ordering & 3D Visualization Platform
*Team project: ordering platform with a real-time 3D pizza configurator (Sep. 2026 – Present). [Team landing page](https://www.laprizza.store/).*

- 🧠 **Key Concepts:** Hexagonal Architecture, DDD, stateless JWT with role-based access control.
- ⚙️ **Architecture:** Spring Boot 4 REST API documented with OpenAPI, with Flyway migrations on PostgreSQL.
- 🎨 **Frontend:** Angular 22 (TypeScript) SPA with Angular Material and a 3D configurator (Three.js) that syncs ingredients and allergen alerts.
- 🧪 **Testing:** end-to-end tests with Playwright through the UI against the real API and PostgreSQL, in CI and before each deployment, plus JUnit and Vitest suites.
- 🚢 **Deployment:** Docker Compose and nginx on a Debian VM, where each version is validated in a throwaway stack before release, with a rollback script.
- 🛠️ **Stack & Practices:** Java 25, Spring Boot 4, PostgreSQL, Docker, nginx, CI/CD (GitHub Actions), JUnit, Vitest, Playwright.

#### [✈️ AISafe - Flight Management System](https://github.com/jo-barbosa/AIsafe-app)
*Flight management backend with domain validation and a simulation engine (Feb. 2026 – Jun. 2026).*

- 🎯 **Achievements:** Graded **18/20**.
- 🧠 **Key Concepts:** Domain-Driven Design (DDD), Domain Specific Language (DSL) for flight plan validation with ANTLR.
- ⚙️ **Architecture:** TCP network servers deployed on AWS EC2, concurrent C simulation engine.
- 🛠️ **Stack & Practices:** Java 21, JPA/Hibernate, PostgreSQL, C, AWS, CI/CD (GitHub Actions) with over 90% code coverage.

#### [🚂 Logistic-on-Rails](https://github.com/jo-barbosa/Logistic-on-Rails)
*End-to-end railway logistics management solution (Integrative Project, Sep. 2025 – Jan. 2026).*

- 🏆 **Achievements:** Graded **18/20** and awarded an **Honorable Mention** (LAPR3).
- 🧠 **Key Concepts:** Route and network optimization using KD-Trees (2D) and graph algorithms (Dijkstra, Max Flow).
- ⚙️ **Architecture:** TDD-driven tiered backend integrated with database and embedded components.
- 🛠️ **Stack & Practices:** Java 17, Oracle SQL/PLSQL, C/Assembly (RISC‑V), JavaFX, TDD.

---

*“Always learning, always evolving.”*

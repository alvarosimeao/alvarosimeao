<div align="center">

<img src="assets/banner.svg" alt="Álvaro Simeão — backend, automation and data" width="100%" />

[About](#about) · [Experience](#experience) · [Projects](#featured-projects) · [Tech stack](#tech-stack) · [Contact](#contact)

</div>

## About

I am an **Analysis and Systems Development student at Universidade Ceuma**, building my path in backend development with **Java, Spring Boot, Python, databases, and automation**. I also have hands-on experience in front-end development.

I like turning business requirements into clear, testable software. The projects below are learning projects: their READMEs explain what I built, how to run or verify it, and what is still missing.

<details>
<summary>🇧🇷 Ler apresentação em português</summary>

Sou estudante de **Análise e Desenvolvimento de Sistemas na Universidade Ceuma** e estou construindo minha trajetória em desenvolvimento backend com **Java, Spring Boot, Python, bancos de dados e automação**. Também tenho experiência prática em desenvolvimento front-end.

Gosto de transformar regras de negócio em software claro e verificável. Os projetos abaixo são trabalhos de estudo: seus READMEs explicam o que construí, como executar ou verificar e o que ainda falta.

**Experiência:** trabalhei como Jovem Aprendiz em desenvolvimento na **Oxygeni, da Universidade Ceuma**. Nesse período, aprendi sobre regras de negócio, fluxo de deploy e comunicação clara com a equipe.

**Projetos:** [API de alunos](https://github.com/alvarosimeao/Entregaveis_Api_Arquitetura) · [Simulador de pagamentos](https://github.com/alvarosimeao/sistema-pagamentos-java) · [Pedidos e estoque](https://github.com/alvarosimeao/Entregaveis_Backend).

**Tecnologias:** Java, Spring Boot, Python, n8n, SQL, PostgreSQL, Docker, Git, GitHub e análise de dados com planilhas. Também uso TypeScript, React e Next.js em front-end.

</details>

## Experience

**Software Development Apprentice · Oxygeni, Universidade Ceuma**

I worked in a front-end development role and learned how to understand business rules, follow deployment workflows, and communicate implementation details clearly with the team. This experience shaped how I approach software beyond the code: understanding the need, explaining decisions, and checking the result.

## Featured projects

| Project | What it shows | How to verify |
| --- | --- | --- |
| **[Student API](https://github.com/alvarosimeao/Entregaveis_Api_Arquitetura)** | Java, Spring Boot, PostgreSQL, REST endpoints, DTOs, and separation of responsibilities. | [Run and call the API](https://github.com/alvarosimeao/Entregaveis_Api_Arquitetura#como-executar-a-api) |
| **[Java payment simulator](https://github.com/alvarosimeao/sistema-pagamentos-java)** | Object-oriented design, `BigDecimal`, payment validation, and executable tests. No real transactions. | [Run the tests](https://github.com/alvarosimeao/sistema-pagamentos-java#como-testar) |
| **[Orders and inventory data model](https://github.com/alvarosimeao/Entregaveis_Backend)** | PostgreSQL modeling, indexes, permissions, and transactions in an academic scenario. | [Run the SQL scripts](https://github.com/alvarosimeao/Entregaveis_Backend/blob/main/Modulo_Backend/Banco_de_dados/entregavel16/README.md) |

<details>
<summary>Technical decisions and current limits</summary>

- **Student API:** DTOs separate API data from the persisted entity. It still needs automated tests, input validation, and specific HTTP handling for missing students.
- **Payment simulator:** `BigDecimal` handles monetary values; executable tests cover approvals, refusals, and repeated processing. It has no persistence or banking integration.
- **Orders and inventory:** the order item stores the agreed price to preserve history; a transaction prevents partial orders when stock is insufficient. The sample data is too small to support performance claims.

</details>

## Tech stack

| Area | Tools and practices |
| --- | --- |
| **Back-end** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" alt="Java" width="28" height="28" /> Java &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/spring/spring-original.svg" alt="Spring Boot" width="28" height="28" /> Spring Boot &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="Python" width="28" height="28" /> Python |
| **Front-end** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" alt="React" width="28" height="28" /> React &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" alt="TypeScript" width="28" height="28" /> TypeScript &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nextjs/nextjs-original.svg" alt="Next.js" width="28" height="28" /> Next.js |
| **Data / analysis** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="28" height="28" /> PostgreSQL &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azuresqldatabase/azuresqldatabase-original.svg" alt="SQL" width="28" height="28" /> SQL &nbsp; 📊 Spreadsheets / data analysis |
| **DevOps / tools** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" alt="Docker" width="28" height="28" /> Docker &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" alt="Git" width="28" height="28" /> Git &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original.svg" alt="GitHub" width="28" height="28" /> GitHub &nbsp; 🚀 Deployment workflows |
| **Automation** | <img src="https://cdn.simpleicons.org/n8n/EA4B71" alt="n8n" width="28" height="28" /> n8n |

## Contact

<div align="center">

<a href="https://www.linkedin.com/in/alvaro-sime%C3%A3o-castelo-branco-0b1349378/"><img src="assets/linkedin.svg" alt="Open Álvaro Simeão's LinkedIn" height="44" /></a>
<a href="mailto:alvarosimeao21@gmail.com"><img src="assets/email.svg" alt="Email Álvaro Simeão" height="44" /></a>

</div>

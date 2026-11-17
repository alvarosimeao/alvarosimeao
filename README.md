<div align="center">

<img src="assets/hero-stack-v2.svg" alt="Álvaro Simeão — backend, automação e dados; logotipos de Java, Spring Boot, Python, n8n, Docker e PostgreSQL" width="100%" />

[About / Sobre](#about) · [Experience / Experiência](#experience) · [Certifications / Certificações](#certifications)
<br />
[Projects / Projetos](#featured-projects) · [Stack / Tecnologias](#tech-stack) · [Contact / Contato](#contact)

</div>

## About

### Backend development · Automation · Data analysis

I study **Analysis and Systems Development at Universidade Ceuma**. I build with **Java, Spring Boot, Python, databases, and automation**, drawing on hands-on front-end experience.

I turn business requirements into clear, testable software. The projects below are learning projects with instructions, evidence, and documented limitations.

<details>
<summary>pt-BR</summary>

### Desenvolvimento backend · Automação · Análise de dados

Estudo **Análise e Desenvolvimento de Sistemas na Universidade Ceuma**. Desenvolvo com **Java, Spring Boot, Python, bancos de dados e automação**, apoiado pela experiência prática em front-end.

Transformo requisitos de negócio em software claro e verificável. Os projetos abaixo são trabalhos de estudo com instruções, evidências e limitações documentadas.

</details>

## Experience

### Software Development Apprentice · Oxygeni, Universidade Ceuma

I worked in a front-end development role and learned to understand business rules, follow deployment workflows, and communicate implementation details clearly with the team.

This experience shaped how I approach software: understand the need, explain decisions, and check the result.

<details>
<summary>pt-BR</summary>

### Jovem Aprendiz em desenvolvimento · Oxygeni, Universidade Ceuma

Trabalhei com desenvolvimento front-end e aprendi a entender regras de negócio, acompanhar fluxos de deploy e comunicar detalhes da implementação com clareza para a equipe.

Essa experiência moldou minha forma de trabalhar: compreender a necessidade, explicar decisões e conferir o resultado.

</details>

## Certifications

My [LinkedIn certifications](https://www.linkedin.com/in/alvaro-sime%C3%A3o-castelo-branco-0b1349378/details/certifications/) document coursework in:

| Area | Certified topics |
| --- | --- |
| **Software engineering** | Software architecture (University of Alberta) and introduction to software engineering (IBM). |
| **Java and Spring Boot** | Java backend development, Java fundamentals, Spring Boot applications, and MVC architecture. |
| **Data and AI** | SQL and relational databases; data analytics; supervised learning with regression and classification; machine learning, computer vision, and generative AI for data analysis. |
| **Automation** | Intelligent agents with DeepSeek and n8n. |

<details>
<summary>pt-BR</summary>

Minhas [certificações no LinkedIn](https://www.linkedin.com/in/alvaro-sime%C3%A3o-castelo-branco-0b1349378/details/certifications/) registram estudos em:

| Área | Temas certificados |
| --- | --- |
| **Engenharia de software** | Arquitetura de software (University of Alberta) e introdução à engenharia de software (IBM). |
| **Java e Spring Boot** | Desenvolvimento backend em Java, fundamentos de Java, aplicações Spring Boot e arquitetura MVC. |
| **Dados e IA** | SQL e bancos relacionais; análise de dados; aprendizado supervisionado com regressão e classificação; machine learning, visão computacional e IA generativa para análise de dados. |
| **Automação** | Agentes inteligentes com DeepSeek e n8n. |

</details>

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

<details>
<summary>pt-BR</summary>

| Projeto | O que mostra | Como verificar |
| --- | --- | --- |
| **[API de alunos](https://github.com/alvarosimeao/Entregaveis_Api_Arquitetura)** | Java, Spring Boot, PostgreSQL, endpoints REST, DTOs e separação de responsabilidades. | [Executar e chamar a API](https://github.com/alvarosimeao/Entregaveis_Api_Arquitetura#como-executar-a-api) |
| **[Simulador de pagamentos em Java](https://github.com/alvarosimeao/sistema-pagamentos-java)** | Orientação a objetos, `BigDecimal`, validações e testes executáveis. Não processa transações reais. | [Executar os testes](https://github.com/alvarosimeao/sistema-pagamentos-java#como-testar) |
| **[Modelo de pedidos e estoque](https://github.com/alvarosimeao/Entregaveis_Backend)** | Modelagem PostgreSQL, índices, permissões e transações em cenário acadêmico. | [Executar os scripts SQL](https://github.com/alvarosimeao/Entregaveis_Backend/blob/main/Modulo_Backend/Banco_de_dados/entregavel16/README.md) |

**Decisões técnicas e limites atuais**

- **API de alunos:** DTOs separam os dados da API da entidade persistida. Ainda faltam testes automatizados, validação de entrada e resposta HTTP específica para aluno inexistente.
- **Simulador de pagamentos:** `BigDecimal` representa valores monetários; testes executáveis cobrem aprovações, recusas e processamento repetido. Não há persistência ou integração bancária.
- **Pedidos e estoque:** o item guarda o preço contratado para preservar o histórico; uma transação impede pedidos parciais quando falta estoque. Os dados de exemplo são pequenos demais para sustentar alegações de desempenho.

</details>

## Tech stack

| Area | Tools and practices |
| --- | --- |
| **Back-end** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" alt="Java" width="28" height="28" /> Java &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/spring/spring-original.svg" alt="Spring Boot" width="28" height="28" /> Spring Boot &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="Python" width="28" height="28" /> Python |
| **Front-end** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" alt="React" width="28" height="28" /> React &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" alt="TypeScript" width="28" height="28" /> TypeScript &nbsp; <img src="https://cdn.simpleicons.org/nextdotjs/8B949E" alt="Next.js" width="28" height="28" /> Next.js &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind CSS" width="28" height="28" /> Tailwind CSS |
| **Data / analysis** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="28" height="28" /> PostgreSQL &nbsp; <img src="assets/sql.svg" alt="SQL" width="28" height="28" /> SQL <br /> <img src="https://raw.githubusercontent.com/microsoft/PowerBI-Icons/main/SVG/Power-BI.svg" alt="Power BI" width="28" height="28" /> <img src="assets/excel.svg" alt="Microsoft Excel" width="28" height="28" /> Spreadsheets / data analysis |
| **DevOps / tools** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" alt="Docker" width="28" height="28" /> Docker &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" alt="Git" width="28" height="28" /> Git &nbsp; <img src="https://cdn.simpleicons.org/github/8B949E" alt="GitHub" width="28" height="28" /> GitHub <br /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postman/postman-original.svg" alt="Postman" width="28" height="28" /> Postman &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" alt="VS Code" width="28" height="28" /> VS Code &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/intellij/intellij-original.svg" alt="IntelliJ IDEA" width="28" height="28" /> IntelliJ IDEA <br /> <img src="https://cdn.simpleicons.org/vercel/8B949E" alt="Vercel" width="28" height="28" /> Deployment workflows |
| **Automation** | <img src="https://cdn.simpleicons.org/n8n/EA4B71" alt="n8n" width="28" height="28" /> n8n |

<details>
<summary>pt-BR</summary>

| Área | Ferramentas e práticas |
| --- | --- |
| **Back-end** | Java · Spring Boot · Python |
| **Front-end** | React · TypeScript · Next.js · Tailwind CSS |
| **Dados / análise** | PostgreSQL · SQL · Power BI e Excel para planilhas e análise de dados |
| **DevOps / ferramentas** | Docker · Git · GitHub · Postman · VS Code · IntelliJ IDEA · fluxos de deploy com Vercel |
| **Automação** | n8n |

</details>

## Contact

Connect with me on LinkedIn or send me an email.

<div align="center">

<a href="https://www.linkedin.com/in/alvaro-sime%C3%A3o-castelo-branco-0b1349378/"><img src="assets/linkedin.svg" alt="Open Álvaro Simeão's LinkedIn" height="44" /></a>
<a href="mailto:alvarosimeao21@gmail.com"><img src="assets/email.svg" alt="Email Álvaro Simeão" height="44" /></a>

</div>

<details>
<summary>pt-BR</summary>

**Contato:** fale comigo pelo LinkedIn ou envie um e-mail pelos botões acima.

</details>

<sub>Icons / Ícones: [Devicon](https://github.com/devicons/devicon) · [Simple Icons](https://github.com/simple-icons/simple-icons) · [Microsoft Power BI Icons](https://github.com/microsoft/PowerBI-Icons) · [Microsoft Cloud Icons](https://github.com/DamoBird365/microsoft-cloud-icons).</sub>

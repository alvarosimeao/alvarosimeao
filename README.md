<div align="center">

<img src="assets/banner.svg" alt="Álvaro Simeão — desenvolvimento front-end e estudos em backend Java" width="100%" />

[Sobre](#sobre) · [Projetos](#projetos) · [Tecnologias](#tecnologias) · [Contato](#contato)

</div>

## Sobre

Sou estudante de **Análise e Desenvolvimento de Sistemas na Universidade Ceuma** e atuo como **Jovem Aprendiz em desenvolvimento front-end**. Estou aprofundando meus estudos em Java, Spring Boot e bancos de dados para construir aplicações backend.

Aqui você encontra projetos de estudo com código, decisões técnicas, instruções de execução e limites documentados. Comece pelo projeto mais próximo da vaga que você está avaliando:

## Projetos

### 01 · API de alunos

**Java · Spring Boot · PostgreSQL** — API REST para cadastro e consulta de alunos fictícios, com DTOs e separação entre controlador, serviço e persistência.

[Explorar o projeto](https://github.com/alvarosimeao/Entregaveis_Api_Arquitetura) · [Como executar](https://github.com/alvarosimeao/Entregaveis_Api_Arquitetura#como-executar-a-api)

<details>
<summary>Ver decisões técnicas e estado atual</summary>

- **Decisão:** separar DTOs da entidade persistida e distribuir as responsabilidades entre controlador, serviço e repositório.
- **Verificação:** o README mostra como iniciar a API com dados fictícios e testar os endpoints pelo terminal.
- **Limite atual:** ainda não há testes automatizados, validação de entrada ou tratamento HTTP específico para aluno inexistente.

</details>

### 02 · Simulador de pagamentos

**Java · orientação a objetos · testes** — simula Pix, débito e crédito no console. Nenhuma transferência ou cobrança real é realizada.

[Explorar o projeto](https://github.com/alvarosimeao/sistema-pagamentos-java) · [Como testar](https://github.com/alvarosimeao/sistema-pagamentos-java#como-testar)

<details>
<summary>Ver regras implementadas e verificação</summary>

- **Decisão:** usar `BigDecimal` para valores monetários e uma classe base para regras comuns.
- **Regras:** recusa valores não positivos e pagamentos sem saldo ou limite; a mesma instância não é processada duas vezes.
- **Verificação:** nove cenários executáveis cobrem aprovações, recusas e processamento repetido usando apenas o JDK.

</details>

### 03 · Pedidos e estoque

**PostgreSQL · modelagem de dados · transações** — estudo de um fluxo de pedidos, da normalização do modelo às consultas, permissões e regras de estoque.

[Explorar o projeto](https://github.com/alvarosimeao/Entregaveis_Backend) · [Como executar os scripts](https://github.com/alvarosimeao/Entregaveis_Backend/blob/main/Modulo_Backend/Banco_de_dados/entregavel16/README.md)

<details>
<summary>Ver decisões de modelagem e verificação</summary>

- **Decisão:** guardar o preço contratado no item do pedido para preservar o histórico quando o preço do produto mudar.
- **Integridade:** o registro de pedido usa transação para evitar pedidos parciais quando falta estoque.
- **Verificação:** a entrega principal documenta a ordem dos scripts SQL e um teste negativo de permissões. Os dados são pequenos e não sustentam alegações de ganho de desempenho.

</details>

## Tecnologias

**Foco atual:** `Java` · `Spring Boot` · `SQL` · `PostgreSQL`  
**Experiência em front-end:** `TypeScript` · `React` · `Next.js`

## Contato

<div align="center">

<a href="https://www.linkedin.com/in/alvaro-sime%C3%A3o-castelo-branco-0b1349378/"><img src="assets/linkedin.svg" alt="Abrir LinkedIn de Álvaro Simeão" height="44" /></a>
<a href="mailto:alvarosimeao21@gmail.com"><img src="assets/email.svg" alt="Enviar e-mail para Álvaro Simeão" height="44" /></a>

</div>

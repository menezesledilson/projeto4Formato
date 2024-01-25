# JDBC (Java Database Connectivity)

O JDBC é uma interface de nível de programação para aplicativos Java que facilita a comunicação entre esses aplicativos e um banco de dados. Esta API (Interface de Programação de Aplicações) permite que os desenvolvedores interajam com um gerenciador JDBC para realizar operações de banco de dados. O código de aplicação utiliza o JDBC como uma camada de abstração para se comunicar com o banco de dados. Além disso, o fornecedor do banco de dados disponibiliza um driver JDBC compatível para permitir essa comunicação.

## Principais Características do JDBC:
- **Comunicação com o Banco de Dados:** Permite a execução de consultas SQL e atualizações no banco de dados.
- **Gerenciamento de Conexão:** Facilita a criação, abertura, fechamento e gerenciamento de conexões com o banco de dados.
- **Tratamento de Exceções:** Oferece suporte para o tratamento de exceções relacionadas a operações no banco de dados.

# JPA (Java Persistence API)

A JPA é um padrão Java que possibilita o mapeamento de objetos Java para registros em um banco de dados relacional. Essa abordagem é conhecida como Object-Relational Mapping (ORM), onde as entidades do banco de dados são representadas por objetos Java. A JPA facilita operações comuns de persistência, como recuperar, armazenar, atualizar e excluir dados no banco de dados relacional por meio de objetos Java.

## Principais Características da JPA:
- **Mapeamento Objeto-Relacional:** Permite o mapeamento direto de classes Java para tabelas do banco de dados e de campos para colunas, simplificando o código.
- **Consultas JPQL:** Introduz a linguagem de consulta JPQL (Java Persistence Query Language) para realizar consultas orientadas a objetos.
- **Portabilidade:** Promove a portabilidade entre diferentes provedores de JPA, permitindo a troca de implementações sem alterações significativas no código da aplicação.

Várias implementações da JPA estão disponíveis, proporcionando flexibilidade na escolha de uma implementação específica para atender aos requisitos do projeto.

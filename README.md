# REST API com Spring Boot e Java 21
​
 Este projeto é uma API RESTful desenvolvida com **Java 21** e **Spring Boot 3**, demonstrando boas práticas de desenvolvimento, arquitetura em camadas e integração com diversas ferramentas modernas.
​
 ##  Tecnologias Utilizadas
​
 *   **Java 21**
 *   **Spring Boot 3.4.0**
     *   Spring Web (REST)
     *   Spring Data JPA
     *   Spring HATEOAS
 *   **Banco de Dados:** MySQL
 *   **Migração de Dados:** Flyway
 *   **Mapeamento de Objetos:** Dozer Mapper
 *   **Serialização:** Jackson (Suporte a JSON, XML e YAML)
 *   **Testes:** JUnit 5, Mockito
​
 ##  Funcionalidades
​
 *   **CRUD Completo:** Operações de Create, Read, Update e Delete (ex: Entidade *Person*).
 *   **Content Negotiation:** Suporte para requisições e respostas em **JSON**, **XML** e **YAML**.
 *   **HATEOAS:** (Hypermedia as the Engine of Application State) para navegabilidade da API.
 *   **Versionamento de Banco de Dados:** Gerenciamento automatizado de schemas com Flyway.
 *   **Testes Unitários e de Integração:** Cobertura de testes para Services e Controllers.
​
​
​​
 ##  Estrutura do Projeto
​
 O projeto segue uma arquitetura padrão do Spring Boot:
​
 *   `controllers`: Camada de controle (REST Endpoints).
 *   `services`: Regras de negócio.
 *   `repository`: Acesso a dados (Interfaces JPA).
 *   `model`: Entidades JPA.
 *   `data/vo`: Value Objects (DTOs) para transferência de dados.
 *   `mapper`: Configurações de mapeamento (Dozer).
 *   `config`: Configurações gerais (Web, Swagger, etc).
 *   `exception`: Tratamento global de exceções.

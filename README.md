# lab-padroes-projeto-spring
Desafio de Projeto sobre Padrões de Projeto com Spring Boot na DIO
# Lab: Padrões de Projeto com Spring Boot

Projeto desenvolvido para o Desafio de Projeto da DIO ("Design Patterns com Java: Dos Clássicos (GoF) ao Spring Framework").

## Padrões Utilizados no Projeto

- **Singleton:** Injeção de dependências gerenciada pelo Spring Framework (beans com `@Service`, `@RestController`, `@Autowired`).
- **Strategy:** Interface `ClienteService` permitindo abstrair e alternar implementações do serviço de negócios.
- **Facade:** Abstração da integração complexa com o serviço externo do ViaCEP por meio de uma interface amigável utilizando `Spring Cloud OpenFeign`.

## Tecnologias
- Java 17
- Spring Boot 3
- Spring Data JPA (Banco de dados H2 em memória)
- OpenFeign (Integração com API REST ViaCEP)

## Como Executar
1. Clone este repositório.
2. Execute a classe `Application.java` na sua IDE ou pelo terminal com `./mvnw spring-boot:run`.
3. A aplicação estará rodando em `http://localhost:8080`.

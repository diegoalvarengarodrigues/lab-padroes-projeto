# Explorando Padrões de Projetos na Prática com Java

## Digital Innovation One: Labs

Projeto desenvolvido com instruções de [Venilton FalvoJr](https://github.com/falvojr) no Labs da [Digital Innovation One](https://www.dio.me/). Como base foi utilizado o repositório [digitalinnovationone/lab-padroes-projeto-spring](https://github.com/digitalinnovationone/lab-padroes-projeto-spring). Neste Lab foi exposto também padrões de projeto Singleton, Strategy e Facade em Java puro que podem ser conferidos no repositório [digitalinnovationone/lab-padroes-projeto-java](https://github.com/digitalinnovationone/lab-padroes-projeto-java)



<hr>

Para iniciar este projeto, foi utilizado o [spring initializr](https://start.spring.io/) utilizando as opções:
* Project: Maven Project;
* Language: Java 17;
* Spring Boot: 2.5.4;
* Dependencies: Spring Web, Spring Data JPA, H2 Database e OpenFeign.

Dependência adicionada manualmente no `pom.xml`: [Springdoc OpenAPI UI v1.5.10](https://mvnrepository.com/artifact/org.springdoc/springdoc-openapi-ui/1.5.12).

<hr>

Padrões e conceitos apresentados no Lab:
* *Singleton*: Padrão Criacional que permite a criação de uma única instância de uma classe e fornecer um modo para recuperá-la;
* *Strategy*: Padrão Comportamental com objetivo de simplificar a variação de algoritmos para a resolução de um mesmo problema;
* *Facade*: Padrão Estrutural que visa prover uma interface que reduza a complexidade nas integrações com subsistemas.

A relação entre Padrões de Projetos com Java e o spring framework pode-se ser percebida em:
* Annotations *@Bean* e *@Autowired* como padrão criacional **Singleton**;
* Annotations *@Service* e *@Repository* como padrão comportamental **Strategy**;
* Annotation *@RestController* como padrão estrutural **Facade**.

<hr>

Swagger: ``http://127.0.0.1:8080/swagger-ui.html``
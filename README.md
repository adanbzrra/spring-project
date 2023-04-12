<h1 align ="center">Projeto de exemplo de aplicação web com Spring</h1>
<h4 align="center">Criando um projeto com spring em dois módulos</h4>

## Projeto

-Project: Maven Project
-Language: Java
-Spring Boot: 3.1.0(M2)
-Group: com.minhaempresa.meuprojeto
-Artifact: spring-project
-Packaging: Jar
-Java: 11

## Dependências

- Spring Web 
- Spring Data JPA
- Lombok
- Spring boot Devtools
- MySQL Driver
- Validation

## Modulos

O módumo api é responsavel por expor a API REST do projeto. 
Ele possui as seguintes camadas:

-  api.rest.dto: pacote que contém as classes de tranferência de dados (DTOs)
-  api.rest.resources: pacote que contém as classes que implementam os endpoints da API REST

O módulo core é responsavel pela lógica de negócio e persistência de dados do projeto.
Ele possui as seguintes camadas:

- core.services: pacote que contém as classes que implementam a lógica de negócio do sistema.
- core.data.models: pacote que contém as classes que lidam com a persistência de dados do sistema, utilizando o Spring Data JPA

## Pilha tecnológica

- Spring Boot
- Mysql


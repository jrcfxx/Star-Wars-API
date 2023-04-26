# API REST COM STAR WARS

# Apresentação

Olá, viajante!

Se você chegou até aqui, meus parabéns. Darth Vader quebrou a quarta dimensão à procura de uma API que retornasse os filmes com participação de Luke Skywalker. Se você chegou primeiro, são boas notícias. O cavaleiro Jedi João Reis me pediu sigilo absoluto com este projeto para proteger a humanidade. A seguir seguem as instruções para a execução.

***Que a força esteja com você…***

## Instalação

![spring-logo.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/846dec2f-23a6-4778-b79c-155136caefc5/spring-logo.png)

Primeiramente, criei um projeto utilizando Spring Initializr e o abri com o Spring Tool Suite.

Depois, criei as variáveis com o mesmo nome da API que vamos utilizar.

![Podemos observar as variáveis que quero que retorne e os devidos Setters e Getters.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7513fb4a-837e-4a89-950d-f03554da2cca/Untitled.png)

Podemos observar as variáveis que quero que retorne e os devidos Setters e Getters.

Em seguida, criei uma classe - **SWAPIResponse**-  que representa a SWAPI. Essa classe terá um campo "results" que contém uma lista de objetos <**SWAPIResponse**>. 

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7f1827c6-b6b3-4178-8e74-e0fd0310a123/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c0947a45-951c-4e12-bbcf-3a729276404f/Untitled.png)

Depois, utilizando o **`RestTemplate` ,** criei um cliente HTTP para a SWAPI. Nessa classe criei uma instância do **`RestTemplate`** e um método que faz uma solicitação GET para a SWAPI que retorna somente os filmes que têm a participação de Luke.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f95d5d67-2595-4e48-a032-070313d91fa5/Untitled.png)

A API está pronta!

- Retornando uma listagem de Filmes The Star Wars utilizando a API do [https://swapi.dev/](https://swapi.dev/) que tenha como personagem envolvido **Luke Skywalker.**
- Inserindo mais um item na listagem de filmes.

## Executando o projeto

1. Para a execução do projeto, abriremos o [Postman API Platform](https://www.postman.com/), uma plataforma de API para teste.
2. Ao executar o projeto no Spring Tool Suite, já é possível executá-lo no Postman, basta colocar o seguinte link: ***[http://localhost:8080/movies](http://localhost:8080/filmes)*** como na imagem abaixo:

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3ec4f8db-4ed3-4ebf-b914-e5e5b6ee950b/Untitled.png)

## Construído com

- Spring Tool Suite
- Java Spring Boot
- Postman
- Json

## Responsável pelo projeto:

Júlia Rocha - Desenvolvedora backend

“**Faça ou não faça.**
 **Não existe tentar.**”

           *mestre Yoda*

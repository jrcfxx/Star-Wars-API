# Star-Wars-API

# API REST COM STAR WARS

# Apresentação

Olá, viajante!

Se você chegou até aqui, meus parabéns. Darth Vader quebrou a quarta dimensão à procura de uma API que retornasse os filmes com participação de Luke Skywalker. Se você chegou primeiro, são boas notícias. O cavaleiro Jedi João Reis me pediu sigilo absoluto com este projeto para proteger a humanidade. A seguir seguem as instruções para a execução.

***Que a força esteja com você…***

## Instalação

Primeiramente, criei um projeto utilizando Spring Initializr e o abri com o Spring Tool Suite.

Depois, criei as variáveis com o mesmo nome da API que vamos utilizar.

![Podemos observar as variáveis que quero que retorne e os devidos Setters e Getters.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/216260a9-1a28-40d2-a83d-275e861a5125/Untitled.png)

Podemos observar as variáveis que quero que retorne e os devidos Setters e Getters.

Em seguida, criei uma classe - **StarWarsApiResponse** -  que representa a SWAPI. Essa classe terá um campo "results" que contém uma lista de objetos <**StarWarsMovie**>. 

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c0947a45-951c-4e12-bbcf-3a729276404f/Untitled.png)

Depois, utilizando o **`RestTemplate` ,** criei um HTTP para a SWAPI. Nessa classe criei uma instância do **`RestTemplate`** e um método que faz uma solicitação GET para a SWAPI. Adicionei um parâmetro de pesquisa "Luke Skywalker" ao URL da API, dessa forma retorna somente os filmes que têm a participação de Luke.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6b3cc107-73ac-4bfc-8307-2eb129ecbd22/Untitled.png)

Depois de adicionar o RestTemplate, criei um controller que retorna somente essa lista de filmes.

![Aqui está o método que faz uma solicitação para o cliente da SWAPI e retorna a lista de filmes. Em baixo é o ponto que adicionei um novo filme à lista com movies.add](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c0734979-a63b-48ed-adc7-8011c22893fb/Untitled.png)

Aqui está o método que faz uma solicitação para o cliente da SWAPI e retorna a lista de filmes. Em baixo é o ponto que adicionei um novo filme à lista com movies.add

A API está pronta!

- Retornando uma listagem de Filmes The Star Wars utilizando a API do [https://swapi.dev/](https://swapi.dev/) que tenha como personagem envolvido **Luke Skywalker.**
- Inserindo mais um item na listagem de filmes.

## Executando o projeto

1. Para a execução do projeto, abriremos o [Postman API Platform](https://www.postman.com/), uma plataforma de API para teste.
2. Ao executar o projeto no Spring Tool Suite, já é possível executá-lo no Postman, basta colocar o seguinte link: ***[http://localhost:8080/movies](http://localhost:8080/movies)*** como na imagem abaixo:

![Usando o método GET](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d7e4d24b-a217-4870-b122-24936fc786f8/Untitled.png)

Usando o método GET

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

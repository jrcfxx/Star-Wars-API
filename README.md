# API REST COM STAR WARS

# Apresentação

Olá, viajante!

Se você chegou até aqui, meus parabéns. Darth Vader quebrou a quarta dimensão à procura de uma API que retornasse os filmes com participação de Luke Skywalker. Se você chegou primeiro, são boas notícias. O cavaleiro Jedi João Reis me pediu sigilo absoluto com este projeto para proteger a humanidade. A seguir seguem as instruções para a execução.

***Que a força esteja com você…***

## Instalação

Primeiramente, criei um projeto utilizando Spring Initializr e o abri com o Spring Tool Suite.

Criei a classe filme e as variáveis com o mesmo nome da API que vamos utilizar.

![Podemos observar as variáveis que quero que retorne e os devidos Setters e Getters.] https://www.notion.so/API-REST-COM-STAR-WARS-19e4982960b34275b20a55453edb6dfa?pvs=4#28b09db8934c448b9806ed6236ae0cb6

Podemos observar as variáveis que quero que retorne e os devidos Setters e Getters.

Em seguida, criei uma classe - **SWAPIResponse**-  que representa a SWAPI. Essa classe terá um campo "results" que contém uma lista de objetos <**SWAPIResponse**>. 

https://www.notion.so/API-REST-COM-STAR-WARS-19e4982960b34275b20a55453edb6dfa?pvs=4#29d70a8e74d048d599b67a89f0d3ba9a

Depois, utilizando o **`RestTemplate` ,** criei um HTTP para a SWAPI. Nessa classe criei uma instância do **`RestTemplate`** e um método que faz uma solicitação GET para a SWAPI que retorna somente os filmes que têm a participação de Luke.

![Ao receber uma requisição POST para a URL "/filmes" no Postman, será adicionado à lista de filmes na classe FilmeControllerApplication.] https://www.notion.so/API-REST-COM-STAR-WARS-19e4982960b34275b20a55453edb6dfa?pvs=4#f9568a5e14864e00b9ecb9c7eca82072

Ao receber uma requisição POST para a URL "/filmes" no Postman, será adicionado à lista de filmes na classe FilmeControllerApplication.

A API está pronta!

- Retornando uma listagem de Filmes The Star Wars utilizando a API do [https://swapi.dev/](https://swapi.dev/) que tenha como personagem envolvido **Luke Skywalker.**
- Inserindo mais um item na listagem de filmes.

## Executando o projeto

1. Para a execução do projeto, abriremos o [Postman API Platform](https://www.postman.com/), uma plataforma de API para teste.
2. Ao executar o projeto no Spring Tool Suite, já é possível executá-lo no Postman, basta colocar o seguinte link: [http://localhost:8080/filmes](http://localhost:8080/filmes) ******como na imagem abaixo:

https://www.notion.so/API-REST-COM-STAR-WARS-19e4982960b34275b20a55453edb6dfa?pvs=4#96d4ccff6fc14b5781f719afe78c899b

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

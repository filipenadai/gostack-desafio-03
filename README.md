<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios-new.png" />

<h3 align="center">
  Desafio 03: Conceitos do React.js
</h3>

## O desafio 

O desafio pede para criar uma aplicação que irá armazenas os repositórios do desafio passado(Conceitos do Node.JS).

São 3 funcionalidades propostas: 

- [x] 1. Listar os repositórios da api

A funcionalidade deve pegar todos os reposiórios contidos na api e listá-los.

- [x] 2. Adicionar um novo repositório na api

Devará ser capaz de adicionar um novo repositório na api e listá-lo logo em seguida. 

- [x] 3. Removar um repositório da api

Irá remover o repositório específico da api. 

## Solução

1. Com o ```ùseEffect``` do React deverá fazer uma requisição do tipo ```[GET]``` para o backend e setar estes valores em um ```state```.

2. Com uma função nomeada ```handleAddRepository``` é feito uma requisição ```[POST]``` passando os valores ```title, url, techs[]```. E com o retorno dessa função devo setar em meu ```state``` de repositórios criado.

3. Utilizando uma requisição do tipo ```[DELETE]``` para o meu backend é removido o repositório escolhido, e o ```state``` de repositórios é filtrado novamente.

### Para instalar e usar esta aplicação sigas os passos abaixo.

1. Faça um ```git clone``` do projeto.

2. Instale as dependências do projeto utilizando ```npm install``` ou ```yarn add```.

3. Inicie o projeto com ```yarn dev```.

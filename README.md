# api-jogos

Api propria para cadastro de jogos

## Endpoints

### GET /Games
Esse endpoint é responsavel por retornar a listagem de todos os games cadastrados no banco de dados

### Parametros
Nenhum
#### Respostas

##### OK! 200
Caso essa resposta aconteça voce vai receber a listagem de todos os games

#### Falha na autenticacao! 401
Caso essa resposta aconteça, isso significa que aconteceu alguma falha durante o processo de autenticacao da requisicao.

## POST / AUTH

Esse endpoint é responsavel por retornar a fazer o processo de login

#### Respostas

##### OK! 200

Caso essa resposta aconteca voce receber o token JWT para conseguir essa endpoint protegidos na API.

#### Parametros

email: Email do usuario cadastrado no sistema

## Clona o projeto 

    https://github.com/vinicius-batista-dev/api-jogos.git

## Seleciona a pasta backend, instala os pacotes

    npm install

## Starta o projeto

    npx nodemon index
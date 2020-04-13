# Desafio02BootcampRocketSeat

<h3 align="center">
  Desafio 02: Conceitos do Node.js
</h3>

## Descrição

Resolução do Desafio 02 do Bootcamp da RocketSeat.

### Testando a resolução

Para utilizar a resolução do desafio, você deve baixar este repositório rodar o comando `yarn` para a instalação das dependências e para "rodar" o back-end deve utilizar o comando `yarn dev`.

Abaixo segue uma descrição das rotas:

- **`POST /repositories`**: Essa rota tem como objetivo cadastrar novos repositórios, é necessário enviar no corpo da requisição (body) os seguintes parâmetros: `title`, `url` e `techs`.

- **`GET /repositories`**: Essa rota é responsável por exibir a lista de todos os repositórios cadastrados na aplicação.

- **`PUT /repositories/:id`**: Essa é reponsável por atuailizar repositórios existentes na aplicação, é necessário enviar o `id` do repositório na url da rota e também no corpo da requisição (body) os seguintes parâmetros: `title`, `url` e `techs`.

- **`DELETE /repositories/:id`**: Essa rota é responsável por apagar (deletar)um repositório específico da aplicação, é necessário enviar o `id` do repositório desejado na url da rota;

- **`POST /repositories/:id/like`**: Essa rota é responsável por adicionar 1 like ao repositório indicado por meio do seu `id` na url da rota;

---

Feito por Herton F. Vilarim.

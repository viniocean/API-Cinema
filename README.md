# Projeto individual Módulo 5



# [ API ] Cinema
### 📑 Descrição
Desenvolvimento da <em>**API REST**</em> no **padrão MVC** que retorna informações das entidades de um cinema e efetua todas as operações **CRUD**: ``Cinemas``, ``Filmes``, ``Sessoes``, ``Clientes``.




**[ Tecnologias ]**

<samp>
  
- <em>Node.js</em> | <em>SQLite3</em> | <em>Express</em> | <em>Insomnia</em> | <em>CORS</em> | <em>npm</em> | <em>Nodemon</em>
  
</samp>

<details>
<summary>  
  <strong>Estrutura do Diretório</strong>
</summary>
<br>

```
src/
├─ controllers/
│  ├─ CinemasController.js
│  ├─ FilmesController.js
│  ├─ SessoesController.js
│  └─ ClientesController.js
├─ dao/
│  ├─ CinemasDAO.js
│  ├─ FilmesDAO.js
│  ├─ SessoesDAO.js
│  └─ ClientesDAO.js
├─ models/
│  ├─ Cinemas.js
│  ├─ Filmes.js
│  ├─ Sessoes.js
│  └─ Clientes.js
├─ database/
│  ├─ create-and-populate.js
│  ├─ config.js
│  └─ database.db
├─ routes/
│  ├─ cinemas.js
│  ├─ filmes.js
│  ├─ sessoes.js
│  └─ clientes.js
└─ main.js
```

</details>


### 🎲 Iniciando o Projeto


<samp>
  
> **Warning** 
> Pré-Requisitos: Git, Node.js e um editor de código.

</samp>

```bash
# Clone o repositório
$ git clone https://github.com/viniocean/Projeto-Individual-5

# Acesse a pasta do projeto no terminal/cmd
$ cd clínicaApi

# Instale as dependências
$ npm install

# Execute a aplicação 
$ npm start

# Acesse o servidor
$ <http://localhost:6020>
```

## Rotas CRUD

### [ 1 ] <em>Cinemas

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
| **`GET`** | **/cinemas** | Retorna todos os cinemas. |
|  **`GET`** | **/cinemas/id** | Retorna um cinema. |
|  **`POST`** | **/cinemas** | Cria um novo cinema.  |
|  **`PUT`** | **/cinemas/id** | Altera os dados do cinema.
|  **`DELETE`** | **/cinemas/id** | Remove o cinema.
  
### [ 2 ] <em>Filmes</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/filmes** | Retorna todos os filmes. |
|  **`GET`** | **/filmes/id** | Retorna um filme. |
|  **`POST`** | **/filmes** | Cria um novo filme.  |
|  **`PUT`** | **/filmes/id** | Altera os dados do filme.
|  **`DELETE`** | **/filmes/id** | Remove o filme.
  
  
### [ 2 ] <em>Sessões</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/sessoes** | Retorna todas as sessões. |
|  **`GET`** | **/sessoes/id** | Retorna uma sessão. |
|  **`POST`** | **/sessoes** | Cria uma nova sessão.  |
|  **`PUT`** | **/sessoes/id** | Altera os dados da sessão.
|  **`DELETE`** | **/sessoes/id** | Remove a sessão.


### [ 2 ] <em>Clientes</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/clientes** | Retorna todos os clientes. |
|  **`GET`** | **/clientes/id** |  Retorna um cliente. |
|  **`POST`** | **/clientes** | Cria um novo cliente.  |
|  **`PUT`** | **/clientes/id** | Altera os dados do cliente.
|  **`DELETE`** | **/cliente/id** | Remove o cliente.
  


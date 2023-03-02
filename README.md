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
$ git clone https://github.com/LaraSharmon/Projeto-API-Redmi.git

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
| **`GET`** | **/fisioterapeutas** | Retorna todos os fisioterapeutas. |
|  **`GET`** | **/fisioterapeuta/id** | Retorna um fisioterapeuta. |
|  **`POST`** | **/fisioterapeuta** | Cria um novo fisioterapeuta.  |
|  **`PUT`** | **/fisioterapeuta/id** | Altera os dados do fisioterapeuta.
|  **`DELETE`** | **/fisioterapeuta/id** | Remove o fisioterapeuta.
  
### [ 2 ] <em>Pacientes</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/pacientes** | Retorna todos os Pacientes. |
|  **`GET`** | **/paciente/id** | Retorna um Paciente. |
|  **`POST`** | **/paciente** | Cria um novo Paciente.  |
|  **`PUT`** | **/paciente/id** | Altera os dados do Paciente.
|  **`DELETE`** | **/paciente/id** | Remove o Paciente.
  
  
### [ 2 ] <em>Agendamento</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/agendamentos** | Retorna todos os agendamentos. |
|  **`GET`** | **/agendamento/id** | Retorna um agendamento. |
|  **`POST`** | **/agendamento** | Cria um novo agendamento.  |
|  **`PUT`** | **/agendamento/id** | Altera os dados do agendamento.
|  **`DELETE`** | **/agendamento/id** | Remove o agendamento.


### [ 2 ] <em>Equipamentos</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/equipamentos** | Retorna todos os equipamentos. |
|  **`GET`** | **/equipamento/id** |  Retorna um equipamento. |
|  **`POST`** | **/equipamento** | Cria um novo mequipamento.  |
|  **`PUT`** | **/equipamento/id** | Altera os dados do equipamento.
|  **`DELETE`** | **/equipamento/id** | Remove o equipamento.
  


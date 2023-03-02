# projeto-5-individual-Api


# Projeto individual MÃ³dulo 5



# [ API ] ClÃ­nica de Fisioterapia
### ðŸ“‘ DescriÃ§Ã£o
Desenvolvimento da <em>**API REST**</em> no **padrÃ£o MVC** que retorna informaÃ§Ãµes das entidades de um estÃºdio de tatuagem e efetua todas as operaÃ§Ãµes **CRUD**: ``Fisioterapeuta``, ``Pacientes``, ``Agendamento``, ``Equipamentos``.




**[ Tecnologias ]**

<samp>
  
- <em>Node.js</em> | <em>SQLite3</em> | <em>Express</em> | <em>Insomnia</em> | <em>CORS</em> | <em>npm</em> | <em>Nodemon</em>
  
</samp>

<details>
<summary>  
  <strong>Estrutura do DiretÃ³rio</strong>
</summary>
<br>

```
src/
â”œâ”€ controllers/
â”‚  â”œâ”€ FisioterapeutaController.js
â”‚  â”œâ”€ PacientesController.js
â”‚  â”œâ”€ AgendamentoController.js
â”‚  â””â”€ EquipamentosController.js
â”œâ”€ dao/
â”‚  â”œâ”€ FisioterapeutaDAO.js
â”‚  â”œâ”€ PacientesDAO.js
â”‚  â”œâ”€ AgendamentoDAO.js
â”‚  â””â”€ EquipamentosDAO.js
â”œâ”€ models/
â”‚  â”œâ”€ Fisioterapeuta.js
â”‚  â”œâ”€ Pacientes.js
â”‚  â”œâ”€ Agendamento.js
â”‚  â””â”€ Equipamentos.js
â”œâ”€ database/
â”‚  â”œâ”€ create-and-populate.js
â”‚  â”œâ”€ config.js
â”‚  â””â”€ database.db
â”œâ”€ routes/
â”‚  â”œâ”€ fisioterapeuta.js
â”‚  â”œâ”€ pacientes.js
â”‚  â”œâ”€ agendamento.js
â”‚  â””â”€ euipamentos.js
â””â”€ main.js
```

</details>


### ðŸŽ² Iniciando o Projeto


<samp>
  
> **Warning** 
> PrÃ©-Requisitos: Git, Node.js e um editor de cÃ³digo.

</samp>

```bash
# Clone o repositÃ³rio
$ git clone https://github.com/LaraSharmon/Projeto-API-Redmi.git

# Acesse a pasta do projeto no terminal/cmd
$ cd clÃ­nicaApi

# Instale as dependÃªncias
$ npm install

# Execute a aplicaÃ§Ã£o 
$ npm start

# Acesse o servidor
$ <http://localhost:6020>
```

## Rotas CRUD

### [ 1 ] <em>Fisioterapeuta</em>

| MÃ©todo | Rota | DescriÃ§Ã£o |
| ------ | ----- | ----------- |
| **`GET`** | **/fisioterapeutas** | Retorna todos os fisioterapeutas. |
|  **`GET`** | **/fisioterapeuta/id** | Retorna um fisioterapeuta. |
|  **`POST`** | **/fisioterapeuta** | Cria um novo fisioterapeuta.  |
|  **`PUT`** | **/fisioterapeuta/id** | Altera os dados do fisioterapeuta.
|  **`DELETE`** | **/fisioterapeuta/id** | Remove o fisioterapeuta.
  
### [ 2 ] <em>Pacientes</em>

| MÃ©todo | Rota | DescriÃ§Ã£o |
| ------ | ----- | ----------- |
|  **`GET`** | **/pacientes** | Retorna todos os Pacientes. |
|  **`GET`** | **/paciente/id** | Retorna um Paciente. |
|  **`POST`** | **/paciente** | Cria um novo Paciente.  |
|  **`PUT`** | **/paciente/id** | Altera os dados do Paciente.
|  **`DELETE`** | **/paciente/id** | Remove o Paciente.
  
  
### [ 2 ] <em>Agendamento</em>

| MÃ©todo | Rota | DescriÃ§Ã£o |
| ------ | ----- | ----------- |
|  **`GET`** | **/agendamentos** | Retorna todos os agendamentos. |
|  **`GET`** | **/agendamento/id** | Retorna um agendamento. |
|  **`POST`** | **/agendamento** | Cria um novo agendamento.  |
|  **`PUT`** | **/agendamento/id** | Altera os dados do agendamento.
|  **`DELETE`** | **/agendamento/id** | Remove o agendamento.


### [ 2 ] <em>Equipamentos</em>

| MÃ©todo | Rota | DescriÃ§Ã£o |
| ------ | ----- | ----------- |
|  **`GET`** | **/equipamentos** | Retorna todos os equipamentos. |
|  **`GET`** | **/equipamento/id** |  Retorna um equipamento. |
|  **`POST`** | **/equipamento** | Cria um novo mequipamento.  |
|  **`PUT`** | **/equipamento/id** | Altera os dados do equipamento.
|  **`DELETE`** | **/equipamento/id** | Remove o equipamento.
  


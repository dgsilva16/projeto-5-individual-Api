## Projeto final - individual - Api


## Prepara+ Potencialize seu desempenho no vestibular!


## ENTENDENDO A PROPOSTA:


<p><p> O site do curso preparatório é uma plataforma online que oferece uma variedade de cursos e materiais de estudo para ajudar os alunos a se prepararem para vestibulares. Esse curso é projetado para ajudar os alunos a obterem as habilidades e conhecimentos necessários para passar em exames específicos, como o vestibular, o Enem, concursos públicos ou certificações profissionais. O site pode incluir aulas em vídeo, materiais de leitura, testes práticos e fóruns de discussão para que os alunos possam interagir e trocar ideias com outros estudantes. Algumas plataformas do site também oferece aulas ao vivo com professores, tutoriais personalizados e feedback para ajudar os alunos a melhorar seus desempenhos. Em resumo, o  site de curso **Prepara+** é uma ferramenta valiosa para aqueles que desejam se preparar adequadamente para um exame ou teste importante.


# Clone o repositório
$ git clone https://github.com/dgsilva16/projeto-5-individual-Api

# Acesse a pasta do projeto no terminal/cmd
$ cd Chat

# Instale as dependências
$ npm install

# Execute a aplicação 
$ npm start

# Acesse o servidor
$ <http://localhost:9091>



#Rotas CRUD


## Rotas CRUD

### [ 1 ] <em>Autenticação</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
| **`GET`** | **/Autenticação** | Retorna todos as Autenticação. |
|  **`GET`** | **/Autenticação/id** | Retorna uma Autenticação. |
|  **`POST`** | **/Autenticação** | Cria uma nova Autenticação.  |
|  **`PUT`** | **/Autenticação/id** | Altera os dados de uma Autenticação.
|  **`DELETE`** | **/Autenticação/id** | Remove a Autenticação.
  
### [ 2 ] <em>Consulta de Cursos/em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/Consulta de Cursos** | Retorna todas as Consulta de Cursos. |
|  **`GET`** | **/Consulta de Cursos/id** | Retorna uma Consulta de Cursos. |
|  **`POST`** | **/Consulta de Cursos** | Cria uma nova Consulta de Cursos.  |
|  **`PUT`** | **/Consulta de Cursos/id** | Altera os dados da Consulta de Cursos.
|  **`DELETE`** | **/Consulta de Cursos/id** | Remove a Consulta de Cursos.
  
  
### [ 3 ] <em>Inscrição</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/Inscrição** | Retorna todas as Inscrição. |
|  **`GET`** | **/Inscrição/id** | Retorna uma Inscrição. |
|  **`POST`** | **/Inscrição** | Cria uma nova Inscrição.  |
|  **`PUT`** | **/Inscrição/id** | Altera os dados da Inscrição.
|  **`DELETE`** | **/Inscrição/id** | Remove a Inscrição.


### [ 4 ] <em>Aulas</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/Aulas** | Retorna todas as Aulas. |
|  **`GET`** | **/Aulas/id** |  Retorna as Aulas. |
|  **`POST`** | **/Aulas** | Cria uma nova Aulas.  |
|  **`PUT`** | **/Aulas/id** | Altera as Aulas.
|  **`DELETE`** | **/Aulas/id** | Remove as Aulas.




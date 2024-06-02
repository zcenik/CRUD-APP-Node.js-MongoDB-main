
<br>** ---- Integrantes do Projeto ---- **<br>
Gustavo Grassini Calabrez<br>
Bruno da Silva<br>
Pedro H. Papa<br>
Cauã Barchi<br>
Leonardo Culler<br>

**Projeto**
<br>Este projeto consiste em uma aplicação CRUD (Create, Read, Update, Delete) de blogs, utilizando Node.js e MongoDB.<br>

**Configuração do Ambiente**
<br>Certifique-se de ter o Node.js e o MongoDB instalados em sua máquina. Além disso, você precisará clonar este repositório e instalar as dependências do projeto. Execute os seguintes comandos no terminal:<br>

<br>git clone <https://github.com/zcenik/CRUD-APP-Node.js-MongoDB-main/edit/main/README.md>
<br>cd crud-app-nodejs-mongodb<br>
<br>npm install<br>

**Executando a Aplicação**
<br>Para iniciar o servidor da aplicação, utilize o seguinte comando:<br>

<br>npm start<br>
<br>Isso iniciará o servidor na porta padrão 3001. Se desejar especificar uma porta diferente, você pode definir a variável de ambiente PORT.<br>

**Exemplos de Requisições**
<br>Aqui estão exemplos de como realizar operações CRUD na API:<br>

**Create (POST)**
<br>POST /api/blogs<br>
<br>Content-Type: application/json<br>

<br>{<br>
  <br>"title": "Título do Blog",<br>
  <br>"body": "Conteúdo do Blog",<br>
  <br>"image": "URL da Imagem"<br>
<br>}<br>

**Read (GET)**
<br>GET /api/blogs<br>
<br>GET /api/blogs/:id<br>

**Update (PUT)**

<PUT /api/blogs/:id<br>
<br>Content-Type: application/json<br>

<br>{<br>
  <br>"title": "Novo Título do Blog",<br>
  <br>"body": "Novo Conteúdo do Blog",<br>
 <br>"image": "Nova URL da Imagem"<br>
}<br>

**Delete (DELETE)**

<br>DELETE /api/blogs/:id<br>

**Ferramentas Utilizadas para Testes**<br>
Para testar a aplicação, foram utilizadas as seguintes ferramentas:<br>

Mocha: Framework de testes JavaScript.<br>
Chai: Biblioteca de asserções para Node.js.<br>
Chai-HTTP: Extensão do Chai para testar APIs HTTP.<br>
Thunder Client: Uma extensão do Visual Studio Code para testar APIs.<br>

**Demonstração dos Testes**
<br>Os testes podem ser executados utilizando o seguinte comando:<br>

npm test<br>
Isso iniciará a execução dos testes definidos no arquivo test.js. Os resultados dos testes serão exibidos no terminal.<br>
Certifique-se de ter o ambiente configurado corretamente antes de executar os testes.<br>


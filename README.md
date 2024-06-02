
<br>** ---- Integrantes do Projeto ---- **<br>
Gustavo Grassini Calabrez<br>
Bruno da Silva<br>
Pedro H. Papa<br>
Cauã Barchi<br>
Leonardo Culler<br>

**CRUD Application with Node.js and MongoDB**
<br>Este é um projeto de CRUD (Create, Read, Update, Delete) desenvolvido com Node.js e MongoDB.<br>

**Descrição do Projeto**
<br>Este projeto implementa uma API para gerenciamento de blogs, onde é possível criar, ler, atualizar e deletar blogs.<br>

**Configuração do Ambiente**
<br>Certifique-se de ter os seguintes itens instalados em sua máquina:<br>

<br>Node.js (versão 12 ou superior)<br>
<br>MongoDB (versão 4 ou superior)<br>

**Executando a Aplicação**
<br>Clone o repositório:<br>

<br>git clone (https://github.com/zcenik/CRUD-APP-Node.js-MongoDB-main/tree/main)<br>
<br>Navegue até o diretório do projeto:<br>

<br>cd (https://github.com/zcenik/CRUD-APP-Node.js-MongoDB-main/tree/main)<br>

**Instale as dependências:**

<br>npm install<br>

**Instruções para Executar a Aplicação**
<br>Para iniciar o servidor, execute o comando:<br>

<br>npm start<br>

<br>A aplicação estará disponível em http://localhost:3001.<br>

**Exemplos de Requisições**
<br>Abaixo estão exemplos de requisições para cada operação:<br>

**Criar um Blog (Create)**
<br>POST /api/blogs<br>
<br>Content-Type: application/json<br>

<br>{<br>
  <br>"title": "Título do Blog",<br>
  <br>"body": "Conteúdo do Blog",<br>
 <br>"image": "URL da Imagem"<br>
<br>}<br>
**Ler um Blog pelo ID (Read)**

<br>GET /api/blogs/:id<br>

**Atualizar um Blog pelo ID (Update)**

<br>PUT /api/blogs/:id<br>
<br>Content-Type: application/json<br>

<br>{<br>
  <br>"title": "Novo Título do Blog",<br>
  <br>"body": "Novo Conteúdo do Blog",<br>
  <br>"image": "Nova URL da Imagem"<br>
}

**Deletar um Blog pelo ID (Delete)**

<br>DELETE /api/blogs/:id<br>

**Ferramentas Utilizadas para Testes**
<br>Thunder Client - Para realizar testes de API.<br>
<br>Mocha e Chai - Para testes automatizados.<br>

**Demonstração dos Testes**
<br>Para demonstrar a execução dos testes utilizando Thunder Client, siga os passos abaixo:<br>

Abra o Visual Studio Code.<br>
Instale a extensão Thunder Client.<br>
Abra o arquivo test_requests.http disponível na raiz do projeto.<br>
Execute as requisições de teste utilizando o Thunder Client.<br>
Verifique os resultados das requisições e as respostas recebidas.<br>


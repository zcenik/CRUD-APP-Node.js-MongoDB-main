
<br>** ---- Integrantes do Projeto ---- **<br>
Gustavo Grassini Calabrez<br>
Bruno da Silva<br>
Pedro H. Papa<br>
Cauã Barchi<br>
Leonardo Culler<br>

**CRUD Application with Node.js and MongoDB**
Este é um projeto de CRUD (Create, Read, Update, Delete) desenvolvido com Node.js e MongoDB.

**Descrição do Projeto**
Este projeto implementa uma API para gerenciamento de blogs, onde é possível criar, ler, atualizar e deletar blogs.

**Configuração do Ambiente**
Certifique-se de ter os seguintes itens instalados em sua máquina:

Node.js (versão 12 ou superior)
MongoDB (versão 4 ou superior)

**Executando a Aplicação**
Clone o repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git
Navegue até o diretório do projeto:

cd seu-repositorio
**Instale as dependências:**

npm install

**Instruções para Executar a Aplicação**
Para iniciar o servidor, execute o comando:

npm start

A aplicação estará disponível em http://localhost:3001.

**Exemplos de Requisições**
Abaixo estão exemplos de requisições para cada operação:

**Criar um Blog (Create)**
POST /api/blogs
Content-Type: application/json

{
  "title": "Título do Blog",
  "body": "Conteúdo do Blog",
  "image": "URL da Imagem"
}
**Ler um Blog pelo ID (Read)**

GET /api/blogs/:id

**Atualizar um Blog pelo ID (Update)**

PUT /api/blogs/:id
Content-Type: application/json

{
  "title": "Novo Título do Blog",
  "body": "Novo Conteúdo do Blog",
  "image": "Nova URL da Imagem"
}

**Deletar um Blog pelo ID (Delete)**

DELETE /api/blogs/:id

**Ferramentas Utilizadas para Testes**
Thunder Client - Para realizar testes de API.
Mocha e Chai - Para testes automatizados.

**Demonstração dos Testes**
Para demonstrar a execução dos testes utilizando Thunder Client, siga os passos abaixo:

Abra o Visual Studio Code.
Instale a extensão Thunder Client.
Abra o arquivo test_requests.http disponível na raiz do projeto.
Execute as requisições de teste utilizando o Thunder Client.
Verifique os resultados das requisições e as respostas recebidas.


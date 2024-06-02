**CRUD Application with Node.js and MongoDB**

Este é um projeto CRUD (Create, Read, Update, Delete) desenvolvido com Node.js e MongoDB.

**Pré-requisitos:**
<br>Certifique-se de ter os seguintes itens instalados em sua máquina:<br>

<br>Node.js (versão 12 ou superior)<br>
<br>MongoDB (versão 4 ou superior)<br>

**Configuração do Ambiente:**
<br>Crie um arquivo .env na raiz do projeto e adicione a URL de conexão do MongoDB:<br>

<br>"MONGODB_URI=mongodb://localhost:27017/CRUD"<br>

<br>Você pode substituir a URL acima pela URL de conexão do seu MongoDB, caso esteja usando um serviço como MongoDB Atlas.<br>

**Executando a Aplicação:**
<br>Para iniciar o servidor, execute o comando:<br>

<br>"npm start"<br>

<br>A aplicação estará disponível em http://localhost:3001.<br>

**Rotas da API:**
<br>Abaixo estão as rotas disponíveis na API:<br>

<br>GET /api/blogs - Retorna todos os blogs<br>
<br>POST /api/blogs - Cria um novo blog<br>
<br>GET /api/blogs/:id - Retorna um blog pelo ID<br>
<br>PUT /api/blogs/:id - Atualiza um blog pelo ID<br>
<br>DELETE /api/blogs/:id - Deleta um blog pelo ID<br>

**Testes**
<br>Para executar os testes, estamos utilizando o Thunder Client. Siga as instruções abaixo para configurar e executar os testes:<br>

<br>Abra o VS Code e instale a extensão Thunder Client.<br>
<br>Crie uma nova coleção de testes no Thunder Client.<br>
<br>Adicione as requisições necessárias para testar as rotas da API conforme descrito na seção anterior.<br>
<br>Execute os testes diretamente no Thunder Client.<br>

**Testes Automatizados**

<br>Também configuramos testes automatizados com Mocha e Chai. Para executar os testes automatizados, utilize o comando:<br>

<br>"npm test"<br>

<br>** ---- Integrantes do Projeto ---- **<br>
Gustavo Grassini Calabrez<br>
Bruno da Silva<br>
Pedro H. Papa<br>
Cauã Barchi<br>
Leonardo Culler<br>

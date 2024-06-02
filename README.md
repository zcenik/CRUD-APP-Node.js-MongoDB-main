CRUD Application with Node.js and MongoDB

Este é um projeto CRUD (Create, Read, Update, Delete) desenvolvido com Node.js e MongoDB.

Pré-requisitos:
Certifique-se de ter os seguintes itens instalados em sua máquina:

Node.js (versão 12 ou superior)
MongoDB (versão 4 ou superior)

Configuração do Ambiente
Crie um arquivo .env na raiz do projeto e adicione a URL de conexão do MongoDB:

"MONGODB_URI=mongodb://localhost:27017/CRUD"

Você pode substituir a URL acima pela URL de conexão do seu MongoDB, caso esteja usando um serviço como MongoDB Atlas.

Executando a Aplicação:
Para iniciar o servidor, execute o comando:

"npm start"

A aplicação estará disponível em http://localhost:3001.

Rotas da API:
Abaixo estão as rotas disponíveis na API:

GET /api/blogs - Retorna todos os blogs
POST /api/blogs - Cria um novo blog
GET /api/blogs/:id - Retorna um blog pelo ID
PUT /api/blogs/:id - Atualiza um blog pelo ID
DELETE /api/blogs/:id - Deleta um blog pelo ID

Testes
Para executar os testes, estamos utilizando o Thunder Client. Siga as instruções abaixo para configurar e executar os testes:

Abra o VS Code e instale a extensão Thunder Client.
Crie uma nova coleção de testes no Thunder Client.
Adicione as requisições necessárias para testar as rotas da API conforme descrito na seção anterior.
Execute os testes diretamente no Thunder Client.

Testes Automatizados

Também configuramos testes automatizados com Mocha e Chai. Para executar os testes automatizados, utilize o comando:

"npm test"

---- Integrantes do Projeto ----
Gustavo Grassini Calabrez
Bruno da Silva
Pedro H. Papa
Cauã Barchi
Leonardo Culler

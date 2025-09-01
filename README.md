# Lista-de-Compras
Atividade 02 da matéria Web III: Criar uma lista de compras integrada ao MongoDB

🛒 Lista de Compras - CRUD com Node.js, Express, TypeScript e MongoDB
Este projeto é uma aplicação web simples e funcional de Lista de Compras. Ele foi desenvolvido como um exercício prático para demonstrar a criação de um CRUD (Create, Read, Update, Delete) completo, utilizando tecnologias modernas no backend e um frontend leve.

A aplicação permite que o usuário adicione, liste, edite e remova itens de uma lista de compras, com o valor total calculado automaticamente e os dados persistidos em um banco de dados.

✨ Funcionalidades
Adicionar Novo Item: Formulário para incluir o nome, preço e quantidade de um produto.

Listar Itens: Exibe todos os produtos cadastrados em uma tabela.

Calcular Total: O total por item (preço x quantidade) e o total geral da lista são calculados e exibidos dinamicamente.

Editar Itens: Botão para preencher o formulário com os dados de um item existente para edição.

Excluir Itens: Botão para remover um item permanentemente da lista.

🚀 Tecnologias Utilizadas
Frontend
HTML5: Estrutura da página.

CSS3: Estilização moderna e responsiva.

JavaScript: Lógica de manipulação do DOM e comunicação com a API.

Backend
Node.js: Ambiente de execução.

Express: Framework para criar a API REST.

TypeScript: Adiciona tipagem estática, garantindo um código mais robusto e livre de erros.

Mongoose: Biblioteca para modelagem de dados e comunicação com o MongoDB.

MongoDB: Banco de dados NoSQL para persistir os dados da lista.

⚙️ Como Rodar o Projeto
Siga os passos abaixo para configurar e executar o projeto em sua máquina.

Pré-requisitos
Node.js (versão 14 ou superior)

npm (gerenciador de pacotes do Node.js)

MongoDB instalado e rodando localmente.

Instalação
Clone este repositório para a sua máquina:

Bash

git clone "https://github.com/PeedroPrado/Lista-de-Compras.git"
cd [pasta-do-seu-projeto]
Instale as dependências do projeto no backend:

Bash

npm install
Configuração do Banco de Dados
Certifique-se de que o seu serviço do MongoDB está em execução.

O servidor está configurado para se conectar à URL mongodb://127.0.0.1:27017/shoppingitems. Se o seu MongoDB estiver em uma porta ou URL diferente, ajuste a string de conexão no arquivo do servidor.

Execução
Inicie o servidor de backend. Ele irá observar as mudanças e reiniciar automaticamente.

Bash

npm run dev
Abra o arquivo index.html em seu navegador. Como o frontend é servido diretamente do backend, acesse:

http://localhost:3000
Agora você pode interagir com a aplicação e começar a gerenciar sua lista de compras!

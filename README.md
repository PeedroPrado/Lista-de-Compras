# 🛒 Lista de Compras  

Atividade 02 da matéria **Web III**: Criar uma lista de compras integrada ao **MongoDB**.  

Este projeto é uma aplicação web simples e funcional de **Lista de Compras**, desenvolvida como um exercício prático para demonstrar a criação de um **CRUD (Create, Read, Update, Delete)** completo, utilizando tecnologias modernas no backend e um frontend leve.  

A aplicação permite que o usuário adicione, liste, edite e remova itens de uma lista de compras, com o valor total calculado automaticamente e os dados persistidos em um banco de dados.  

---

## ✨ Funcionalidades  

✅ **Adicionar Novo Item** – Formulário para incluir o nome, preço e quantidade de um produto.  
✅ **Listar Itens** – Exibe todos os produtos cadastrados em uma tabela.  
✅ **Calcular Total** – Exibe o total por item (preço x quantidade) e o total geral da lista dinamicamente.  
✅ **Editar Itens** – Permite atualizar as informações de um item existente.  
✅ **Excluir Itens** – Remove permanentemente um item da lista.  

---

## 🚀 Tecnologias Utilizadas  

### Frontend  
- **HTML5** – Estrutura da página  
- **CSS3** – Estilização moderna e responsiva  
- **JavaScript** – Manipulação do DOM e integração com a API  

### Backend  
- **Node.js** – Ambiente de execução  
- **Express** – Framework para API REST  
- **TypeScript** – Tipagem estática para maior robustez  
- **Mongoose** – Modelagem de dados e integração com o MongoDB  
- **MongoDB** – Banco de dados NoSQL  

---

## ⚙️ Como Rodar o Projeto  

### 📌 Pré-requisitos  
- [Node.js](https://nodejs.org/) (v14 ou superior)  
- [npm](https://www.npmjs.com/)  
- [MongoDB](https://www.mongodb.com/) instalado e rodando localmente  

---

### 📥 Instalação  

Clone este repositório:  
```bash
git clone https://github.com/PeedroPrado/Lista-de-Compras.git
cd Lista-de-Compras

Instale as dependências no backend:

npm install

🛠️ Configuração do Banco de Dados

Certifique-se de que o MongoDB está em execução.

O servidor está configurado para se conectar em:

mongodb://127.0.0.1:27017/shoppingitems

▶️ Execução

Inicie o servidor backend:

npm run dev


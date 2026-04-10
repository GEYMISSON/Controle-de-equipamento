# Controle-de-equipamento

# 💻 Sistema de Chamados e Controle de Equipamentos

Sistema web desenvolvido para gerenciamento de:

- 📋 Chamados técnicos
- 🏢 Setores
- 👤 Usuários
- 🖥️ Equipamentos (PCs)
- 🔧 Peças

![Menu Lateral](./Images/MenuLateral.png)

---

# 🚀 Tecnologias Utilizadas

- Node.js
- Express
- MongoDB Atlas
- Mongoose
- JWT (Autenticação)
- HTML, CSS e JavaScript

---

# 🔐 Funcionalidades

### 👤 Usuários
- Cadastro de usuários
- Login com autenticação JWT
- Controle de acesso (admin / user)

![Cadastro de Usuários](./Images/CadastrodeUsuários.png)

### 🏢 Setores
- Cadastro de setores
- Listagem e exclusão

![Cadastro de Setores](./Images/CadastrodeSetores.png)

### 📋 Chamados
- Abertura de chamados
- Associação com setor e usuário
- Controle de revisão
- Geração automática de código (tombo)

![Cadastro de Chamados](./Images/CadastrodeChamados.png)

### 🖥️ Equipamentos
#### PCs
- Cadastro com:
  - Sistema Operacional
  - Placa Mãe
  - Processador
  - Memória
  - Armazenamento
  - Fonte
- Código automático (FCJZTI0001...)

![Cadastro de Computadores/Notebooks](./Images/CadastrodeComputadoresNotebooks.png)

#### Peças
- Cadastro de peças
- Controle de estoque básico

![Cadastro de Peças](./Images/CadastrodePeças.png)

### 📊 Dashboard
- Total de usuários
- Total de setores
- Alertas de revisão

![Tela do Dashboard](./Images/TeladoDashboard.png)

---

# ⚙️ Como Rodar o Projeto

## 1. Clonar o repositório

```bash
git clone https://github.com/SEU_USUARIO/SEU_REPO.git
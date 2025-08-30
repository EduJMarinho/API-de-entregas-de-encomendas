
🚀 Rocketlog

Rocketlog é uma API RESTful desenvolvida com Node.js e TypeScript, focada em autenticação de usuários e testes automatizados. O projeto utiliza Prisma para gerenciamento de banco de dados e Supertest + Jest para testes de integração.

📦 Tecnologias

- Node.js + Express
- TypeScript
- Prisma ORM
- PostgreSQL (via Docker)
- Jest + Supertest para testes
- JWT para autenticação

⚙️ Instalação e Configuração

# Clone o repositório
git clone https://github.com/EduJMarinho/rocketlog.git
cd rocketlog

# Instale as dependências
npm install


Crie um arquivo .env com base no .env-exemple:
DATABASE_URL="postgresql://usuario:senha@localhost:5432/rocketlog"
JWT_SECRET="sua_chave_secreta"



🐳 Usando Docker

docker-compose up -d


Isso irá subir o banco PostgreSQL e conectar com o Prisma.

🧪 Executando os Testes

npm test


Os testes estão configurados com Jest e Supertest para validar rotas e autenticação.

📚 Endpoints principais
|  |  |  | 
|  | /users |  | 
|  | /sessions |  | 
|  | /profile |  | 



🔐 Autenticação

Após o login, envie o token JWT no header:
Authorization: Bearer <token>



📁 Estrutura de Pastas

rocketlog/
├── prisma/           # Migrations e schema do banco
├── src/
│   ├── controllers/  # Lógica das rotas
│   ├── routes/       # Definição das rotas
│   ├── services/     # Regras de negócio
│   └── middlewares/  # Autenticação, validações
├── jest.config.ts
├── docker-compose.yml
└── .env-exemple

------------------------------------

📄 Licença

Este projeto está sob a licença MIT.

------------------------------------

🧠 Analisar 📚 Aprender ❌ Errar  
   🔁 Refatorar  🛠️ Construir  
          
→ Esse é o caminho do Dev. — Edu Marinho




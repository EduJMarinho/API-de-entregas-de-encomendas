🚀 Rocketlog
Aplicação de registro de logs com autenticação JWT e integração com MongoDB.
📦 Tecnologias
- Node.js
- Express
- MongoDB + Mongoose
- JWT
- Docker
📁 Estrutura de Pastas
rocketlog/
├── src/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   └── utils/
├── .env.example
├── Dockerfile
├── docker-compose.yml
└── README.md


⚙️ Instalação
git clone https://github.com/EduJMarinho/rocketlog.git
cd rocketlog
npm install


🛠️ Configuração
Crie um arquivo .env com base no .env.example:
PORT=3000
MONGO_URI=mongodb://localhost:27017/rocketlog
JWT_SECRET=sua_chave_secreta


▶️ Executando
npm start


Ou com Docker:
docker-compose up


🔐 Autenticação
As rotas protegidas exigem o header:
Authorization: Bearer <seu_token>


📮 Endpoints principais
|  |  |  | 
|  |  |  | 
|  |  |  | 
|  |  |  | 






------------------------------------

📄 Licença

Este projeto está sob a licença MIT.

------------------------------------

🧠 Analisar 📚 Aprender ❌ Errar  
   🔁 Refatorar  🛠️ Construir  
          
→ Esse é o caminho do Dev. — Edu Marinho




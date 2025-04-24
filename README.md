# Nutricare

Nutricare é um sistema de gestão para clínicas de nutrição. A aplicação permite controlar pacientes, agendar consultas, montar planos alimentares personalizados e registrar alimentos com suas respectivas quantidades.

## Tecnologias Utilizadas

Frontend:
- Angular
- TypeScript

Backend:
- Node.js
- Express.js
- Sequelize ou Prisma (ORM)

Banco de Dados:
- FireBase

## Estrutura do Projeto

nutricare/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middlewares/
│   │   └── index.js
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── app/
│   │   │   ├── components/
│   │   │   ├── pages/
│   │   │   ├── services/
│   │   │   └── app.module.ts
│   └── angular.json
└── README.md

## Funcionalidades

- Cadastro e gerenciamento de pacientes
- Agendamento e controle de consultas
- Criação de planos alimentares personalizados
- Registro de alimentos e quantidades
- Histórico de atendimentos por paciente
- Painel administrativo para gestão dos dados

## Instalação

### Backend

1. Acesse a pasta backend:
cd backend

2. Instale as dependências:
npm install

3. Configure o banco de dados:
Crie um arquivo .env com os seguintes dados:

DB_HOST=localhost  
DB_USER=root  
DB_PASSWORD=sua_senha  
DB_NAME=nutricare_db  
PORT=3000

4. Execute as migrações:
npx sequelize db:create  
npx sequelize db:migrate

5. Inicie o servidor:
npm run dev

### Frontend

1. Acesse a pasta frontend:
cd frontend

2. Instale as dependências:
npm install

3. Inicie o projeto:
ng serve

Acesse o sistema em http://localhost:4200

## Autenticação

Será utilizada autenticação com JWT no backend, e guards no Angular para proteger rotas no frontend.

## Melhorias Futuras

- Integração com e-mail ou WhatsApp
- Área do paciente com acesso aos planos alimentares
- Dashboard com gráficos e métricas

## Contribuições

Contribuições são bem-vindas! Para grandes mudanças, abra uma issue para discutir o que pretende modificar.

## Licença

MIT


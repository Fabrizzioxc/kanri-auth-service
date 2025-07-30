# 🔐 Kanri - Auth Service

**Descripción:**  
Microservicio encargado de la autenticación y autorización de usuarios. Emite JWT para el rol de administrador.

## 🚀 Tecnologías utilizadas
- Express.js
- TypeScript
- Prisma ORM
- PostgreSQL
- Zod
- Bcrypt
- JWT
- Dotenv

## 🧱 Modelo principal
- `User`

## 📦 Comandos útiles

```bash
npm install
npx prisma generate
npx prisma migrate dev --name init
npm run dev
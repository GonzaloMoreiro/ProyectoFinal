<p align="center"> <img src="./devcore-banner.png" alt="DevCore Project" width="600"/> </p>
💻 Proyecto DevCore - Plataforma de Cursos

Full Stack Developer | TypeScript | Node.js | React | NestJS | PostgreSQL

🖥️ Descripción

DevCore es una plataforma de cursos online que permite a los usuarios registrarse, explorar cursos y acceder a contenido educativo.
El proyecto combina un frontend moderno con Next.js/React y un backend escalable con NestJS y PostgreSQL.

Funcionalidades principales:

Registro e inicio de sesión de usuarios

Gestión de cursos, categorías y contenidos

Autenticación y autorización con JWT

Dashboard para administración de cursos y usuarios

⚙️ Tecnologías

Frontend:

Next.js

React

TypeScript

CSS / Tailwind

Backend:

NestJS

TypeScript

PostgreSQL (via TypeORM)

JWT para autenticación

Swagger para documentación de API

🚀 Instalación y ejecución
Clonar el proyecto
git clone <REPO_URL>
cd devcore

Frontend
cd frontend
npm install
npm run dev
# o yarn dev / pnpm dev


Abre http://localhost:3000
 en tu navegador.

Backend
cd backend
npm install
npm run start:dev
# Producción: npm run start:prod

Pruebas
npm run test      # Unitarias
npm run test:e2e  # End-to-end
npm run test:cov  # Cobertura

🌐 Despliegue

Frontend: recomendado en Vercel
Backend: desplegable en AWS/Mau usando NestJS Mau:

npm install -g @nestjs/mau
mau deploy

🔗 Proyecto destacado

Repositorio GitHub: DevCore

Plataforma educativa desarrollada con enfoque full stack, escalable y modular.

📚 Recursos

NestJS Docs

Next.js Docs

TypeORM Docs

Tailwind CSS Docs

📝 Licencia

MIT License – Proyecto Open Source

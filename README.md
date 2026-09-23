# Enanos Backend

Backend desarrollado con Express, TypeScript, Prisma y SQLite.

## Instalación

Instalar las dependencias:

npm install

## Configuración

Crear un archivo `.env` en la raíz del proyecto con:

DATABASE_URL="file:./dev.db"

PORT=3000

## Inicializar la base de datos

npm run db:init

## Ejecutar el servidor

npm run dev

La API estará disponible en:

http://localhost:3000

## Endpoints principales

- GET /api/personas
- POST /api/personas
- PATCH /api/personas/:id
- DELETE /api/personas/:id
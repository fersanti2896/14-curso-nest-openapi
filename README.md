# Documentación de API - Teslo REST Server

Se crea la documentación de Teslo REST Server con `OpenAPI`.

## Teslo API
1. Instalar las dependencias de `node_modules` con el comando:
```
npm install
```
2. Renombrar el archivo `.env.template` a `.env`.
3. Definir las variables de entorno.
4. Levantar la base de datos con `Docker`:
```
docker-compose up -d
``` 
5. Ejecutar el SEED para reestablecer la Base de datos de tipo `GET`: 
```
http://localhost:300'/api/seed
```
6. Levantar el proyecto en entorno de desarrollo: 
```
npm run start:dev
``` 
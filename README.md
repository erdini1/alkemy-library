# Alkemy Library

El proyecto fue desarrollado en equipo como parte del programa de Aceleración de Talento Fueguino basado en la tecnologia SQL+NODE.

Alkemy Library consiste en una API de gestión de datos que permite a sus usuarios realizar operaciones de consulta y modificación de datos. 

## Características principales:
  #### Usuarios:

  - **Registro y Autenticación:**
      - Los usuarios pueden registrarse y autenticarse en la plataforma.
  - **Préstamos de Libros:**
      - Posibilidad de solicitar préstamos de libros.
  - **Chat:**
      - Acceso al chat para intercambiar opiniones y .
  - **Reseñas:**
      - Generar reseñas de libros, colocar puntaje y obtener recomendaciones
  - **Participación en Eventos:**
      - Participación en eventos relacionados con la biblioteca.

  #### Administradores:

  - **Gestión Integral:**
      - Administradores tienen un control completo sobre los diversos aspectos relacionados con la información almacenada en la aplicación.
      - Añadir o eliminar libros, autores, géneros y más.

## Implementación tecnica

- Requisitos Funcionales:
    - Cumplimiento de requisitos establecidos por Alkemy, permitiendo gestionar datos en la biblioteca.
- Diseño de la Base de Datos:
- Roles y Permisos:
    - Implementación de roles y permisos para usuarios, administradores y superadmin.
- Rutas y Controladores:
- Validación de Datos:
- Seguridad:
    - Implementación de medidas de seguridad, incluyendo autenticación de usuarios y protección contra posibles ataques.

## Documentación:
La documentación de la API se ha realizado utilizando Swagger y se puede acceder a través del siguiente enlace cuando el servidor está en ejecución:

**[Acceder a la documentación](http://localhost:3000/api-docs)**

## Tecnologias y dependencias utilizadas:

- **Bcrypt**: v5.1.1
- **Chai**: v4.3.10
- **Compression**: v1.7.4
- **Cookie-parser**: v1.4.6
- **Cors**: v2.8.5
- **Csurf**: v1.11.0
- **Csv-writer**: v1.6.0
- **Dotenv**: v16.3.1
- **Dropbox**: v10.34.0
- **Express**: v4.18.2
- **Express-handlebars**: v7.1.2
- **Helmet**: v7.1.0
- **Jest**: v29.7.0
- **Joi**: v17.11.0
- **JsonWebToken**: v9.0.2
- **Mocha**: v10.2.0
- **Node.js**: v18.16.1
- **Node-cron**: v3.0.3
- **Nodemailer**: v6.9.7
- **Sequelize**: v6.35.1
- **Socket.io**: v4.7.2
- **SwaggerJSDoc**: v6.2.8
- **SwaggerUiExpress**: v5.0.0
- **Yamljs**: v0.3.0
- **Herramientas de Prueba**: Postman para el manejo de endpoints
- **Herramientas de Documentación**: Swagger

# Instalacion del proyecto

## 1) Clonar el repositorio del proyecto desde github

Usa el siguiente comando en la terminal:

`git clone https://github.com/erdini1/alkemy-library.git`

## 2) Instalar dependencias

Dentro de la raiz del proyecto: `npm install`

## 3) Configuración de variables de entorno
1) Crea un archivo `.env` en la raíz del proyecto.
2) Añade las variables de entorno necesarias indicadas en env.sample

## 4) Comandos principales

- Ejecutar el proyecto: `npm start`
- Ejecutar backup de la base de datos en dropbox: `npm run backup`
- Ejecutar tests: `npm run test`

## Estado

Proyecto finalizado en 3 sprints.

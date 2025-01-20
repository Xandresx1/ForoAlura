# ForoHub: Plataforma de Discusión 🎉

ForoHub es una API RESTful construida con **Spring Framework**, diseñada para gestionar tópicos de discusión en una plataforma. El objetivo de este proyecto es ofrecer una API eficiente que permita a los usuarios interactuar con los tópicos, sus respuestas y gestionar usuarios de manera segura.

## Características Principales 🚀

La API proporciona funcionalidades para gestionar los siguientes elementos:

- **Tópicos** 📚:
  - Crear, leer, actualizar y eliminar tópicos.
  - Obtener una lista completa de los tópicos.
  - Ver detalles de un tópico específico.

- **Respuestas** 💬:
  - Añadir respuestas a los tópicos.
  - Ver las respuestas existentes en cada tópico.

- **Usuarios** 👤:
  - Registrar nuevos usuarios.
  - Autenticar usuarios mediante JWT.

## Propósitos del Proyecto 🎯

- Desarrollar una **API RESTful** siguiendo las mejores prácticas.
- Aplicar **validaciones de entrada** basadas en reglas de negocio.
- Utilizar una **base de datos relacional** para la persistencia.
- Implementar **autenticación y autorización** mediante **JWT**.
- Documentar la API utilizando **Swagger** para facilitar la integración.

## Endpoints 🌐

A continuación, se detallan los endpoints disponibles:

- **Tópicos** (`/api/topicos`) 📚:
  - `GET /`: Listar todos los tópicos.
  - `POST /`: Crear un nuevo tópico.
  - `GET /{id}`: Obtener un tópico específico.
  - `PUT /{id}`: Actualizar un tópico existente.
  - `DELETE /{id}`: Eliminar un tópico.

- **Usuarios** (`/api/usuarios`) 👤:
  - `POST /registro`: Registrar un nuevo usuario.
  - `POST /login`: Autenticar un usuario y generar un token JWT.

- **Respuestas** (`/api/respuestas`) 💬:
  - `GET /`: Obtener todas las respuestas.
  - `POST /`: Añadir una nueva respuesta a un tópico.

## Requisitos 🛠️

### Versiones 📦

- **Java**: 17 o superior ☕
- **Maven**: 4.x 🔧
- **Spring Boot**: 3.2.3 o superior 🚀
- **MySQL**: 8.x o superior 🐬
- **PostgreSQL**: 16.x o superior 🍇

### Dependencias 📚

- **Lombok**: Para simplificar el código. ✨
- **Spring Web**: Para crear los servicios RESTful. 🌐
- **Spring Boot DevTools**: Herramientas de desarrollo para facilitar la programación. 🛠️
- **Spring Data JPA**: Para la interacción con la base de datos. 🗄️
- **Flyway Migration**: Para gestionar las migraciones de base de datos. 🔄
- **MySQL Driver**: Conector de MySQL. 🐬
- **Validation**: Validación de datos de entrada. ✔️
- **Spring Security**: Seguridad y autenticación con JWT. 🔐
- **Spring Doc**: Documentación de la API con Swagger. 📖
- **Auth0**: Gestión de tokens JWT y autenticación. 🛡️

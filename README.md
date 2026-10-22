# Qalikay – Backend

API REST desarrollada con Java y Spring Boot como parte del proyecto universitario Qalikay. Se encarga de gestionar la información del sistema, procesar las solicitudes del frontend y conectar la aplicación con una base de datos PostgreSQL.

## Funcionalidades

- Gestión de productos y recetas tradicionales.
- Registro de ventas y detalles de venta.
- Administración de usuarios y roles.
- Autenticación mediante JWT.
- Gestión de opciones de pago, certificados y comentarios.
- Consultas y reportes relacionados con productos, usuarios y ventas.

## Tecnologías utilizadas

- **Java 17:** lenguaje de programación.
- **Spring Boot:** desarrollo de la API REST.
- **Spring Data JPA:** acceso y manejo de datos.
- **PostgreSQL:** base de datos relacional.
- **Spring Security y JWT:** autenticación y control de acceso.
- **Swagger / OpenAPI:** documentación de los endpoints.
- **Maven:** gestión de dependencias.

## Instalación y ejecución

Para ejecutar el proyecto localmente, es necesario contar con Java 17, Maven (o utilizar Maven Wrapper) y PostgreSQL.

1. Clonar el repositorio:

   `git clone https://github.com/GianpieroFlores/backend-sistema-web.git`

2. Ingresar a la carpeta del proyecto:

   `cd backend-sistema-web/backend-qalikay/qalikay`

3. Configurar la conexión a PostgreSQL en `src/main/resources/application.properties`, utilizando credenciales locales que no se publiquen en el repositorio.

4. Ejecutar el proyecto en Windows:

   `mvnw.cmd spring-boot:run`

   En Linux o macOS:

   `./mvnw spring-boot:run`

5. Una vez iniciado el servidor, acceder a la documentación de Swagger:

   `http://localhost:8082/swagger-ui/index.html`

## Frontend

La API se utiliza junto con una aplicación web desarrollada en Angular.

El código del frontend se encuentra en el siguiente repositorio:

[Qalikay – Frontend](https://github.com/GianpieroFlores/frontend-sistema-web)

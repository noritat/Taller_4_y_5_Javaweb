
# Proyecto 4 tipos de conexión a base de datos MySQL con Java y Encrypt - Decrypt MySQL

Este proyecto consiste en mostrar los 4 tipos de conexiones a base de datos MYSQL desde Java los cuales son:
# BasicConnection:

![1](https://user-images.githubusercontent.com/128448216/236710633-24ce0ac1-78df-4b13-9e46-e28680391204.png) widh:100px

# BasicConnectionWithResources:

![2](https://user-images.githubusercontent.com/128448216/236710726-fcc025ca-4e08-461d-8288-dc17716da1a0.png)

# BasicConnectionSingleton:

![3 1](https://user-images.githubusercontent.com/128448216/236710805-a2b0648c-e894-4a5a-b1b4-f2ee3d995ee3.png)

# ConnectionPool

![4](https://user-images.githubusercontent.com/128448216/236710849-e3bc0d7d-8bcc-46b0-b8a5-ccadf0561ee5.png)

Ademas tambien consiste en realizar un Encrypt y Decrypt en MYSQL:




# Requisitos

Para ejecutar este proyecto se necesitan los siguientes requisitos:
- Java 8 o superior
- Maven 2.9.0 o superior
- Una base de datos MySQL
- Widfly 27.0.1
- IntelliJ IDEA

# Configuración de la base de datos

Antes de ejecutar la aplicación, es necesario configurar la conexión a la base de datos en la carpeta Util dentro de las 4 clases presentadas anteriormente debe tener el siguiente contenido:

-  private static final String URL= "jdbcmysql://localhost:3306/my_app serverTimezone=America/Bogota";"
- private static final String USER ="El usuario que crees en mysql";
- private static final String PASS="la contraseña que quieras";

# Autor

Este proyecto fue creado por Angely Estrada.
Derechos reservados a Servicio Nacional de Aprendizaje (SENA).

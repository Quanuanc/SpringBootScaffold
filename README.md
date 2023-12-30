# SpringBootScaffold
`SpringBootScaffold` is a scaffold for Spring Boot project. It contains basic configurations and common used components.
- Spring Boot: `3.1.0`
- Spring JPA: `Same as Spring Boot`
- Spring Web: `Same as Spring Boot`
- Spring Test: `Same as Spring Boot`
- Spring Doc (Swagger): `2.3.0`
- Lombok: `1.18.26`
- MySQL Connector: `8.0.27`


## How to use
1. Make sure your IDEA IDE setting to JDK 17.
   ![](ide.png)
2. Create a MySQL database named `springboot_scaffold`.
3. Change MySQL connection string in `application.yml`, or add environment variables. Default MySQL configuration is:
    - host: `localhost`
    - port: `3306`
    - database: `springboot_scaffold`
    - username: `root`
    - password: `12345678`
4. Run `MainApplication.java` to start the server.
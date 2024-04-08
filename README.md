# STUDENT_API_CRUD

Developing an  CURD API using  SPRING BOOT and Testing it in a following way :-

1. **Setup Spring Boot Project**: Start by creating a new Spring Boot project using Spring Initializr or your preferred IDE. This project will serve as the foundation for your CRUD API.

2. **Define Entity Class**: Create a Java class to represent your entity, in this case, the `Student` class. This class will have attributes that map to fields in your database table, along with appropriate annotations to mark it as an entity.

3. **Create Repository Interface**: Define a repository interface, which extends `JpaRepository` (provided by Spring Data JPA). This interface will handle the CRUD operations for your entity.

4. **Implement Service Layer**: Develop a service class to contain the business logic related to your entity. This class will interact with the repository to perform CRUD operations and apply any necessary business logic.

5. **Build Controller**: Create a controller class to handle HTTP requests and responses. This class will define methods to handle CRUD operations (Create, Read, Update, Delete), each mapped to specific HTTP endpoints using appropriate annotations like `@PostMapping`, `@GetMapping`, `@PutMapping`, and `@DeleteMapping`.

6. **Configure Database Connection**: Configure your database connection details in the `application.properties` file. This includes properties such as the database URL, username, password, and driver class.

7. **Testing**: Once your CRUD API is implemented, you can test it using tools like Postman, curl, or any REST client. Send HTTP requests to the appropriate endpoints to create, read, update, and delete student records.

8. **Upload to GitHub**: Finally, upload your project to GitHub to share the code with others. Ensure that your repository contains all the necessary files and configurations to run the application successfully.

By following these steps, you'll have a basic CRUD API implemented using Spring Boot. This API will allow you to perform CRUD operations on a simple `Student` entity, exposing endpoints that can be accessed over HTTP.


-
  LINTA A NANDGAONKAR

# Blog-website
This is a full-featured Blog Website built using Java Spring Boot. The application allows users to read, create, update, and delete blog posts. It includes user authentication, role-based access control, and an admin panel for managing content and categories.

# Blog Website

This is a Spring Boot blog website project.  
Users can view posts, categories, and comments.

## Features

- User registration and login  
- Create, edit, and delete blog posts  
- Add comments to posts  
- Categorize posts  
- Admin panel for managing content  

## How to Run

1. Install Java 11 or higher and Maven.  
2. Set up a MySQL database named `blogdb`.  
3. Configure your database settings in `src/main/resources/application.properties`.  
4. Run the app with:

   ```bash
   ./mvnw spring-boot:run

# Bootcamp Beancamp Sesi 01
Latihan bootcamp sesi 02
1. Buat Spring Boot Project dengan https://start.spring.io/ dengan dependencies:
   - Spring Web
   - Spring Data JPA
   - PostgreSQL Driver
   - DevTool
2. Buat Entity berikut:
   - User
     - Long id
     - String username
     - String password
     - String address
     - String phone
3. Buat RESTful API endpoints sederhana berikut
     - localhost:8000/users        (GET | Get group of existing users)
     - localhost:8000/users        (POST | Save new User)
     - localhost:8000/users/{id}   (PUT | Update existing User)
     - localhost:8000/users/{id}   (GET | Get single User)
     - localhost:8000/users/{id}   (delete | Delete single User)

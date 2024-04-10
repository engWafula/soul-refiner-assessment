**Code review summary  report**

1. Code uses express js with typescript for type safety to write RESTful API endpoints.
2. Code uses Prisma ORM  a very popular ORM that is flexible and can easily be used with Both NoSQL databases like MongoDB and  SQL databases like MYSQL, and Postgres.
3. It uses the Postgres database to store user information.
4. API endpoints are well documented using Swagger UI
5. It also uses Docker one of the popular containerization tools to package the application.
6. The code has reusable  exception handling code  to have different  handle different kinds of exceptions
7. The code also has validation being done on routes so that the request body matches its corresponding  DTO
8. Code also doesn't have unit tests being written though Jest a popular testing library is being configured.
9. Controller, Service, and Route folders are being included having all required CRUD operations 

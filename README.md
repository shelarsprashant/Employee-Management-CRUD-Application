# Employee Management System

## How to Run This Project

### From the IDE

1. *Open the Project*
   - Open the project in an IDE like Intellij Idea for backend. (Employee-Management-CRUD-Application/Backend/ems-backend)

2. *Run the DBScript*
   - Execute the provided DBScript in MySQL to create the database and tables with basic values. 
   - *Note*: Creating the database is necessary since the Hibernate update option is used: 
     properties
     spring.jpa.hibernate.ddl-auto = update
     

3. *Change Hibernate Setting (if needed)*
   - If you prefer not to run the DBScript, you can change the following line in src/main/resources/application.properties:
     properties
     spring.jpa.hibernate.ddl-auto = create-drop
     

4. *Check Database Connection*
   - Verify your database connection settings in src/main/resources/application.properties and modify if necessary.

5. *Run the Application*
   - Navigate to Backend/ems-backend.
   - Select "Run As Java Application" in the IDE.                    //Make sure you have JDK installed//.
   - Confirm that the localhost server has started.

6. *Test the API with Postman*
   - Open Postman or Cosmoscloud client on Google Chrome.
   - Use the following URLs to interact with the API:
     - *Employees*:
       - GET - http://localhost:8080/employees - Gets a list of all employees.
       - GET - http://localhost:8080/employees/{id} - Gets employee with the specified ID.
       - POST - http://localhost:8080/employees - Inserts a new employee.
       - PUT - http://localhost:8080/employees/{id} - Updates employee with the specified ID.
       - DELETE - http://localhost:8080/employees/{id} - Deletes employee with the specified ID.
       - PATCH - http://localhost:8080/employees/{id} - Patches/updates employee with the specified ID.

## Assumptions

- The database and tables are created in MySQL.
  ```json
  {
    "id": 1,
    "firstName": "Prash",
    "lastName": "Shelar",
    "email": "prashantshelar@gmail.com"
  }

7. **Open the Project **
   - Open the project in an IDE like VSCode for frontend. (Employee-Management-CRUD-Application/Frontend/ems-frontend)
   - run the project by using command npm run dev          // Make sure you have NodeJS installed
  


THANK YOU!!
        Thank you for using the Employee Management CRUD Application! We hope this project helps you effectively manage employee. If you have any questions or feedback, feel free to reach out!

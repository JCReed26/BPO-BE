# Backend Operations

This details the different ways to run the backend of the project.
It covers testing, and deployment.

---
## Testing 

Currently, the project can be testing with 'python main.py' in the terminal.
This will be for the start of the project local queries and routing function 
output to the terminal for development purposes. We need to add the database 
and test it to make sure it is working properly. 

### Terminal
    'python main.py'

### API / Flask 
    'docker-compose up --build'

---

## Database

    We need to add the MySQL database to the project. 
    @Marat 
        Can you add this to the database and update the documentation. 
        If you use Workbench, we can add users might be
        easier to use a Postgres we might be allowed to use that. 

    test with postman(API) after terminal output successful
    
    Once the database is added and working, we can start working on 
    each piece. We can create basic data to send through the API
    but I need to learn more about ML and PyTorch before I can 
    know for sure what the actual deliverables will need to be. 

---
## Deployment

    Im not sure I want to use docker for this project 

    The project requires getting data from the database 
    and filtering it to be used properly with the PyTorch model which needs to be trained and deployed to the SageMaker endpoint and S3 bucket.

---
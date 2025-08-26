# vector-db-for-db-objects
Create a vector db for oracle database objects(tables,views).

### **In the 1st example, we'll create a vector db based on a users/schemas views/tables of oracle database.**
 - **Retrieve all the views/tables from a oracle db user.**
 - **Create a documents list by reading those views and associated columns.**
 - **Create a vector DB over the document list using an embedding model.**
 - **Check the results by vector similarity search.**


 ### **In the 2nd example, we'll create a vector db based on a sample file of user questions and sql queries**
 - **Read the example file. Which is a list of user question and sql query**
 - **Create a json file on top of that esample file.**
 - **Create a documents list by reading the json file.**
 - **Create a vector DB over the document list using an embedding model.**
 - **Check the results by vector similarity search.**
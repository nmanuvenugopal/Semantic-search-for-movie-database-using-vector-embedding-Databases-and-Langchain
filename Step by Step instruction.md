1. Create one free account for mongodb. After creating a account, login to it and create a new project I have named it as "GenAI". After creating the new project, its time to create a new deployment. I have leave the default values as such.
   ![image](https://github.com/nmanuvenugopal/Semantic-search-for-movie-database-using-vector-embedding-Databases-and-Langchain/assets/99719105/d0e2de52-499a-4be6-b6d6-3ca049b47914)

2. Once we complete the above steps our dashboard looks like as follows. Mongodb provide an option to add our custom data, they also provide an option to load their own sample data.
  ![image](https://github.com/nmanuvenugopal/Semantic-search-for-movie-database-using-vector-embedding-Databases-and-Langchain/assets/99719105/d7a0c4d8-7916-40fa-8730-5e53ea7b3628)

3. Click on the sample data, then MongoDB will deploy the sample dataset to the deployment that we have created. Once it is completed we can access the sample dataset the mongodb provides. Here we are using the sample "movie"dataset the mongodb provides. Take a look at the screenshot:
   ![image](https://github.com/nmanuvenugopal/Semantic-search-for-movie-database-using-vector-embedding-Databases-and-Langchain/assets/99719105/83dc6443-4306-4329-a1dd-80cd81fb3d12)

4. Once we are able to search through the sample databases, it's time to code. I am using VS Code for writing the code. For accessing the data from Mogodb we need to connect to the database first. Below is the code to connect to the database and display first records.
   ![image](https://github.com/nmanuvenugopal/Semantic-search-for-movie-database-using-vector-embedding-Databases-and-Langchain/assets/99719105/20f54b42-bcd4-4523-9198-8dde88f4a4b4)

6. We need to give MongoDB URL to the above highlighted portion and it can be retived by doing the following step:
  ![image](https://github.com/nmanuvenugopal/Semantic-search-for-movie-database-using-vector-embedding-Databases-and-Langchain/assets/99719105/faf684d7-f5b4-41eb-b89a-3b21905d7676)
  ![image](https://github.com/nmanuvenugopal/Semantic-search-for-movie-database-using-vector-embedding-Databases-and-Langchain/assets/99719105/a894a53c-f42a-4ea8-8933-dbd1206526ae)

  I have striked out my username, it should have you username and passowrd to connect to the database you have created:
  ![image](https://github.com/nmanuvenugopal/Semantic-search-for-movie-database-using-vector-embedding-Databases-and-Langchain/assets/99719105/47cf6c0a-f926-430c-b9eb-6a6c7e24ac70)

7. Once we fill in all the details try to run our python code to see whether we are able to establish the connection.
   





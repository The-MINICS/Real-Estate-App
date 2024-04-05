# MINICS-HOTEL "EXPLORE & BOOKING"

## Environment Setup
_This project utilizes environment variables to store configuration details. To run the application, follow these steps:_
1. Create a `.env` file:
   
      ```
        cp .env.example .env  
      ```
  * Copy the provided **.env.example** file to **.env**:
  * This **.env** file will hold your specific configuration values.
2. Update the `.env` file:
     * Open the **.env** file in a text editor.
     * Replace the placeholder values within angle brackets (<...>) with your actual credentials for the following variable:
        * MONGO: This variable stores your MongoDB database connection string. Refer to your database provider's documentation for constructing the correct connection string format.
Task requirements: 
    Version control/tracking: Git. 
        - The initial commit should be as early as possible in the development, so that we can assess the workflow.
    Build system: Gradle.
    Database: PostgreSQL. 
        Please include all necessary sql scripts in one file so that we can pass it to the postgresql, create the database structure and test locally. The database name is '<your_first_name>_task', e.g. 'plamen_task'.
    DB ORM: To persist data in the postgre server use Ebean framework. 
    Database credentials must not be hard coded in the source code. Use external config file or env variables or any other appropriate method.
    GUI: WEB based GUI using JavaScript/Angular

Description:
    Write a phone book application that stores its information in PostgreSQL database. The application must allow the user to:
        - browse phone book contacts (show a table with all entries with possibility for filtering/searching)
        - search contacts
        - manage phone book contacts. This includes:
            * create a new contact
            * edit an existing contact
            * delete an existing contact
       
    GUI structure is entirely your choice. 
    Advantage: Write appropriate unit tests.

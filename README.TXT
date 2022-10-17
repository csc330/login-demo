Instructions to run the application

STEP 0: 
   This assumes that you have a database named population already 
   created on your SQL instance. If you don't already have it, create it.
   (use either the GCP web interface or MySQLWorkbench)

STEP 1:
   Modify .flaskenv and include your SQL instance IP address, username and 
   root password.

STEP 2:
   In the project folder, type the following: 
   sudo pip3 install -r requirements.txt

   This ensures that all the required Python modules are installed.

STEP 3:
   Run the application (flask run)

STEP 4: Login credentials for application:

  Admin username: admin   password: csc330
  Regular user:   user    password: csc330
  
Regular user can do everything except delete an entry.  

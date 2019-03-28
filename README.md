# Lab 09 - Recursion running on GCP

## Set up
1. Make sure when you print your working directory, you are in your lab08 folder.
   If not, naviagate to your lab08 directory
   
   `cd CS2334_SP19/lab09`
   
2. Clone this repo. Note: make sure to include the dot in the command below.
   
   `git clone https://github.com/MomoSho/lab09.git .`
   
3. Extract the project files into a created folder named webapp
   
   `unzip webapp.zip -d webapp`

4. Adjust the permissions on the lab09 folder. Note: if you get Permission denied issues at any point during this assignment, make sure this command completed successfully.
   
   `chmod -R 755 .`

## Coding
5. Take a look at a few of the files. recursion.jsp is the ONLY file you will need to modify.
   
   `cat webapp/recursion.jsp`
   
   `cat webapp/index.jsp`
   
   `cat webapp/login.jsp`
   
   `cat webapp/appengine-web.xml`
   
   `cat webapp/web.xml`

6. Before you make any modifications to any files, link this folder to your own private repo.
   
   `git remote rm origin`
   
   `git remote add origin new_repo_url`
   
   `git remote -v`

7. You can edit files using the terminal text editer nano. You can only use your keyboard to interact with the editer.
   
   `nano webapp/recursion.jsp`
   
   Use CTRL+O and then ENTER to save changes.
   
   Use CTRL+X to exit the editer.

## Testing


## Final deployment

   `gcloud app deploy webapp/WEB-INF/appengine-web.xml`


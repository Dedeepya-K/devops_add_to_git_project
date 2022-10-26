# devops_add_to_git_project
this project is to demonstrate addition of file from file system to git 

### prerequisites: 

> Create a folder in your file system and add a  sample html and python files in it.(any files caan be there for now we added these)

> create a basic repository inside your github and copy the url of that repository, we will use it later.


now inside your folder, open git bash and follow the following commands one after the other and you can easily add the files from your folder to git:

1. git init
2. git status
   (your files in red will be seen)
3. git add .
   (adds all of your files from the folder choosen)
4. git status 
   (your files will be seen in green this suggests that all your files are successfully added.)
5. git remote add origin <git repository url created in your github as suggested in prerequisites>
6. git commit -m "Initial Commit"
7. git push -u origin master 
  
  
You can now go to browser and check 

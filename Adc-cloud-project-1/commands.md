# COMMANDS FOR RUNNING AND DEPLOYMENT
## GCLOUD
### Check gcloud version:
    gcloud -v
### Login to gcloud:
    gcloud auth login
### Initialize gcloud:
    gcloud init

## GIT
### Check Git version:
    git -v 
### Git help:
    git -h 
### Clone a repository:
    git clone [link] 
### Check repository status:
    git status 
### Add all files to the repository:
    git add . 
### Add a specific file to the repository:
    git add [file]
### Remove a file from the repository:
    git rm [file]
### Remove a file from the repository and the local directory:
    git rm -f [file]
### Commit the files to the repository:
    git commit -m "mensagem" 
### Push the files to the repository (local to remote):
    git push 
### Pull the files from the repository (remote to local):
    git pull 

## MAVEN
### Check Maven version:
    mvn -version 
### Clean the project:
    mvn clean 
### Run project tests (unit tests):
    mvn test 
### Verifies the project:
    mvn verify 
### Generate the project site:
    mvn site 
### Compile the project:
    mvn compile
### Package the project:
    mvn package 
### Install the project:
    mvn install 
### Deploy the project (with the App Engine plugin):
    mvn appengine:deploy 
### Run the project (with the App Engine plugin):
    mvn appengine:run

### Command used to run the project locally:
### Package the project and runs it locally:
    mvn package appengine:run 

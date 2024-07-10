Install the necessary software on the machines using a configuration management tool




Git workflow has to be implemented
CodeBuild should automatically be triggered once a commit is made to master branch or develop branch.
If a commit is made to master branch, test and push to prod
If a commit is made to develop branch, just test the product, do not push to prod
The code should be containerized with the help of a Dockerfile. 
The Dockerfile should be built every time there is a push to GitHub. Use the following pre-built container for your application: hshar/webapp 
The code should reside in '/var/www/html'
The above tasks should be defined in a Jenkins Pipeline with the following jobs: Job1:build  Job2:test   Job3:prod

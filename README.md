# DevOps Final Project
## GIT
In this section, we will work with Git version control system to store and manage the code of our web application.

- Find or create a simple web application using JSP. This step involves either finding an existing JSP web application or creating a new one.
- Store the code in a new project on GitHub. After creating or finding the web application, we will store the code in a new project on GitHub for version control and collaboration purposes.
## Jenkins
In this section, we will use Jenkins, an open-source automation server, to automate the deployment process of our web application.

- Create a folder on your Ubuntu server for Jenkins. In this step, we will create a folder on our Ubuntu server where we will store Jenkins and its related files.
- Pull the latest version of the Jenkins Docker image. We will use Docker to run Jenkins, so we will pull the latest version of the Jenkins Docker image.
- Run and start the Jenkins container with volume mapping. After pulling the Jenkins Docker image, we will run and start the Jenkins container with volume mapping to store the Jenkins data outside the container.
- Perform the initial configuration to make sure Jenkins is available from outside. This step involves configuring Jenkins so that it can be accessed from outside the container.
- Deploy the simple web application into production by creating a Jenkins job that will take the JSP file from GitHub and place it in the new folder. In this step, we will create a Jenkins job that will automate the deployment process of our web application. The job will take the JSP file from GitHub and place it in the folder on our Ubuntu server.
## Tomcat
In this section, we will use Tomcat, an open-source Java Servlet Container, to run our JSP web application.

- Pull the latest version of the Tomcat Docker image. We will use Docker to run Tomcat, so we will pull the latest version of the Tomcat Docker image.
- Run and start the Tomcat container with volume mapping. After pulling the Tomcat Docker image, we will run and start the Tomcat container with volume mapping to store the Tomcat data outside the container.
- Verify that the Tomcat server is available. This step involves checking if the Tomcat server is running and accessible.
## Monitor
In this section, we will set up monitoring for our web application to ensure its availability and functionality.

- Create an availability monitor for the Tomcat application. In this step, we will create a monitor that checks the availability of the Tomcat application.
- Create a separate monitor Jenkins job that will monitor the website every minute. In this step, we will create another monitor Jenkins job that will monitor the website every minute to ensure its functionality.
- If the monitor Jenkins job fails, trigger the build job. If the monitor Jenkins job fails, we will trigger the build job to ensure that the web application is functioning as expected.
## Jenkins + Tomcat
In this section, we will integrate Jenkins and Tomcat to automate the deployment process of our web application.

- Make changes in Git. Whenever changes are made to the web application code, they will be committed and pushed to the Git repository.
- Ensure that the application is automatically updated by Jenkins. Using the Jenkins job created earlier, we will make sure that the changes made in Git are automatically deployed to the production environment by Jenkins.

# Deploy-the-application-by-using-Jenkins
First of all create a  4 ec2 insatance on aws and connect to every instances.
EC2 ;

                                Jenkins
                                Sonarqube
                                Nexus     
                                Tomcat

  ![Screenshot 2024-11-11 185703](https://github.com/user-attachments/assets/ef4fb877-3e71-4a70-bcf6-59bad934c729)

Connect to the Jenkins server and install the java and Jenkins.

And now go to Log into the Jenkins dashboard and install the sonarqube scanner and docker to container plugin.

Install availabe plugins like Artfactrs and deploy to container,sonarqube.
![Screenshot 2024-11-12 093135](https://github.com/user-attachments/assets/8a4dd253-d050-4a58-b80f-e6843650bac1)

Install the sonarqube on sonarqube server.
![Screenshot 2024-11-12 093251](https://github.com/user-attachments/assets/46444332-c600-43de-b7f0-f1dac731dec2)

Install the tomcat on tomcat server.

Jenkins pipeline success
![Screenshot 2024-11-12 084809](https://github.com/user-attachments/assets/89f05d39-fa8a-4204-a3bc-41b7798273f5)

Code analysis by sonarqube

![Screenshot 2024-11-11 191913](https://github.com/user-attachments/assets/b085bbcb-5d3c-4bfc-a2d3-dcfc96fb63af)


finally Access the application on tomcat
![Screenshot 2024-11-12 092215](https://github.com/user-attachments/assets/86e2cd9d-e3fe-4847-a415-674b90388156)

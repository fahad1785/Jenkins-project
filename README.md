# Jenkins-project
Today I installed Jenkins on AWS EC2 instance and setup a Freestyle project for CI/CD. 
Installed openjdk before installing Jenkins 
Then Installed Jenkins 
Gave UFW permissions on port 8080
Enabled the UFW on port 8080
Login to Jenkins on localhost http://16.170.243.249:8080/
Logged in with the Initial password located in jenkins server /var/lib/jenkins/secrets/initialAdminPassword
Setup Jenkins and installed required plugins 
Made new Freestyle project Jenkins-project 
Generated Github Access token and added to project details 
Added Build Triggers 
GitHub hook trigger for GITScm polling    and
Poll SCM
Then added the Github Webhook of the repository and added the Jenkins url in the Webhook url.

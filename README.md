# GitOps Project - README
In this project, I implemented a GitOps workflow to manage and deploy both infrastructure and applications using Git.

# What I Did:

-Set up two Git repositories: one for Terraform code to manage AWS infrastructure and another for the application code.

-Created CI/CD pipelines using GitHub Actions to automate the deployment process.
   
  - -The infrastructure pipeline manages AWS resources using Terraform.
   
  - -The application pipeline builds, tests, and deploys the application using Docker, Maven, and Helm.

-Ensured that all changes to the infrastructure and application are tracked and versioned in Git, following GitOps principles.

This setup streamlines deployments and enhances consistency, traceability, and automation.
# Prerequisites
#####
- JDK 11
- Maven 3
- MySQL 8 

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
# Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql

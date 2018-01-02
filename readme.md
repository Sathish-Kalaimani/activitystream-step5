## Seed code - Boilerplate for step 5 - Activity Stream Assignment

### Assignment Step Description

In this case study Activity Stream Step 5, we will implement Java Persistence API (JPA) for accessing, persisting, and managing data between Java objects/classes and a relational database. 
In this step, we will create this application in two parts one for REST and other for Backend.

- REST will have all the controller classes been implemented
- Backend will have all the configuration classes, model classes, repository classes, service classes and logging aspect been implemented.

### Steps to be followed:

    Step 1: Clone the boilerplate in a specific folder on your local machine and import the same in your eclipse STS.
    Step 2: Go thru the readme.md file and implement the code for Backend and run the test cases
    Step 3: Go thru the readme.md file and implement the code for REST and run the test cases

### Project structure

The folders and files you see in this repositories, is how it is expected to be in projects, which are submitted for automated evaluation by Hobbes

    Project
	|
	├── step-5-backend-boilerplate              // This project holds all the backend configuration, services, models, loggers
	├── step5-rest-boilerplate                  // This project holds all the REST Controllers
	├── .classpath			                    // This file is generated automatically while creating the project in eclipse
	├── .gitignore			                    // This file contains a list of file name that are supposed to be ignored by git 
	├── .hobbes   			                    // Hobbes specific config options, such as type of evaluation schema, type of tech stack etc., Have saved a default values for convenience
	├── .project			                    // This is automatically generated by eclipse, if this file is removed your eclipse will not recognize this as your eclipse project. 
	├── pom.xml 			                    // This is the parent POM, which holds Backend project and REST project dependencies.
	└── PROBLEM.md  		                    // This files describes the problem of the assignment/project, you can provide as much as information and clarification you want about the project in this file

> PS: All lint rule files are by default copied during the evaluation process, however if need to be customizing, you should copy from this repo and modify in your project repo


#### To use this as a boilerplate for your new project, you can follow these steps

1. Clone the base boilerplate in the folder **assignment-solution-step5** of your local machine
     
    `git clone https://gitlab-dev.stackroute.in/activity-stream-java/activitystream-step5-boilerplate.git assignment-solution-step5`

2. Navigate to assignment-solution-step5 folder

    `cd assignment-solution-step5`

3. Remove its remote or original reference

     `git remote rm origin`

4. Create a new repo in gitlab named `assignment-solution-step5` as private repo

5. Add your new repository reference as remote

     `git remote add origin https://gitlab-dev.stackroute.in/{{yourusername}}/assignment-solution-step5`

     **Note: {{yourusername}} should be replaced by your username from gitlab**

5. Check the status of your repo 
     
     `git status`

6. Use the following command to update the index using the current content found in the working tree, to prepare the content staged for the next commit.

     `git add .`
 
7. Commit and Push the project to git

     `git commit -a -m "Initial commit | or place your comments according to your need"`

     `git push -u origin master`

8. Check on the git repo online, if the files have been pushed

### Important instructions for Participants
> - We expect you to write the assignment on your own by following through the guidelines, learning plan, and the practice exercises
> - The code must not be plagirized, the mentors will randomly pick the submissions and may ask you to explain the solution
> - The code must be properly indented, code structure maintained as per the boilerplate and properly commented
> - Follow through the problem statement shared with you

### Further Instructions on Release

*** Release 0.1.0 ***

- Right click on the Assignment select Run As -> run on server to run your Assignment.
- Right click on the Assignment select Run As -> JUnit Test to run your Assignment.
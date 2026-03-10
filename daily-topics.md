## Day1 : 04/02/2026
* Devops Introduction
* Projct Flow

## Day2 : 05/02/2026
* Account Creations on cloud 
* Roles and responsibilities 

## Day3 : 06/02/2026
* Linux 

## Day4 : 09/02/2026
* Linux

## Day5 : 10/02/2026
* Comparision of files
* Grep , arguments 
* compression, archiveel.....unarchive 
* userid , 
* sudo 
* password authentticaion
* user login (username and passwd )

## Day6 : 11/02/2026
* User access
* File Permissions 
* Key Management 
* Connecting to linux machines using key , rather than passwords 

## Day7 : 12/02/2026
* git init 
* git add .
* git add filename
* git status
* git commit 
* git log 
* git log --oneline
* git config(both global and local)
* Workflow 
* Local repo 

## Day8 : 13/02/2026
* Git 
* add, commit , local repo

## Day9 : 16/02/2026
* Github account creation 
* remote repo creation 
* PAT 

## Day10 : 17/02/2026
* PAT 
* Keys in both linux and windows
* Multi Account keys configuration using config file 

## Day10 : 19/02/2026
* git branches 
* tags
* Pull request

## Day11 : 20/02/2026
* Merge conflicts 
* Org account 
* Colloborator  for a repo
* Reviewers and merge through a pr
* default branch 
* repo, setting

## Day12 : 25/02/2026
* what are build tools 
* Various build tools 
* maven intro
* installing java maven on windows and linux machines

## Day13 : 26/02/2026
* Mvn build phases 
* type of repos
* Artifacts creation

## Day13 : 27/02/2026
* Code analysis
* Code quality
* Sonarqube 
* Installing and accesing sonarqube 
* Configuring/opening port 9000 on gcp and aws cloud
## Day14 : 28/02/2026
* 
## Day15 : 02/03/2026
* Quality Profile 
* Quality Gates
* SonarQube rules and their importance in code analysis
* Implemented sonarqube on java based maven project and analyzed code quality in SonarQube dashboard using mvn sonar:sonar command.
## Day16 : 03/03/2026
* Sonarqube analysis using Python and maven projects
* SonarQube Scanner installation and configuration
* Sonarqube prperties file configuration
* Executing sonar scans using sonar-scanner cli and analyzing results in SonarQube dashboard
* Task: 
    * Implement the same format for java based maven project and analyze the code quality in SonarQube dashboard using sonar-scanner cli
## Day17 : 04/03/2026
* Understood what ci/cd is and its importance in software development
* Installed Jenkins on ubuntu 
* Configured jenkins 
* Created a simple job in jenkins > ran the job > checked the console output for build status
## Day18 : 05/03/2026
* Explored manage jenkins options 
* Created multiple jobs with build steps 
* Observerd diff b/w git clone and scm 
* Created a job for java using scm
## Day19 : 06/03/2026
* Implemented a free style jenkins job for a java based maven project using git scm
* Configured differnet versions of s/w packages in jenkins using global tool configuration
* Created a credential in jenkins for github access and used it in git scm configuration for the job
* Archived the build artifacts in jenkins and observed the archived artifacts in the build history
## Day20 : 10/03/2026
* Configure jenkins-master slave setup 
* Task:
    * Create a jenkin-master-slave setup and have a label called `app-slave`
    * On slave vm configure, java, mvn, node , docker as well .
    * Create a job called `java-app-1` configure to have `mvn package` and make sure it will run on the slave whos label is `app-slave`
    * Create a job called `docker-hello-world` and configure to have this command run `docker run hello-world` on the slave whos label is `app-slave`

## Good to know
* undo operations 

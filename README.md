https://github.com/juaneortiz1/taller01-ARSW.git
# Maven WebApp

This project is a simple web application built using Maven.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You need to have Java installed (7 or 8). Verify your Java installation with:

```sh
java -version
```
![image](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/79bc5001-7759-4c98-8774-8957ce897361)
Follow the instructions at Maven Installation Guide to install Maven. To verify Maven installation, run:
```sh
mvn -version
```
![image](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/29695be0-b817-4c3f-afcd-493a42ffe908)
### Installing
A step-by-step guide to set up the development environment:

Open a shell and navigate to the directory where you want to store your projects.
Create a new Maven project using the quickstart archetype:
![image](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/57eb9165-8dfe-4b1d-83f0-1a819a1d6e9c)
### Project Structure
Your project directory will look like this:
![image](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/1763d4f0-f47e-4967-8ea9-e32687c1b9d9)
### Sample Code
We make a little test with our App.java class
![image](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/cc631bc8-ff45-4c4e-a925-fab452cd771e)
pom.xml
![image](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/dca5162f-fde4-40ad-94f6-8a57e95615dc)
As we package our project with the next command
```sh
mvn package
```
![image](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/b682b061-5aec-4bfd-8232-0811d02aaca2)
Once our .jar is created as we see, and we can execute the next command to check our App
```sh
java -cp target/mi-primera-app-1.0-SNAPSHOT.jar edu.escuelaing.arsw.ASE.app.App
```
### Generating Javadoc
We update our pom.xml so we can add javadoc plugin 
![image](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/0b2cf00f-e1fc-4d92-8ddb-ebb5b0a79051)
After this we use the next commands to generate and package Javadoc:
![image](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/938d6204-6783-4f91-b624-06b8747240a9)
![image](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/fdaed66f-7086-4ee8-9e3e-d9f5e4624df1)
```sh
java -cp target/mi-primera-app-1.0-SNAPSHOT.jar edu.escuelaing.arsw.ASE.app.App
```
![image](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/56d1694b-8d10-49ce-a8fa-0eff54cd5223)
### Creating a Git Repository
In the project directory, run:
```sh
git init
```
### Adding Files to Version Control
Use the add command:
```sh
git add pom.xml
git status
```
### Working with Remote Repositories
To add a new remote repository, run:
```sh
git remote add origin https://github.com/dnielben/miprimerrep.git
```
We push to our local repository to the remote repository with:
```sh
git push -u origin master
```
we check the status of our repository and we get
![image](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/f8715fb1-dac9-4219-aae5-e81c7070769f)
### Adding More Files
It's recommended to create a README, LICENSE, and .gitignore file:
```sh
echo 'Mi primer proyecto' > README.txt
echo 'TODO: Copiar el texto de la licencia http://www.gnu.org/licenses/gpl.html' > LICENSE.txt
echo '# TODO: Copiar los contenidos de https://github.com/github/gitignore/blob/master/Java.gitignore' > .gitignore
```
![image](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/005f30b5-3440-413e-bb08-fa8e155a1dc7)
![image](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/615f4511-a11b-412d-bf51-1bc3c58c6fb3)
### Ignoring Files
Modify your .gitignore file to ignore the target, idea directory and also some files associated with junk:
![image](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/a574821e-0c3f-42b0-aa48-97708a37068e)

## Build with

* [Maven](https://maven.apache.org/) - Dependency manager
* [Java](https://www.oracle.com/java/technologies/) - Programming Language

## Authors

* Juan Esteban Ortiz


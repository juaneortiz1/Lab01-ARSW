https://github.com/juaneortiz1/taller01-ARSW.git
---

# Maven WebApp

This project is a simple web application that I built using Maven.

## Getting Started

Here’s how I set up the project to run on my local machine for development and testing purposes. You’ll also find notes on deploying the project on a live system.

### Prerequisites

First, I made sure I had Java installed (version 7 or 8). I verified my Java installation with:

```sh
java -version
```
![Java version](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/79bc5001-7759-4c98-8774-8957ce897361)

Next, I followed the instructions at the Maven Installation Guide to install Maven. I verified the Maven installation by running:

```sh
mvn -version
```
![Maven version](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/29695be0-b817-4c3f-afcd-493a42ffe908)

### Installing

Here’s a step-by-step guide on how I set up the development environment:

1. I opened a shell and navigated to the directory where I wanted to store my projects.
2. I created a new Maven project using the quickstart archetype:
![Creating a new Maven project](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/57eb9165-8dfe-4b1d-83f0-1a819a1d6e9c)

### Project Structure

My project directory looked like this:
![Project structure](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/1763d4f0-f47e-4967-8ea9-e32687c1b9d9)

### Sample Code

I wrote a small test with the `App.java` class:
![App.java](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/cc631bc8-ff45-4c4e-a925-fab452cd771e)

Here’s the `pom.xml` file:
![pom.xml](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/dca5162f-fde4-40ad-94f6-8a57e95615dc)

To package the project, I used the following command:
```sh
mvn package
```
![Packaging the project](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/b682b061-5aec-4bfd-8232-0811d02aaca2)

Once the `.jar` file was created, I ran the following command to check the application:
```sh
java -cp target/mi-primera-app-1.0-SNAPSHOT.jar edu.escuelaing.arsw.ASE.app.App
```

### Generating Javadoc

I updated the `pom.xml` to include the Javadoc plugin:
![Updating pom.xml](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/0b2cf00f-e1fc-4d92-8ddb-ebb5b0a79051)

Then, I used these commands to generate and package the Javadoc:
![Generating Javadoc](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/938d6204-6783-4f91-b624-06b8747240a9)
![Packaging Javadoc](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/fdaed66f-7086-4ee8-9e3e-d9f5e4624df1)
```sh
java -cp target/mi-primera-app-1.0-SNAPSHOT.jar edu.escuelaing.arsw.ASE.app.App
```
![Running the App](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/56d1694b-8d10-49ce-a8fa-0eff54cd5223)

### Creating a Git Repository

In the project directory, I ran:
```sh
git init
```

### Adding Files to Version Control

I added files using:
```sh
git add pom.xml
git status
```

### Working with Remote Repositories

To add a new remote repository, I ran:
```sh
git remote add origin https://github.com/dnielben/miprimerrep.git
```

I pushed the local repository to the remote repository with:
```sh
git push -u origin master
```
Here’s the status of the repository:
![Repository status](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/f8715fb1-dac9-4219-aae5-e81c7070769f)

### Adding More Files

I created a README, LICENSE, and .gitignore file:
```sh
echo 'Mi primer proyecto' > README.txt
echo 'TODO: Copiar el texto de la licencia http://www.gnu.org/licenses/gpl.html' > LICENSE.txt
echo '# TODO: Copiar los contenidos de https://github.com/github/gitignore/blob/master/Java.gitignore' > .gitignore
```
![Additional files](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/005f30b5-3440-413e-bb08-fa8e155a1dc7)
![Creating files](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/615f4511-a11b-412d-bf51-1bc3c58c6fb3)

### Ignoring Files

I modified the `.gitignore` file to ignore the `target`, `.idea` directory, and some files associated with junk:
![Modifying .gitignore](https://github.com/juaneortiz1/taller01-ARSW/assets/97971732/a574821e-0c3f-42b0-aa48-97708a37068e)

## Built With

* [Maven](https://maven.apache.org/) - Dependency Manager
* [Java](https://www.oracle.com/java/technologies/) - Programming Language

## Author

* Juan Esteban Ortiz

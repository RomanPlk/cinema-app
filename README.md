![](https://i.pinimg.com/564x/fc/eb/df/fcebdf9e34ad5d5f1d8f728f781a00ac.jpg)
# Cinema-app
## Project description:
This web application is a simple representation of cinema's ticket reservation system that requires registration or authentication process for access and includes basic CRUD operations
## Features:
➩ registration;

➩ log in;

➩  add / find by email:
* a user

➩  add / get by id / get all:
* a movie / movies
* a cinema hall / cinema halls

➩  add / get by id / find available:
* a movie session

➩  add a session / find by user / register & clear:
* a shopping cart

➩  complete / get a history:
* an order

## Structure:
Project uses an N-tier architecture with following layers of functionality:

* DAO: operates with data in DB;
* Service: contains all business logic of the application.

## Application technologies:
* JDK **11**
* Apache Maven **3.8.5**
* MySQL **8.0.30**
* Hibernate **5.4.21.Final**
* HQL

## Usage:
Project assumes that you've already installed:

* JDK (*version 11 or higher*)
* Apache Maven
* MySQL
1. Clone this project to your IDE and check errors in *pom.xml* file (if needed):

   `git clone https://github.com/RomanPlk/cinema-app.git`
2. ... (IN PROGRESS)

## UML diagram for DB:
![](https://scontent.fifo4-1.fna.fbcdn.net/v/t1.15752-9/308032324_608916237603786_4208919991278081530_n.png?_nc_cat=110&ccb=1-7&_nc_sid=ae9488&_nc_ohc=UctnRGHBnMcAX_FG36H&_nc_ht=scontent.fifo4-1.fna&oh=03_AVILyRIFgVNtg0an8RmgvkzN5E7SxymbUHJL_ToQsiZZ4A&oe=634EA3FF)


# Assignment-1-Java-Rest-API

## What is Spring boot?

Accoring to me Spring Boot is a loosely couple famework build on the top of Spring framework. Currently spring boot is one of the most poplar framework used to make web application.The thing that makes spring boot different from others is fast way to setup, config and run web application. It is a injection based framework and **Rapid Application Devlopment** is a ket feature of it. 

### Framework Used:-

**Springboot: 2.7** 

### Database Used:-

**MongoDB: 6.0**

### Dependency Managers Used:-

**Maven: 3.8.6**

### Java Version Used:-

**Java: 17.0.5**

## Components of this project:

**Entity:**

-Server

Here, in this entity I have used values like Id, Name, Language and Framework.

**Repository:**

-ServerRepository

Here, for repository I have create the ServerRepository interface which extends to the 
MongoRepository class. here, we are passing the server Class and data type as String.
Services:

**Service:**

-ServerService

Here, we have seted the different methods for all the CURD operation like delete, update, add and find which we are going to declare in the controller.

**Controller:**

-ServerController

Here, we have created the class server
controller which is responsible for handling all the client requests and navigation. Here, we declare the different urls to conduct different CURD operations and navigation.

## Screenshorts of different CURD operation in postman:

### GET ALL DATA

![](https://i.imgur.com/tUChi2l.png)

### ADD

![](https://i.imgur.com/7dtZVhm.png)

### UPDATE

![](https://i.imgur.com/z428uJB.png)

### DELETE

![](https://i.imgur.com/Eiw9WF2.png)

### FIND

![](https://i.imgur.com/KO94vMQ.png)

### GetById

![](https://i.imgur.com/ZD7HtbJ.png)


                                      





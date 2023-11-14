<!--
title: 'Java Maven project'
description: 'This example demonstrates how to setup a Java web app using Maevn allowing you to create and login user. MySql is used to store the data.'

-->
# Java Maven Web Application

This example demonstrates how to setup a Java Web Application using Maven allowing you to create and login user. MySql is used to store the data. This is just an example and of course you could use any data storage as a backend.

## Structure

This web app is simple user registration and Login App. Code base contain servives for User Registration and User login. There is index page which shows user registration option and login page whcih shows login option. After successfull login welcome page is displayed.

## Database
Change MySql credentials in DbConnection.Java file as shown below
![image](https://github.com/Ashvini379/Devops/assets/44570192/963bb27c-a85d-4a5f-aaec-5e78da3e9e48)


## Setup

```bash
mvn clean install
mvn clean package
mvn tomcat:run
```

## Usage

You can create user and login using that user with the following commands:
Registration Page
![image](https://github.com/Ashvini379/Devops/assets/44570192/facd5edd-6b6e-4f88-9532-b6e3bffe4b2c)

Login page
![image](https://github.com/Ashvini379/Devops/assets/44570192/98244791-4fd2-4530-8201-2dc51d5dff71)


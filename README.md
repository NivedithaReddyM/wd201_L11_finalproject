# Hello Guys ,This is Niveditha


# Online Voting System
** ABOUT THE PROJECT **
This is a Node.js, Postgresql, Bootstrap, and Express.js-based digital voting platform that allows election officials to sign up and create multiple elections. You can create ballots with multiple questions, add options to the questions, add voters for a specific election, reset passwords for both election administrators and voters, create a custom public URL for the election, and so on.


[![MIT License](https://img.shields.io/badge/Platform-Deployed-green.svg)](https://choosealicense.com/licenses/mit/)

Deployed App link: 

https://wd201-l11-finalproject.onrender.com

## Demo link


## Features


- Fully Responsive platform
- Uses CSRF tokens to prevent attacks such as sql-injection
- Admin will be able to signup,Login
- Admin can create the elections
- Admin can create a ballot of questions in an election
- Admin can add options and delete options for a question in the election
- Admin can delete the elections,questions,voters
- Admin can register voters
- Admin can launch election
- Admin has the privilege to launch and end the election
- We cannot delete election after ending election
- We cannot edit questions after launching election
- We cannot edit questions,voters,options etc... after ending an election




## Technologies used to build the website

**Client:** EJS(Embedded Javascript Templates),CSS,Bootstrap 

**Server:** Node.js, Express.js

**Database:** Postgres


## Installation

Don't forget to create the databse with corresponding name as mentioned in `config.json`



Go to the project directory

```bash
  cd wd201_L11_finalproject
```

Install dependencies

```bash
  npm install
```
or
```bash
  npm i
```
start server to run the website in localhost

```bash
  npm start
```
## To create database

To create database,run the following command

```bash
npx sequelize-cli db:create
```
## To migrate database

To migrate database,run the following command

```bash
npx sequelize-cli db:migrate
```

## Running Tests

To run tests,run the following command

```bash
  npm test
```
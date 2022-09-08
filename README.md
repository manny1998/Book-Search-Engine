# Book-Search-Engine
The GITHUB URL: https://github.com/manny1998/Book-Search-Engine
<br>
Heroku link (Is currently not active): https://shielded-river-79796.herokuapp.com/ 
# Description
Creating a MERN(MongoDB, Express, React, Node) book search engine, this is an application that allows users to save books they like to their own profile.
## User Story

```md
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
```


## Acceptance Criteria

```md
GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the signup button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button  
```
# Table of Contents 
* [Technologies Used](#Technologies-Used)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Tests](#tests)
* [Questions](#questions)

# Technologies used
The technologies used include MongoDB, Express.js, ReactJS & Node.js. The dependencies used include: 
* apollo-server-express
* bcrypt
* graphql 
* jsonwebtoken
# Installation
GIT clone the repository ('git@github.com:manny1998/Book-Search-Engine.git') to VS code and then install all the dependencies using 'npm i'. 
# Usage
In order to use this app, type 'npm run develop' in the VS code terminal after the dependecies have been installed. Then visit 'localhost:3000' to use the the application. When you are using the application the user has to signup and create and account (if they have not already created one) in order to use the 'save book function'. 

Sign up page
<img src="./Assets/sign up.jpg">

Search results
<img src="./Assets/search results.jpg">

Saving book
<img src="./Assets/saved.jpg">

View saved books
<img src="./Assets/view saved books.jpg">

# License
This project is licensed under the MIT license. 
![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
# Contributing
​Contributors: Manny
# Tests
The following is needed to run the test: 
# Questions
If you have any questions about the repo, open an issue or contact manny1998 directly at : manny@hotmail.com.

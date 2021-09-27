# Book Search Engine

## Description:
Taking a starter code with a fully functioning Google Books API search engine built with a RESTful API, and refactor it to be a GraphQL API built with Apollo Server. The app was built using the MERN stack with a React front end, MongoDB database, and Node.js/Express.js server and API. It's already set up to allow users to save book searches to the back end.


  ### Table of Contents:

   - [Installation](#installation)
   - [Acceptance Criteria](#acceptance-criteria)
   - [Final Results](#final-results)
   - [Tests](#testing)
   - [Questions](#additional-info)

## Installation:
  You’ll need to have Node >= 14.0.0 and npm >= 5.6 on your machine.
  In order to use this application you will need to first run an `npm install` dependencies listed below in [Tests](#testing)

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
## Final Results:

![Responsive Viewport](https://media.giphy.com/media/Dqe3JQpEJX7KvCQ4w0/giphy.gif?cid=790b7611b6b370f5ef20057b4719571f33e1b55f211044a0&rid=giphy.gif&ct=g)
![Responsive Viewport](https://media.giphy.com/media/7zunXrCOxabnKcxdTU/giphy.gif?cid=790b76112c45cdb8df2d83227c533e70b47b3f4ce0aef357&rid=giphy.gif&ct=g)

* [Deploy Link](https://dry-forest-89220.herokuapp.com/)

## Testing:
- REACT  -  React is a JavaScript library for building modern applications. React is used for handling the view layer and can be used for development of both web and mobile applications.
- react-router-dom- DOM bindings for React Router.
- GraphQL - The JavaScript reference implementation for GraphQL, a query language for APIs created by Facebook.
- Apollo Serve - A TypeScript GraphQL Server for Express, Koa, Hapi, Lambda, and more.
- Apollo Client - Apollo Client is a fully-featured caching GraphQL client with integrations for React, Angular, and more. It allows you to easily build UI components that fetch data via GraphQL.
- Bootstrap - Sleek, intuitive, and powerful front-end framework for faster and easier web development.
- Concurrently - Run multiple commands concurrently. Like npm run watch-js & npm run watch-less but better. 
- jwt-decode - is a small browser library that helps decoding JWTs token which are Base64Url encoded. 
- Javascript - Used to base functionality of functions and prompts within the application.
- GitHub - Hosts repository that can be deployed to GitHub Pages. 


## Additional Info:
:octocat: [Ana Abad](https://github.com/abanae)
- Email: https://github.com/abanae 
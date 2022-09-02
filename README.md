# Books Api Search Engine

## Table of Content

- [Description](#description)
- [User Story](#user-story)
- [Deployment](#deployment)
- [User Story](#User-Story)
- [Node Packages](#node-packages)
- [Questions](#questions)

## Description

Full stack Google Books API search engine using GraphQL API built with Apollo Server. This app is created using the MERN stack with a React front end, MongoDB database, and Node.js/Express.js server and API.

## Deployment

Heroku deployment: https://still-ridge-22361.herokuapp.com/

Github : https://github.com/zahrahaji10/books-api-search-engine/tree/dev

## User Story

```md
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
```

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

## Node Packages

### Client Dependencies

    - apollo/client: "^3.6.9",
    - testing-library/jest-dom: "^4.2.4",
    - testing-library/react: "^9.3.2",
    - testing-library/user-event: "^7.1.2",
    - bootstrap: "^4.4.1",
    - graphql: "^16.6.0",
    - jwt-decode": "^2.2.0",
    - react: "^16.13.1",
    - react-bootstrap: "^1.0.1",
    - react-dom: "^16.13.1",
    - react-router-dom: "^6.2.1",
    - react-scripts

## Server Dependencies

    - apollo-server: "^3.10.2",
    - bcrypt: "^4.0.1",
    - express: "^4.17.1",
    - graphql: "^16.6.0",
    - jsonwebtoken: "^8.5.1",
    - mongoose: "^5.9.10"

## Questions

For any questions, feel free to email me on;

Email: zahrahhaji10@gmail.com

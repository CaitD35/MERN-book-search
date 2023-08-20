# MERN-book-search

Modern web development emphasizes user data personalization and evolving with user demands. This project embodies these principles by refactoring a RESTful API-based search engine into a GraphQL-driven model using Apollo Server.

## Table of Contents

* Overview
* Features
* User Stories
* Getting Started
* Contribution
* License


## Overview

This application is a fully-functioning Google Books search engine using the MERN stack:

* MongoDB for data storage.
* Express.js and Node.js for server-side logic.
* React for frontend UI/UX.

The primary goal of this challenge is to replace the current RESTful API approach with GraphQL using Apollo Server.

## Features

* Search for books via the Google Books API.
* Save books to a database.
* View saved books.
* Delete saved books from the database.
* Appollo Server and GraphQL API.
* Deployed to Heroku 

## User Stories

* When the user loads the page, they are preseneted with options to login or signup and search for books with a search field.
* When the user clicks on the `Signup` option, they are prompted to create a username and password.
* When the user clicks on the `Login` option, they are prompted to enter their username and password.
* When the user is logged in, they are presented with the `Search for Books` and `See Your Books` links in the navigation bar.
* When the user clicks on the `Search for Books` link in the navigation bar, they are presented with an input field to search for books and a submit button.
* When the user is not logged in and they click on the `See Your Books` link in the navigation bar, they are prompted to login or signup.
* When the user enters a search term in the input field and clicks the submit button, they are presented with several search results, each featuring a book's title, author, description, image, and a link to that book on the Google Books site.
* When the user clicks on the `Save This Book` button on a book, that book's information is saved to the database.
* When the user clicks on the `See Your Books` link in the navigation bar, they are presented with all of the books they have saved to the database.
* When the user clicks on the `Delete This Book` button on a book, that book is deleted from the database.
* When the user clicks on the `Logout` button in the navigation bar, they are signed out of the site.


## Getting Started

* Clone the repository to your local machine.
* Navigate to the root directory and run `npm install` to install the dependencies.
* Refactor the application the implement Apollo Server and GraphQL API.

## Deployed Application



## Demo

![Demo](.)







## License

This project is licensed under the MIT License 
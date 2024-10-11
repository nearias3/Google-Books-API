# Google-Books-API

This project is licensed under the MIT License.

## Description

This repository contains a book search engine built with the MERN stack (MongoDB, Express.js, React, Node.js) and utilizes the Google Books API. Users can search for books, save their favorite searches, and view their saved books. The backend was refactored using GraphQL with Apollo Server.

In addition, the project meets Progressive Web Application (PWA) standards, allowing users to search for books even while offline using service workers for caching.

## Table of Contents
- Installation
- Usage
- GraphQL
- Service Worker
- License
- Contributing

## Installation

1. Clone the repository using: 
`git clone`

2. Navigate to the root directory and install dependencies: 
`npm install`

3. Install dependencies for the client:
`cd client`
`npm install`

4. Build the client-side assets:
`npm run build`

## Usage

1. Start the server
`npm start`

2. Access the application at:
`http://localhost:3000`

Here is the link to the [deployed application](https://google-books-api-ljjp.onrender.com/)

![Screenshot of Site](/site.png)
![Screenshot of GraphQL](/graphql.png)


## GraphQL

This project replaces RESTful API routes with a GraphQL API. It uses Apollo Server to handle queries and mutations:

- Queries:
    - me: Fetches the logged-in user's profile and saved books.
- Mutations:
    - login: Logs in a user and returns an authentication token.
    - addUser: Registers a new user and returns a token.
    - saveBook: Saves a book to the logged-in user's profile.
    - removeBook: Removes a saved book from the user's profile.

## License

This project is licensed under the MIT License. Please refer to the license in the repository for more details.

## Contributing

Useful information about coding, including tutorials and guides as well as starter code used, were provided by the UT Bootcamp GitLab: [https://git.bootcampcontent.com/University-of-Texas-at-Austin/UTA-VIRT-FSF-PT-05-2024-U-LOLC/].

I frequently referred to Mozilla's developer tool blogs (MDN Web Docs) for help identifying the correct code and syntax: [https://developer.mozilla.org/en].    
  
I utilized helpful tips and tutorials from coding websites such as: [https://www.geeksforgeeks.org/], [https://coding-boot-camp.github.io], and [https://www.stackoverflow.com].
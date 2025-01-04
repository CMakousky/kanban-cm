# Kanban-CM
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

Kanban-CM is a web application where the user can track project issues.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)
- [License](#license)

## Installation

Use your favorite package manager, such as Node Package Manager, to install the required dependancy packages.

## Usage

Login to Kanban-CM and click the on-screen buttons. Follow the link below to see the deployed web app.

[Deployed Kanban-CM](https://kanban-cm.onrender.com)

## Contributing

Contact Christopher Makousky for inquiries about making contributions.

## Tests

Click the buttons on the screen to test the client functions. Use your favorite API development platform, such as Insomnia, to test the server functions.

    GIVEN a Kanban board with a secure login page

        WHEN I load the login page
        THEN I am presented with form inputs for username and password

        WHEN I enter my valid username and password
        THEN I am authenticated using JSON Web Tokens (JWT) and redirected to the main Kanban board page

        WHEN I enter an invalid username or password
        THEN I am presented with an error message indicating that the credentials are incorrect

        WHEN I successfully log in
        THEN a JWT is stored securely in the client's local storage for subsequent authenticated requests

        WHEN I log out
        THEN the JWT is removed from the client's local storage and I am redirected to the login page

        WHEN I try to access the Kanban board page without being authenticated
        THEN I am redirected to the login page
        
        WHEN I remain inactive for a defined period
        THEN my session expires, the JWT is invalidated, and I am redirected to the login page upon my next action


## Questions

https://github.com/CMakousky

christopher.makousky@gmail.com

## License

MIT License
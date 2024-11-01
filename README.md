# 14 Full-Stack React: Kanban Board

## Task

Authentication with JSON Web Tokens (JWTs) is crucial for full-stack applications, as it provides a secure and scalable method for verifying user identities. JWTs are compact, URL-safe tokens that encode a user's authentication data, allowing servers to authenticate requests. Additionally, JWTs can include metadata and be easily verified and decoded, enhancing security while enabling seamless authentication across various parts of an application.

Your Challenge this week is to add authentication with JWT to an existing Kanban board application.

The Kanban board application has already been created. It's your job to complete the UI for the login page, add authentication with JWT to the server API, and then deploy the entire application to Render.

## User Story

```md
AS A member of an agile team
I WANT a Kanban board with a secure login page
SO THAT I can securely access and manage my work tasks
```

## Acceptance Criteria

```md
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
```

## Usage
First run the following commands in this order in your terminal:
npm i
npm run build
npm run start:dev
After running the commands the program should be up.
To login to Kanban use the following username and password:
JollyGuru
password
Once logged in you will have access to Kanban

## Contributing
You can contribute by downloading the GitHub repo and adding to it, as the repo is publicly open.

## Tests
I tested it by running it over and over again in my terminal until it worked properly.

## Questions
You can reach me at [ddan25](https://github.com/ddan25) or via email at ddan25@gmail.com for any follow-up questions!

## GitHub Repository
https://github.com/ddan25/kanban

## Deployment
https://kanban-savj.onrender.com
---
© 2024 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.

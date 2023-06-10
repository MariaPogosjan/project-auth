# Project Auth
The aim of this project was to build an API with authentication to implement a registration flow, and a frontend with forms to sign up, sign in, and view some content once user is logged in.

# The main requirements included
Backend:
- Registration endpoint, to create a new user.
- Sign-in endpoint, to authenticate a returning user.
- An authenticated endpoint which only returns content if the `Authorization` header with the user's token was correct.

Frontend:
- A registration form.
- A sign-in form.
- A page to show the authenticated content from the API.
- A 'sign out' button that removes the saved access token and redirects the user to the login form.

# Stretch goals included
- Store data in the database for your authenticated data routes.
- When registering, display error messages from the API.
- Improve validations in the backend to ensure unique email addresses, or validate the email address format using a regular expression.

# Backend endpoints

- POST '/users': creates a user;
- POST '/sessions': allows user to log in;
- POST '/users/:id/feelings': allows user to register emotions of the day

## View it live

Backend: https://moody-be-77tqxxowdq-lz.a.run.app/
Frontend: https://moody-test.netlify.app/

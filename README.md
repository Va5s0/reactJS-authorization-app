# React Authorization app

This is a login application build with ReactJS and https://auth0.com/ service, used for mobile and web apps authentication. It's a simple Bootstrap log-in/sign-up page which lands to a dashboard.

This was a practice assignment for a ReactJS Udemy course I took.

### Installation & setup

- Clone this repo
- Run npm install
- In order to use the application, you need to connect your Auth0 client to Google and request a Client Id. You can learn how to do that at https://auth0.com/docs/connections/social/google
- Store your Client Id and your domain name at secrets.mine.js inside the corresponding variables and rename the file to secrets.js
- You're done!

### Development server

- Start the development server with `npm start`
- Point your browser at http://localhost:3000

### Dependencies

- React ^16.0.0
- react-bootstrap ^0.31.5
- react-dom ^16.0.0
- auth0-lock: "^10.23.1"

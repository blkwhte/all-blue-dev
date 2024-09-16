You will need to have the latest version of Node.js installed on your machine to run the app. Please refer to this guide on installing Node.js if you need a reference: https://nodejs.org/en/download/package-manager#macos

All Blue (dev) utilizes OIDC and the identity token provided to access user information on API v3.0. You will need to create a new Clever dev app, here: https://apps.clever.com/signup

How to run the app:

  1. Clone the Github Repo
  2. Create a .env file and include the following variables: CLEVER_CLIENT_ID, CLEVER_CLIENT_SECRET, REDIRECT_URI_ and a SESSION_SECRET
  4. Run the command "node index.js" in your terminal while in the file location of the repo
  5. Navigate to "localhost:3000" in your web browser of choice
  6. Select the "Log in with Clever" button on the site
  7. When prompted with the School Picker, enter the district ID 63e42be9ea7d85c10c19ebe5 (#DEMO All Blue (dev))
  8. When prompted to log in, select the Clever Passwords login and enter 243615677 for the username and password
  9. You should be redirected back to the All Blue (localhost) site with a message confirming the authentication was successful.

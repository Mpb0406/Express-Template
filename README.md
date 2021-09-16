# Express-Template

## Express Backend connecting with MongoDB Database
This is a backend template with 4 main routes that can be expanded on

### Users Route
Ability to create a new user account using JWT Tokens and BCrypt to hash passwords. Uses express-validator to handle validation on the server side. Route returns JWT token to put in header on the front end

###Auth Route
Authenticate users using JWT and check against hashed password using BCrypt. This route returns a JWT token to put in the header on the frontend for authentication

###Profile Route
8 Endpoints
* Post a new profile
* Get the user profile
* Delete the user profile
* Update the user profile (Experience)
* Delete part of user profile (Experience)
* Update the user profile (Education)
* Delete part of user profile (Education)
* Get github repos from user by username

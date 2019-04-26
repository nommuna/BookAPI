# BookAPI

Repository for the bookAPI project from leetcode. 
https://leetcode.com/discuss/interview-question/system-design/125383/REST-API-for-Book-Catalog/244588

## Getting Started

Follow these instructions to get a dev environment up and running on your system. 

### Prerequisites
```
- Install Node https://nodejs.org/en/.
- Once node is installed you should be able to check the version in the terminal by doing --version.
- Install MongoDB https://www.mongodb.com/download-center/community.
- Install MongoDB Compass(GUI for MongoDB) https://www.mongodb.com/download-center/compass.
```

### Installing
1. Clone the repro.
2. In a terminal, go to the folder where the package.json is and run `npm install`.
3. Then `DEBUG=myapp:* npm start` to run the server. 

### Contributing
- Branches 
    - Master: Should always work. Code review before pushing to master. 
    - Dev: The branch to work with. 
- Workflow (We can change this later if it does not work out)
    - Work from the dev branch. 
    - Before committing to the dev branch do a pull request to get current info from the repro. 
    - Push to dev if everything is good. Also make sure to document the part you did in the code.

### Additional Information
- bin/www - Sets up the server.
- public - any JS, css, images we need for the server.
- routes - Endpoints for the API. Logic for the endpoints should be placed here. 
- test - test logic placed here.
- views - rendering of html for the server if needed. 
- app.js - Entry point for the server. Create new route endpoints here and add middleware.
- .gitignore - Tells git not to push stuff in this file. 
- package.json - dev dependencies/dependencies.

### Testing
 - Testing for the routes are done in the test folder.
 - To run a test do `npm test`.
 - Mochajs doc https://mochajs.org/#getting-started.

### Built With 
- Node - JavaScript Runtime.
- Express - Web Framework.
- MongoDB - Database.
- Mochajs - Testing framework.

# Personal Portfolio

## Tech stack

React 18.2.0</br>
Node 16.16.0</br>
Express 4.18.1

* It's recomended to use the same versions

## Up and Running

To get started, clone/fork or download as zip the repository.

### Command to download packages

  npm install

### Command to run the app

  npm start

### Folder Structure (Demo)

    ├── frontend                         
        ├── src                      # Contains all files used across the project  
            ├── api                      # All services that take care of the communication between the React application(frontend) and an API(backend)
            ├── assets                   # Contains images of the project 
            ├── components               # Collection of UI components
            ├── helpers                  # Contains helper functions
            ├── hooks                    # Contains custom hooks which are used in several components         
        ├── public                   # Contains all static files of the project
            ├── _redirects               # Contains redirect rules for SPA
            ├── index.html               
            ├── manifest.json            
            ├── robots.txt               
        ├── build                    # Contains production files for the application
        ├── README.md   
        ├── package.json
        ├── package.json.lock
    ├── backend
        ├── index.js                 # Handles app start up 
        ├── controllers              # Contains functions that processes the requests
        ├── models                   # All data models required for the application 
        ├── routes                   # Contains all the routes of the application
        ├── README.md   
        ├── package.json
        ├── package.json.lock
    ├── .gitmodules                
    ├── package.json                
    ├── package-lock.json 
------

### Todo's List

[x] API creation, backend/.

[x] API implementaion, frontend/src/api/.

[x] Add responsive styles.

[x] Add client side form validations frontend/src/helpers.

[ ] CI/CD integration.

[ ] Unit Tests.

[ ] Integration Tests.

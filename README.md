# cypress-intermediario
Tests in gitlab using cypres. 

## pre-requirements

It is required to have node.js and npm installed to run this project.

> I used versions `9.6.7` of npm and `v18.17.0`of node.js.

It is also necessary install docker 

## Installation

Run `npm install` to install the dev dependencies  

## Tests

Create the container: `docker run wlsf82/gitlab-ce`. Run docker. 

Run `npx cypress open` to open cypress and `npx cypress run` to run tests in cypress.
You can also run all tests `npx cypress run --spec "path.cy.js"


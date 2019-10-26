# AutomatedBoilerplate
Boilerplate code and tips to help setup automation projects.


# Getting started with Cypress
CypressIO is an end to end testing framework, suitable for UI and API automated testing.

```
npm install
npm run cy:verify
npm run cy:open
```
Check out the examples in cypress/integration/examples

# Getting started with Newman (Postman)
Newman is a command line runner for postman tests. 
Simply export your collections and environments and run using the command line.

```
newman run URL_OR_PATH_TO_COLLECTION -e URL_OR_PATH_TO_ENVIRONMENT
```
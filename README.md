# AutomatedBoilerplate
Boilerplate code and tips to help setup automation projects.

What is included:
- ESLint 
- JUnit Reporter for Cypress
- Example yaml file that can be used in Azure DevOps (All currrently commented out so would need updating)

By pulling down this repo the user should now have the tools to get started with Cypress. Extra plugins can be added as necessary but this could be on a Project by Project basis.


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
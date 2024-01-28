# Loan Management Application
This Meteor and Blaze-based loan management application enables users to register, request loans, and oversee loan transactions. The application includes the following functionalities:

## User Registration
Users can register using their email and choose roles (admin, borrower, lender) during the registration process.

## Loan Request
Borrowers have the ability to submit loan requests, and these requests are displayed on their respective dashboards.

## Loan Confirmation
Lenders can confirm and make loan payments, and the transaction details are updated on both the lender's and borrower's dashboards.

## Dashboard Updates
Any changes in the loan status are immediately reflected on the dashboards of all users involved.

## Admin Dashboard 
Admin users have access to a comprehensive transaction history.

Getting Started
Fork and clone the repository.
Install dependencies by running the meteor npm install command.
Start the web server with the meteor command. The application will be accessible at http://localhost:3000/.
Open your browser and navigate to http://localhost:3000/.

## Dependencies
### Meteor Packages
- accounts-ui
- accounts-password
- kadira:flow-router
- kadira:blaze-layout
- twbs:bootstrap
- themeteorchef:jquery-validation
- jquery
- tprzytula:remember-me
- fortawesome:fontawesome

### NPM Modules
- Meteor
- Bcrypt
- @babel/runtime
- meteor-node-stubs

## Process
This application builds upon the existing Meteor/Blaze project, incorporating additional features for user roles, loan requests, and transactions. Leveraging Meteor's reactive capabilities ensures instant updates on user dashboards.

## Next Steps
Strengthen security protocols, particularly for financial transactions.
Implement a "Forgot password" functionality.
Expand the application's capabilities with more advanced features.
Conduct comprehensive testing and review to ensure readiness for production.

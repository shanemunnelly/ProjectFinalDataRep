Trading Card Database

This project was bootstrapped with Create React App.
Getting Started

In the project directory, you can run:
npm start

Open http://localhost:3000 to view it in your browser after using npm start.
Overview

This CRUD app is designed to Store trading cards in a databse for the purposes of looking at ones collection. Upon starting the app, you'll end up on the home page, which provides an introduction to the app's functionality.
Navigation

The navigation bar offers three main pages:

    Home: Initial landing page with essential information about the app.
    Create: Access this page to add new entries to the MongoDB database.
    Read: View all entries in the database in card form. You can sort them alphabetically based on card names.

Create Component

The Create component enables you to add new entries to the MongoDB database, which will be displayed on the Read component.
Read Component

The Read component displays all entries from the database in bootstrap card format. You can also sort the cards alphabetically with a button. in this component, you have 2 other components:

    Edit: goes to a page like to the Create component. This page has the information of the selected card, allowing you to update and modify it.
    Delete: Remove the selected entry from both the database and the website.


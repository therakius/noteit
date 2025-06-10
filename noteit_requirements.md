## Noteit
> a web application that helps people take notes from the books they read!

### requirements:

### 1. signup page
The signup page is going to be very simple. users will be able to register using their google/github account, or enter they data, namely the usarname and password in order to create an account, after the account has been created, the users will be redirected to their dashboards, where they can add books and notes for their books

### 2. login
The login page must be very simple and intuitive. users should be able to login with google, github or email and password.

### 3. Add a book
After the user has logged in, a blank page will be rendered to him, with a button to add a book.
Clicking at the button, the user will receive a popup, to add the data related to that book, such as title and author. and once he clicks on 'checked' the book will be added.

The book cover will be rendered automatically, using the book covers api.

### 3. add notes to a book

the user will be able to add notes by clicking o the button '+', where he can start writing his thoughts on the related book.

## The MVP

The minimum viable product will have a simple interface, and as for the text editor, for this version, it is going to be a plain text, with the possibility of applying markdown for better hierarchy and styling.

Users will be able to add up to 10 books.

Users will be able to update and delete their notes.

Users wil be able to manage their accounts.

The application will collect information such as email, full name and profile picture.

Every note that the users will take will be confidential (only they will have access to them, unless they want to make them public).

## Tech stack

### technologies and services:
* html / ejs
* css
* javascript
* node.js + express.js
* PostgreSQL
* book covers api

The project is going to be deployed on render (backend), vercel (frontend).

the database is probably goin to be stored in supabase.

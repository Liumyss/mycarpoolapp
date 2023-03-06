# Overview

The objective of this project is to demonstrate the development of a robust yet straightforward authentication system for a mobile application using Firebase, a cloud-based database developed by Google. A cloud database has the capability to store information that can be accessed through an internet connection from any location, simply by logging into the database.

This mobile application allows users to register new login credentials, which are added to the cloud database. In other words, it creates a new user instance with unique values such as an email, a password, and a verification status (e.g., emailVerified = true). The application then establishes a connection between the user's input and the database to either register a new user or authenticate an existing one.

Furthermore, the application is designed to handle exceptions such as invalid email addresses or email addresses that have already been registered by another user. The cloud database is configured to accept only specific values to ensure data consistency and accuracy.

In summary, this project showcases the development of a powerful yet easy-to-use authentication system for a mobile application using Firebase, a reliable cloud database solution developed by Google. The system is designed to handle exceptions, maintain data consistency, and enhance the user experience.


[Software Demo Video](https://youtu.be/nAo1GlPY2VY)

# Cloud Database

I am using the Firebase Database made by Google. The app uses the Firebase Authentification Module that let an user to insert login credentials in the cloud database to be used later again to sign in the app.

# Development Environment

- Firebase
- Firebase Auth
- VS Code
- Flutter
- Dart (Programming Language)
- IOS Emulator

# Useful Websites

{Make a list of websites that you found helpful in this project}

- [Intro to CLoud Databases](https://www.oreilly.com/library/view/an-introduction-to/9781492044857/ch01.html)
- [What are Cloud Databases?](https://www.mongodb.com/cloud-database)
- [How to use Flutter and Firebase together](https://firebase.google.com/docs/flutter/setup?platform=ios)

# Future Work

{Make a list of things that you need to fix, improve, and add in the future.}

- Allow users to store data in the app that only them can access by signing in to their account.
- Focus on the design of the app to make it more responsive and attractive for potential users
- Allow users to create an account with another way of authentification (Like a Google or Apple account)
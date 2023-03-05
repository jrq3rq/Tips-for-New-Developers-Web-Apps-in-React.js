# Steps for Deploying a Web Application on Firebase

Install Firebase CLI:

You will need to install Firebase Command Line Interface (CLI) using Homebrew or npm. Open your terminal and enter one of the following commands:

## For Mac users:

```javascript
// This is an example of a code block
$ brew install firebase-cli
```

## For Windows users:

```javascript
// This is an example of a code block
$ npm install -g firebase-tools
```

## Sign in to Firebase: Use the following command to sign in to your Firebase account:

```javascript
// This is an example of a code block
$ firebase login
```

## Create a new Firebase project: Go to the Firebase console and create a new project.

## Initialize your Firebase project: Navigate to your project directory in the terminal and run the following command:

```javascript
// This is an example of a code block
$ firebase init
```

## Follow the prompts to set up Firebase hosting for your project. Make sure to select "Hosting" when prompted to choose a Firebase service.

## Set up your project: Follow the prompts to set up your project. For the "public directory", enter the directory where your web application is located.

## Deploy your project: Run the following command to deploy your project to Firebase hosting:

```javascript
// This is an example of a code block
$ firebase deploy
```

## Your website will be available at the URL specified in the Firebase console.

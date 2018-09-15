This React/Webpack project is deployed to Firebase at [https://webpack-react-pizza.firebaseapp.com](https://webpack-react-pizza.firebaseapp.com)

## To Use Locally

### Install dependencies:

`npm install`

In the project directory, you can run:

`npm start`

Runs the app in the development mode.<br>
Open [http://localhost:8080](http://localhost:8080) to view it in the browser.

## To deploy

### Build production files first:
`npm run build`

Then follow the instructions on your preferred hosting.

For example, in Firebase:

`sudo npm install -g firebase-tools`

`firebase login`

`firebase init`

Then:
1. select the Firebase project you created on Firebase to associate this project with.
2. select the folder containing the production files as your public directory
3. type 'y' for yes, to confirm that you want to configure a single-page app
4. if you already have an index.html file, type 'n' for no, to not overwrite it

`firebase deploy`

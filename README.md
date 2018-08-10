# Quick guidance for installing reactstrap in React

The procedures of installing reactstrap can sometimes be confusing. This guidance is for the developers we want to install reactstrap quickly to their React projects. The `App.js` file in this repo shows a navigation bar of reactstrap / Bootstrap.

Let's start!

## 1. Install create-react

- Run `npm install -g create-react-app`.
- Run `create-react-app my-app`.
- Run `cd my-app`.
- Run `npm start`. (Alternatively, you can skip it and execute it at Step 4.)

## 2. Install reactstrap and peer dependencies via NPM

Run `npm install --save reactstrap react react-dom

(You can open another terminal if you skip running `npm start`.)

## 3. Install Bootstrap

- Run `npm install bootstrap --save`.
- Run `npm install --save reactstrap react react-dom`.
- Import Bootstrap CSS to `src/index.js`:

  `import 'bootstrap/dist/css/bootstrap.min.css';`

- Import the chosen reactstrap components to `src/App.js` or your custom component files:

  `import {Element} from 'reactstrap';`

## 4. Add reactstrap code

- Visit the [reactstrap](https://reactstrap.github.io/) website and choose a component.
- Add the code of the chosen component to your `App.js` or other files. Modify it when necessary.
- Execute `npm start` if you skip it at Step 1.

## 5. Add CDN

When you deploy the web app to a server, add a Bootstrap CDN link from [here](https://cdnjs.com/libraries/react) to ensure Bootstrap works properly.



Courtesy of the excellent developer **[Mr Norbert Angyal](https://github.com/nangyal)** and the [reactstrap](https://reactstrap.github.io/) website.

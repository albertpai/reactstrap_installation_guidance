## How to install reactstrap correctly?

1. Install create-react-app (Short instruction)
`npm install -g create-react-app`
`create-react-app my-app`
`cd my-app`
`npm start`

2. NPM - Install reactstrap and peer dependencies via NPM
`npm install --save reactstrap react react-dom` 

3. Adding Bootstrap
`npm install bootstrap --save`
`npm install --save reactstrap react react-dom`
Import Bootstrap CSS in the `src/index.js` file:
`import 'bootstrap/dist/css/bootstrap.min.css';`
Import required reactstrap components within `src/App.js` file or your custom component files:
`import {Element} from 'reactstrap';`

Courtesy of reactstrap https://reactstrap.github.io/




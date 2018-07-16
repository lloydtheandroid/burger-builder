# burger-builder
React Burger Builder App

The code in this app is Based on [React 16 - The Complete Guide](https://www.udemy.com/react-the-complete-guide-incl-redux) instructed by [Maximilian Schwarzmüller](https://twitter.com/maxedapps)

App is built on Nodejs and React.

To use:

1) Run "npm install" in the extracted folder
2) Run "npm start" to view the project

**NOTE:** **/src/hoc/Aux.js** *is a reserved name in windows.* You will need to add this file manually. See below:  
### Aux.js
```javascript
const aux = (props) => props.children;

export default aux;
```
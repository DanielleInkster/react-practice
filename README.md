# Practice with React

In an effort to become more familiar with React, I completed a tutorial found here: 
https://reactjs.org/tutorial/tutorial.html

This was a step-by-step guide to complete a simple tic-tac-toe game that allows users to take turns as well as tracks moves and declares a winner. 

### Technologies
 - React
 - CSS
 - ***It's recommended but not strictly necessary to have a recent version of Node.js installed***
 
 ### How to install and run
 
 ```
 git clone git@github.com:DanielleInkster/react-practice.git
 npm start (if Node is installed)
 
```
### Reflection

Admittedly, I think this tutorial did a bit too much handholding but it is a good jumping-off point. It's showed me the very basics of React and (though probably unintentionally) helped me find questions to ask about how React works and why, which is far better off than I was before (that is, not even sure where to start.) I plan to complete another tutorial or two before beginning my own project (completing a front-end for my Javascript tech test.) 

### What I've learned

- ***Components*** are a Javascript class or function that takes properties as inputs and returns a React element that describes how the User Interface should look. 
    - ***Functional Components*** are basically Javascript functions that are only for show, such as buttons. They don't use a render method
    - ***Class Components*** extend the component class in React. They usually implement logic and/or state. 

- ***Properties(Props)*** are immutable data (usually) passed from parent components to child components. I understand this in theory but would benefit from more hands-on practice. `super(props)` is used in the parent constructor only. 

- ***State*** is not inherited but created within the component itself. State is changed over time (usually by user activity) using `this.state info` and `.setState` (causes object to re-render). State remains within the component; it is not passed on to any child components. 

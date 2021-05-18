# React lifecycle 

+ The render happens first method is required and will always be called, the others are optional and will be called if you define them.

+ Mounting phase (constructor) which is mean  putting elements into the DOM.

+ React has four built-in methods constructor, render, React Updates, componentDidMount, and componentWillUnmount.

+ componentDidMount() is used to connect to the YouTube API and get videos when the components is rendered.

![react cycle](https://www.kirupa.com/react/images/lifecycle_react2.png)


## prpps and State 

+ Props: are like arguments to functions, props pass into a component which means It is handled outside the component 
and must be updated outside the component Props are passed to components via HTML attributes.



+ State: object inside a component, is handled inside the component and must be updated inside the component
When the state object changes, the component re-renders.
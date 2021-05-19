# Thinking in React

+ Break The UI Into a component hierarchy

you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names.

+ so  we have five components in our app:

*FilterableProductTable (orange)*

*SearchBar (blue)*

*ProductTable (green)*

*ProductCategoryRow (turquoise)*

*ProductRow (red)*

+ use the single responsibility principle to decide which is a component or not and then 
 build a static version of your application .

+ add State to make the UI interactive

+ Is it passed in from a parent via props? If so, it probably isn’t state.

 Does it remain unchanged over time? If so, it probably isn’t state.

 Can you compute it based on any other state or props in your component? If so, it isn’t state.

+ For each piece of state in your application:

Identify every component that renders something based on that state.

Find a common owner component (a single component above all the components that need the state in the hierarchy).

Either the common owner or another component higher up in the hierarchy should own the state.

If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it 
somewhere in the hierarchy above the common owner component.

# reading-notes for code 301

My reading notes for **Class 2**


#### Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

render

#### What is the very first thing to happen in the lifecycle of React?

Mounting

#### Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

Constructor, Render, React Updates, componentDidMount - render, updates, componentDidUpdate

#### What does componentDidMount do?

Allows you to execute code when the component is already placed in the DOM.

#### What types of things can you pass in the props?

Any component information that you will wish to use.

#### What is the big difference between props and state?

State is handled inside the component and Props are handled outside.

#### When do we re-render our application?

Everytime state changes

#### What are some examples of things that we could store in state?

Counter, user input, form, checkbox


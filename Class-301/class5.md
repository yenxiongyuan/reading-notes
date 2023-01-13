# reading-notes for code 301

My reading notes for **Class 5**


#### What is the single responsibility principle and how does it apply to components?

One component should be doing only one thing

#### What does it mean to build a ‘static’ version of your application?

Build a version of your app that renders the UI but has no interactivity

#### Once you have a static application, what do you need to add?

State

#### What are the three questions you can ask to determine if something is state?

* Is it passed in from a parent via props?
* Does it remain unchanged over time?
* Can you compute it based on any other state or props in your component?

#### How can you identify where state needs to live?

* Identify every component that renders based off state
* find common owner of component
* common owner OR another component higher up should OWN

#### What is a “higher-order function”?

Functions that operate off of other functions.

#### Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

Returning a boolean 

#### Explain how either map or reduce operates, with regards to higher-order functions.

It uses the function you pass on all of the elements in the array 


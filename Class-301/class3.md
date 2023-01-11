# reading-notes for code 301

My reading notes for **Class 3**


#### What does .map() return?

New mapped array

#### If I want to loop through an array and display each value in JSX, how do I do that in React?

Use the map function

#### Each list item needs a unique _____.

Key

#### What is the purpose of a key?

Helps react identify which items have changed, added, or removed.

#### What is the spread operator?

Expands iterable object into the list of arguments.

#### List 4 things that the spread operator can do.

Copying an array, Concatenating or combining arrays, Using Math functions, Using an array as arguments

#### Give an example of using the spread operator to combine two arrays.

let oneArr = [1, 2, 3] 
let twoArr = [4, 5, 6] 
let bothArr = [...oneArr, ...twoArr]

#### Give an example of using the spread operator to add a new item to an array.

let numbers = [1, 2, 3] ;
let addNumbers = [... numbers, 4, 5,]

#### Give an example of using the spread operator to combine two objects into one.

let objOne = { name: 'tom' };     
let objTwo = { id: 18 };     
let newObject = { ...objOne, ...objTwo };

#### In the video, what is the first step that the developer does to pass functions between components?

Create the function wherever the state changes

#### In your own words, what does the increment function do?

Add one count to the state

#### How can you pass a method from a parent component into a child component?

Using props

#### How does the child component invoke a method that was passed to it from a parent component?

this.props.name(things you want to passed)
# reading-notes for code 201
My reading notes for **Class 3**

#### When should you use an unordered list in your HTML document?

Unordered list don't have a numerical ordering and there is no meaning to the order.

#### How do you change the bullet style of unordered list items?

You can use css and change the bullet style through the "type" attribute.

#### When should you use an ordered list vs an unorder list in your HTML document?

Ordered is for when you need to list items in a particular order, unordered is for related but not in a particular order.

#### Describe two ways you can change the numbers on list items provided by an ordered list?

* lowercase Roman numerals
* uppercase Roman numerals

#### Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

* content box: this is where the content lies
* padding: this is the space between the content box and the border
* border: usually a visible border (the box)
* margin: the outer space between other content and the border of the box

#### What data types can you store inside of an Array?

You can store strings, numbers, booleans, and other arrays inside of the Array.

#### Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

To access the items in the array first call the name of the array followed by the slot number(which starts at 0) of the object you want to grab.

#### List five shorthand operators for assignment in javascript and describe what they do.

* == assignment 
* += addition 
* -= subtraction 
* *= multiplication 
* /= division 

#### Read the code below and evaluate the last expression and explain what the result would be and why.

let a = 10; let b = 'dog'; let c = false;
// evaluate this (a + c) + b;

This will give you nothing because these are different variable types.

#### Describe a real world example of when a conditional statement should be used in a JavaScript program.

If the person is old enough to drive.

#### Give an example of when a Loop is useful in JavaScript.

When you want to run a piece of code a certain number of times.

## Things I want to know more about

Spend more time with Array.
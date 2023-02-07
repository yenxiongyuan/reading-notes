# reading-notes for code 301

My reading notes for **Class 9**


#### What is functional programming?

It's a way of programming by means of using functional logic to your code to create clean and maintainable code

#### What is a pure function and how do we know if something is a pure function?

It has no side effects to the code and returns a result

#### What are the benefits of a pure function?

They are easier to test

#### What is immutability?

Unchanging over time or unable to be changed.

#### What is Referential transparency?

Holds same result for same input

#### What is a module?

A module is file containing self contained code that is imported and exported to share functionality

#### What does the word ‘require’ do?

Brings the module into the current file

#### How do we bring another module into the file that we are working in?

require('./filepath')

#### What do we have to do to make a module available?

module.exports = function
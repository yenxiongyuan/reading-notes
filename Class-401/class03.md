# reading-notes for code 401

My reading notes for **Class 3**


#### Classes are a template for creating ____.

Objects

#### Can a class declaration be hoisted?

A class will reject being hoisted because they have to be defined before they're constructed

#### How would you describe a constructor and contextual “this” to a non-technical friend?

Creates the object with those properties of it, and it's all customizable

#### Within Express, what does routing refer to?

This is the direction pointing to an endpoint

#### What is the difference between a route path and a route method?

Path takes you to that page only, no queries and other information can be passed along. Method are get/post/etc to accomplish the task

#### When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

So the function can continue to move to the next iteration

#### What is an Express Router?

A mini instance of the express app. It can only contain the routing functionality.

#### By what mean do we initialize express.Router() in an express server?

We create routes and then tell our app to use those routes.

#### What do we use route middleware for?

This allows us to do something or have checks prior to running the route
# reading-notes for code 301

My reading notes for **Class 12**


#### In your own words, describe what each group of status code represents:

* 100’s = informational; tells the client the request has been received
* 200’s = success codes
* 300’s = redirection codes
* 400’s = client error codes - something about the request was wrong
* 500’s = server error codes

#### What is a status code 202?

Accepted

#### What is a status code 308?

Website/API has a new URL

#### What code would you use if an update didn’t return data to a client?

204 No Content

#### What code would you use if a resource used to exist but no longer does?

410 Gone

#### What is the ‘Forbidden’ status code?

403 - no permissions to access the resource

#### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

The URL will be different in local testing than when it is deployed.

#### What is middleware?

Code that run when server gets request but before it gets past to routes

#### What does app.use(express.json()) do?

lets server accept json

#### What does the /:id mean in a route?

It is a parameter

#### What is the difference between PUT and PATCH?

put updates everything while patch only modifies part

#### How do you make a default value in a schema?

default: "default value goes here"

#### What does a 500 error status code mean?

Server had a error

#### What is the difference between a status 200 and a status 201?

200 means the request was successful while 201 indicates a resource was created
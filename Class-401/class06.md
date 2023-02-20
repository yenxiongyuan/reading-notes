# reading-notes for code 401

My reading notes for **Class 6**

#### Explain to a non-technical friend how you would safely hash and store a password.

Hashing is a way to store huge amounts of data in a short as time possible.

#### What is Bcrypt?

Bcrypt is a way of encrypting passwords with a techinique called key stretching.

#### Why might you use something like Bcrypt?

To stop brute force attackers trying to steal passwords and user information.

#### What is Basic Authentication?

Its a way for an HTTP request to provide a username and password

#### What properties are necessary in the header of a Basic Auth request?

A form of authorization that take basic credential, this is where credential are base64 encoded and joined by single colon

#### How are username:password in Basic Auth encoded?

They are encoded in Base64

#### Define the authentication process to a non-technical recruiter.

Allows user to be verified and ensure they meet the credentials

#### How should your error messaging respond (both HTTP and HTML)? Why?

Error messages should be generic. We dont want to help the brute force attacker

#### Bookmark and Review

[bcrypt docs](https://www.npmjs.com/package/bcrypt)
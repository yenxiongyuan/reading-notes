# reading-notes for code 401

My reading notes for **Class 7**

#### What is a JSON Web Token (JWT)?

JWT is an open standard (RFC 7519) this is a compact way of of securely transmitting info from one party to another

#### When should we use JSON Web Tokens?

during authorization or information exchange

#### Claims are expected in which structural component of a JWT?

Claims are expected to be in the payload component

#### If I get a JWT and I can decode the payload, how can we call that secure?

the payload encrypted separate from JWT

#### If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

Both sender and receiver need the hash

#### Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

A key is like a map that shows you how to decode a secret message. You need the key to figure out the password that unlocks the message

#### Why use JWT?

JWT is a good option because it verifies the transfer of data and it is an open standard, so anyone can use it.

#### JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

With it being compact its transmission is fast and being self contained we dont need anything else to use it. Everything is there.

#### What are the three components (the structure) of a JWT signature?

* Header
* Payload
* Signature

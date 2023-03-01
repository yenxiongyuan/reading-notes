# reading-notes for code 401

My reading notes for **Class 13**

#### Explain to a non-technical recruiter what the Chat Example (above) does.

chat is a bi-directional communication between two or more clients and servers

#### What proof of life are we getting on the backend from the above app?

Console logs record when a user connects or disconnects as well as when a message is sent.

#### Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

broadcasting flag

#### What is a room and how might a room be useful?

A room is a channel that sockets can join and leave.

#### How do you join a room?

socket.join

#### how do you leave a room?

socket.on("disconnect")

#### What is a Namespace and what does it allow you to do?

allows you to split the logic of your application over a single shared connection.

#### Each namespace potentially has its own what? (hint: 3 things)

* Event Handlers
* Rooms
* Middleware

#### Discuss a possible use case for separate namespaces

To create private rooms

## Bookmark and Review
[Socket.io Emit Cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)
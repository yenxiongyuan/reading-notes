# reading-notes for code 401

My reading notes for **Class 19**


#### What is the difference betweeen SQS and SNS?

* SNS is distributed publish-subscribe service.
* SQS is distributed queuing service.

#### What is the difference betweeen SQS and SNS?

Use SNS if order doesn't matter. Use SQS if order is needed

#### Describe how to use SQS and SNS in a “fanout” pattern.

Publish topics to many subscribers, messages broadcast to one-to-many arrangement

#### Explain how “push notifications” work, using SNS.

The SNS sends a message out to each subscriber. If the subscriber is active, they receive the message.

#### How might a large scale, distributed application make use of a Queue system like SQS?

SQS is highly scalable and has a queueing system so all will get messages in order
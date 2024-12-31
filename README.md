# Real-Time Chat Application

A simple chat application built using raw WebSockets in Node.js with the following features:

- Allow an admin to create a new chat session/room.
- Admin should be allowed to set the following properties on the room:
  - Name
  - Start time
  - Is open
  - Cool down time
- Allow users to join the room and send messages.
- Allow users to upvote chat messages.
- If chat messages reach more than 3 upvotes, move them over to a separate section.
- If chat messages reach more than 10 upvotes, alert the admin to answer.

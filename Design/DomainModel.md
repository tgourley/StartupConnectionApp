# Domain Model

![Domain Model](../Auxiliary%20Files/Domain_Model.png)

## Classes

### Chat
The Chat is where message related tasks will be generated; allowing users to interact with each other. Questions people may have over pitches can be asked here, for example.
### User
User will contain all basic shared information and methods dedicated to the three roles: investor, founder, and developer.
### Admin
Admin is a type of user with special commands. This allows for the software to be moderated.
### Proposal
Proposal will contain all information regarding a developer or investor proposal. These can then be accepted or denied by the recipient.
### Funds
Funds are the allocated resource of a given pitch or investor. This determines how other users will be paid.
### Search
Every user needs the ability to search for pitches to determine what they want to interact with. The search class will fulfill the given searches.
### Pitch
Pitch will contain all information related to a given pitch.
### Graphic
Graphic is focused around creating and finding visuals to represent the project.

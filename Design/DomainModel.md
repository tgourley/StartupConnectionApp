# Domain Model

![Domain Model](../Auxiliary%20Files/Domain_Model.jpg)

## Classes

### Profile
Profile is where information dictated by users intercations with each other's profiles. Such as the number of visitors a profile has gotten within a given timeframe.
### Inbox
The inbox is where message related tasks will be generated; allowing users to interact with each other. Questions people may have over pitches can be asked here, for example.
### User
User will contain all basic shared information dedicated to the three roles: investor, founder, and developer.
### Investor
Investors have actions that founders and developers will not have, such as the ability to fund a pitch. This requires investors to have their own class.
### Founder
Founders have the ability to create pitches, making them different from investors and developers.
### Develeoper
Developers require different information to dictate if they should work on a given pitch, such as their programming language knowledge. This requires them to be seperated from the other users.
### Funds
Funds are how investors, pitches, and payment will interact with money.
### Payment
Payment will focus around distributing the money to founders and developers who participated in the pitch.
### Search
Every user needs the ability to search for pitches to determine what they want to interact with. The search class will fulfill the given searches.
### Pitch
Pitch will contain all information related to a given pitch.
### Graphics
Graphics is focused around creating and finding visuals to represent the project.
### Project
Project is viewed slightly differently than Pitch. Project is a completed pitch, resulting in it needing different function and information.

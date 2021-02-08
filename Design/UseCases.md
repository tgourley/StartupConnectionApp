## Actors
* **Software System** - Payment management, Keyword analysis, Pitch cataloging, Collect statistical data.

* **Founder** - Pitch creation, Create statistics.

* **Investor** -Observation of parties, provide funds.

* **Developer** - Completion of tasks, observation of parties.

* **User (Founder, Investor, and Developer)** - Profile creation, Sending direct messages, Negotiate terms, Fluid role choice.

* **Administrator** - System support, processing management, SuperUser, security

## Use Cases
* **UC1** Search for pitches.
  * Searching for pitches is a fundamental and necessary part of the system. It will allow the actors of our system to find different pitches to inquire about. They may not join them, but having the ability to search for them will give them the opportunity to find pitches they prefer.
  * To use this function the actor will locate the search function on the page and filter for the pitches their looking for by name.
  * Actors: Developer, Investor, System
  * BR1
  
* **UC2** Define keywords for pitch.
  * Certain keywords are associated with different types of pitches. Being able to define by keywords for a pitch during pitch creation is important because it gives it a category for interested users to search in. Investors will search for pitches they're interested in based on those keywords. 
  * Inside of the pitches creation menu there will be a text box titled "Keywords". The founder can select this text box to enter 
  * Actors: Founder
  * BR1

* **UC3** Filter profrane and vulgar pitch keywords
  * Admins need the ability to filter out tags and pitch pages that use obscene and vulgar language or have a negative purpose. We want the application to allow adult content, but all within reason. Anything that isn't formal and decent should be able to be blocked or disabled from view by an admin.
  * An admin would go to the search page and either search for vulgar language in titles or by tags and disable them accordingly with buttons located on each pitch holder.
  * Actors: Administrator
  * BR1

* **UC4** Create user profiles.
  * The users will need profiles to store different information related to what they're involved in on the site. This could be negotiations through direct messages, projects their a part of, etc. Creating a user profile is a necessary feature because it provides these functionalities which are critical to the site. Without user profiles, the site couldn't function in the intended way because it wouldn't provide these critical functionalities.
  * In order to create a user profile they will have to navigate to the "Sign Up" button, click it, and then fill out a form asking for their email and a password. After they fill out the form and hit "Submit", they'll have created a user profile.
  * Actors: User
  * BR2
  
* **UC5** Create statistical graphics.
  * Statistical graphs will be used to represent data about a pitches. It will provide useful information that can be used to see if the pitch is on a good path or not. It will be beneficial because it will provide concrete details on how quickly and efficiently the pitch is progressing.
  * The system will create the graphs under the Graphs page. It will collect the input over the course of the pitch.
  * Actors: System, Founder
  * BR2
  
* **UC6** Format pitch page.
  * The founder needs to bring developers and investors into their pitch. They can accomplish through through formatting their pitch page in a way that attracts their target audience. Their pitch page should catch the attention of the intended audience quickly.
  * In order to format the pitch page it needs to be created first. Then, the founder would display the information where it needs to go through drag and drop. The founder may want slides in the middle of the pitch page, or page interactions in the upper right of the page. They will decide where items such as statstics are placed and the general information of the page.
  * Actors: Founder
  * BR2
  
* **UC7** Verify pitch pages after creation.
  * An administrator will need to verify a pitch before it will displayed on the website. This helps limit scam pitches and obscene pitches by using reasoning to deduce when something isnt right. Administrators will judge this based on a set list of guidelines mostly, not just on personal opinon.
  * This will be done on a page specifically for the admins where it is the pitch deck and any other information related to it and an approve or deny button.
  * Actors: Administrator
  * BR2

* **UC8** Send direct messages.
  * This is a very important feature because it will allow users to privately communicate with one another. It's necessary because of the communication component. They will be able to discuss options for any pitches or pitches they're considering, have completed, or are currently a part of.
  * In order to send a direct message a user will navigate to the Direct Messages button on the site. They will only be able to do this if they are signed into their account. Then, they will click the Direct Message button and be taken to the Direct Message page where a list of previous messages are stored. They can choose to send a new message or reply using a message thread already listed. 
  * Actors: User
  * BR3
* **UC9** Create pitch pages.
  * Creating pitch pages is an important part of the software because it is how the founders will advertise to potential investors or developers for their pitch. The pitch page hosts the information that will attract these users to the pitch. It's also the place that describes what the pitch is intended to be. 
  * To create a pitch page a founder will navigate to the button on the home page that says "Create Pitch". This will redirect them to the pitch creation page. Here, they'll have to enter the name of their pitch, details, and keywords for others to be able to find it. 
  * Actors: Founder
  * BR3

* **UC10** report issues in chat.
  * Reporting is important for a chat system where users can report other users who are being obscene, vulgar, or trying to scam people and keep the community around the software healthy and formal. It is common chatroom etiquette to be be kind to other users, and when you aren't, there is consequences.
  * This will be achieved by a user clicking on another user's name or profile picture and click the "report" button and typing out a description of why they are being reported.
  * Actors: Users
  * BR3

* **UC11** Handle chat reports
  * Administrators will review chat reports and determine if the accused user is breaking any guidelines. If the user is breaking the guidelines, they will be muted in that chatroom. If a second report is filed on the same person, they will be muted for a week in all chatrooms. If a third report is filed on them, they will be muted indefinitely with little chance of recovery.
  * This will be done in a reports section on an administrators workpage, with each report linking to the moment in the chatroom and the message from the person writing the report.
  * Actors: Administrator
  * BR3

* **UC12** Interchange between user roles.
  * Interchanging between user roles is an important use case because users may have to switch between different roles. For example, a founder for a pitch may be a developer on another pitch and/or on the same pitch. Users need to be able to switch between roles so they can take on the different roles that are required of them per pitch.
  * Interchanging between user roles is fluid between it exists in the back-end to dictate functionality. The user is given the roles based on the tasks they perform. For example, if they click the Create Pitch tab they would then go through that process as a founder.
  * Actors: User
  * BR4

* **UC13** Disable account permissions.
  * When a user is breaking guidelines set by the client and developers repeatedly, the user needs to be dealt with to prevent any other mishaps. An administrator will be able to disable accounts entirely to prevent further issues from the user.
  * This will be done by an administrator on a users profile, with a red button labeled disable. It will require the administrator to enter their password to disable it to remove possibility of other users disabling accounts by chance.
  * Actors: Administrator
  * BR4

* **UC14** Manage investor payment processing.
  * This use case is critical to the software. managing investor payments is one of the most important tasks the software has since it serves as an intermediary between the different users. It tracks the investor payments so everyone is satisfied and the money goes to who its supposed to.
  * The investors give the money to the third party and  they hold it until the system is told by the administrator to disperse the money to the necessary parties.
  * Actors: System, administrator
  * BR5
* **UC15** Finish a given pitch.
  * This use case is necessary because the pitch should eventually be completed. Once the pitch is finished funds can be dispersed. The end goal of the pitch is to eventually reach this point.
  * In the pitch page the developer will find the "Finish" button within the pitch settings. Clicking it will finish the pitch.
  * Actors: Developer
  * BR5

* **UC16** process fund acquisition.
  * This use case stems from making sure the money is actaully being provided and the founder and developer don't get screwed over. When an investor funds a pitch, the system will detect that they did and mark a pitch as funded. At this point, the funds are in a secure location where the investor can't retract them (without special circumstances) and the money is guaranteed to the founder/developer.
  * This is done by an approved investment proposal by a founder being sent to an administrator to change the status of the pitch.
  * Actors: Administrators
  * BR5

* **UC17** process fund distribution.
  * Fund distribution when a pitch is in development is essential to ensure the developer gets paid for their work and the founder has money to advertise and build their business/idea. This will be done by an administrator marking a pitch in development and the third party distributing the money in the way agreed in the development proposals, if any.
  * This will be done similarly to the acquisition, where once a founder and investor (and developer) agree on terms, the pitch will transition into development and will be marked by an administrator as in development. The money will then be distributed accordingly.
  * Actors: Administrators
  * BR5

* **UC18** Change status of pitches.
  * Changing the status of a pitch is essential to knowing how far along an idea is and what is left to fulfill. An administrator will change the status of a pitch as investors and developers submit proposals and they are approved by the founder. This is to keep our system in order and middle-man for the pitch team.
  * This will be done by going to a pitch page as an administrator and choosing from a drop-down menu, switching the status on the public page.
  * Actors: Administrators
  * BR5

* **UC19** Negotiate terms of a pitch.
  * The ability to negotiate terms is important because it lets the different users involved in the process come to an agreement on pitch details. Once the different users come to agreement the pitch is complete and the pitch can move forward. Without this functionality, the users would find it difficult to come to an appropriate agreement on individual terms for the pitch. One way they will be able to negotiate is through the direct message functionality.
  * To negotiate terms of a pitch the users will navigate to the direct messages page. Here, they can choose who to negotiate with by sending a message to them.
  * Actors: User
  * BR6
* **UC20** Observe associated parties with the pitch.
  * The investor or developers will want to be able to see the parties associated with certain pitches to make an educated decision on if they want to be involved with them. By being able to observe associated parties with the pitch the investor or developer can determine their overall quality and if they're worth being involved with based on the pitch. It could be someone the investor or developer has worked with before so they can make a decision based on their previous experience with them.
  * The investor or developer will navigate to the pitch page. While there, they'll be able to see a contribution list of who has contributed to the pitch. They can click on each contributor to navigate to their profile and see more information about them.
  * Actors: Investor, Developer
  * BR6
  
* **UC21** Confirm pitch investment proposals.
  * A founder needs to be able to agree to the terms of an investment such as amount and terms stated by the investor. The founder should be able to do this with ease to ensure connections are established and the pitch can move forward.
  * The founder will go to their pitch page, under a widget labeled "proposals", they can select a proposal and choose to accept or decline it.
  * Actors: Founders
  * BR6

* **UC22** Confirm pitch development proposals.
  * The founder also needs to be able to agree to the tech-stack and payment terms discussed by the developer. This is huge when trying to find developers for your software and ensures their payment in the long run.
  * This will be done the same way as investment proposals.
  * Actors: Founders
  * BR6

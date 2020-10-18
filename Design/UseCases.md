## Actors
* **Software System** - Payment management, Keyword analysis, Pitch cataloging, Collect statistical data.

* **Founder** - Pitch creation, Create statistics.

* **Investor** -Observation of parties, provide funds.

* **Developer** - Completion of tasks, observation of parties.

* **User (Founder, Investor, and Developer)** - Profile creation, Sending direct messages, Negotiate terms, Fluid role choice.

## Use Cases
* **UC1** Search for projects.
  * Searching for projects is a fundamental and necessary part of the system. It will allow the actors of our system to find different projects to inquire about. They may not join them, but having the ability to search for them will give them the opportunity to find projects they prefer.
  * To use this function the actor will locate the search function on the page and filter for the project their looking for by name.
  * Actors: Developer, Investor, System
  * BR1
  
* **UC2** Define keywords for pitch.
  * Certain keywords are associated with different types of pitches. Being able to define by keywords for a pitch during pitch creation is important because it gives it a category for interested users to search in. Founders will search for pitches they're interested in based on those keywords. 
  * Inside of the project creation menu there will be a text box titled "Keywords". The founder can select this text box to enter 
  * Actors: Founder
  * BR1

* **UC3** Create user profiles.
  * The users will need profiles to store different information related to what they're involved in on the site. This could be negotiations through direct messages, projects their a part of, etc. Creating a user profile is a necessary feature because it provides these functionalities which are critical to the site. Without user profiles, the site couldn't function in the intended way because it wouldn't provide these critical functionalities.
  * In order to create a user profile they will have to navigate to the "Sign Up" button, click it, and then fill out a form asking for their email and a password. After they fill out the form and hit "Submit", they'll have created a user profile.
  * Actors: User
  * BR2
  
* **UC4** Create statistical graphics.
  * Statistical graphs will be used to represent data about a project. It will provide useful information that can be used to see if the project is on a good path or not. It will beneficial because it will provide concrete details on how quickly and efficiently the project is progressing.
  * The system will create the graphs under the Graphs page. It will collect the input over the course of the project.
  * Actors: System, Founder
  * BR2
  
* **UC5** Format pitch page.
  * The founder needs to bring developers and investors into their project. They can accomplish through through formatting their pitch page in a way that attracts their target audience. Their pitch page should catch the attention of the intended audience quickly.
  * In order to format the pitch page it needs to be created first. Then, the founder would display the information where it needs to go through drag and drop. The founder may want slides in the middle of the pitch page, or page interactions in the upper right of the page. They will decide where items such as statstics are placed and the general information of the page.
  * Actors: Founder
  * BR2
  
* **UC6** Send direct messages.
  * This is a very important feature because it will allow users to privately communicate with one another. It's necessary because of the communication component. They will be able to discuss options for any projects or pitches they're considering, have completed, or are currently a part of.
  * In order to send a direct message a user will navigate to the Direct Messages button on the site. They will only be able to do this if they are signed into their account. Then, they will click the Direct Message button and be taken to the Direct Message page where a list of previous messages are stored. They can choose to send a new message or reply using a message thread already listed. 
  * Actors: User
  * BR3
* **UC7** Create pitch pages.
  * Creating pitch pages is an important part of the software because it is how the founders will advertise to potential investors or developers for their project. The pitch page hosts the information that will attract these users to the project. It's also the place that describes what the project is intended to be. 
  * To create a pitch page a founder will navigate to the button on the home page that says "Create Pitch". This will redirect them to the pitch creation page. Here, they'll have to enter the name of their pitch, details, and keywords for others to be able to find it. 
  * Actors: Founder
  * BR3

* **UC8** Interchange between user roles.
  * Interchanging between user roles is an important use case because users may have to switch between different roles. For example, a founder for a project may be a developer on another project and/or on the same project. Users need to be able to switch between roles so they can take on the different roles that are required of them per project.
  * Interchanging between user roles is fluid between it exists in the back-end to dictate functionality. The user is given the roles based on the tasks they perform. For example, if they click the Create Pitch tab they would then go through that process as a founder.
  * Actors: User
  * BR4

* **UC9** Hold investor payments.
  * This use case is critical to the software. Holding investor payments is one of the most important tasks the software has since it serves as an intermediary between the different users. It keeps the investor payments safe so everyone is satisfied and the money goes to who its supposed to go to during or after the projects lifespan.
  * The investors give the money to the system and holds it until the system is told by the founder to disperse the money to the necessary parties.
  * Actors: System
  * BR5
* **UC10** Finish a given project.
  * This use case is necessary because the project should eventually be completed. Once the project is finished funds can be dispersed. The end goal of the project is to eventually reach this point.
  * In the project page the developer will find the "Finish" button within the project settings. Clicking it will finish the project.
  * Actors: Developer
  * BR5

* **UC11** Negotiate terms of a pitch.
  * The ability to negotiate terms is important because it lets the different users involved in the process come to an agreement on project details. Once the different users come to agreement the pitch is complete and the project can move forward. Without this functionality, the users would find it difficult to come to an appropriate agreement on individual terms for the pitch. One way they will be able to negotiate is through the direct message functionality.
  * To negotiate terms of a pitch the users will navigate to the direct messages page. Here, they can choose who to negotiate with by sending a message to them.
  * Actors: User
  * BR6
* **UC12** Observe associated parties with the pitch.
  * The investor or developers will want to be able to see the parties associated with certain pitches to make an educated decision on if they want to be involved with them. By being able to observe associated parties with the pitch the investor or developer can determine their overall quality and if they're worth being involved with based on the project. It could be someone the investor or developer has worked with before so they can make a decision based on their previous experience with them.
  * The investor or developer will navigate to the pitch page. While there, they'll be able to see a contribution list of who has contributed to the project. They can click on each contributor to navigate to their profile and see more information about them.
  * Actors: Investor, Developer
  * BR6

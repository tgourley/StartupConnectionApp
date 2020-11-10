# Functional Requirements

### [BR1](https://github.com/Cjbucker/StartupConnectionApp/blob/master/Design/BusinessRequirements.md)
* The user will have the ability to search by tags associated with pitches. [FR1 - LOW]
* The user will have the ability to search by pitch title. [FR2 - HIGH]
* The user will have the ability to search by user’s names. [FR3 - HIGH]
* Founders may set custom tags to categorize their pitches. [FR4 - MEDIUM]
* If the search terms described in a, b, and c are valid, then the system will display a list of predicted results associated with the terms. [FR5 - HIGH]
* Admins have the ability to filter out vulgar projects. [FR6 - LOW]
* Admins have the ability to filter out or disable vulgar tags [FR7 - LOW]

### [BR2](https://github.com/Cjbucker/StartupConnectionApp/blob/master/Design/BusinessRequirements.md)
* The system will generate graphics based on pitch page traffic. [FR8 - MEDIUM]
* Project completion(s) of a user can be viewed from their user profile. [FR9 - HIGH]
* Admins will have the ability to verify pitch pages. [FR10 - MEDIUM]


### [BR3](https://github.com/Cjbucker/StartupConnectionApp/blob/master/Design/BusinessRequirements.md)
* The system will allow users to send direct messages to other users. [FR11 - HIGH]
* The user may add a subject when sending a direct message. [FR12 - LOW]
* The user may indicate their desired role for a pitch when sending a direct message. [FR13 - LOW]
* Users will have the ability to report other users for scam pitches. [FR14 - LOW]
* Users will have the ability to report other users for scam proposals. [FR15 - LOW]
* Admins will have the ability to review reports. [FR16 - LOW]

### [BR4](https://github.com/Cjbucker/StartupConnectionApp/blob/master/Design/BusinessRequirements.md)
* The user will switch to the founder role when creating a pitch page. [FR17 - HIGH]
* The user will switch to the investor role when funding a pitch. [FR18 - HIGH]
* The user will switch to the developer role when contributing to a pitch. [FR19 - HIGH]
* Admins will have the ability to disable user accounts [FR20 - LOW]


### [BR5](https://github.com/Cjbucker/StartupConnectionApp/blob/master/Design/BusinessRequirements.md)
* Once the pitch is complete, the admin will mark the pitch as complete [FR21 - MEDIUM]
* Once a pitch begins development, the admin will mark the pitch as in development. [FR22 - MEDIUM]
* When an pitch receives funds, the admin will mark the pitch as funded. [FR23 - LOW]
* The admin has the ability to distribute funds to pitches in development. [FR24 - MEDIUM]

### [BR6](https://github.com/Cjbucker/StartupConnectionApp/blob/master/Design/BusinessRequirements.md)
* Developers may negotiate terms of payment, based on their contributions to the pitch, with the founder. [FR25 - MEDIUM]
* Developers may negotiate, with the founder, the tech-stack used for a pitch. [FR26 - LOW]
* Founders have the ability to accept or decline investment proposals. [FR27 - HIGH]
* Founders have the ability to accept or decline development proposals. [FR28 - HIGH]

# Non-Functional Requirements

### [BR1](https://github.com/Cjbucker/StartupConnectionApp/blob/master/Design/BusinessRequirements.md)
* The search shall respond within 10 seconds of sending the request. [NR1 - LOW]

### [BR2](https://github.com/Cjbucker/StartupConnectionApp/blob/master/Design/BusinessRequirements.md)
* Graphics will be generated if 3 months of data is available. [NR2 - LOW]
* The front-end must be designed using the Slim Admin Template. [NR3 - HIGH]

### [BR3](https://github.com/Cjbucker/StartupConnectionApp/blob/master/Design/BusinessRequirements.md)
* A message will send within 5 minutes [NR4 - LOW]
* Messages should only be sent to valid users [NR5 - MEDIUM]

### [BR5](https://github.com/Cjbucker/StartupConnectionApp/blob/master/Design/BusinessRequirements.md)
* Payments will be received, by the developer and founder, within at most 5 business days from the completion of the project. [NR6 - MEDIUM]

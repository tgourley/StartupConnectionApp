# Functional Requirements

### [BR1](https://github.com/Cjbucker/StartupConnectionApp/blob/master/Design/BusinessRequirements.md)
* The user will have the ability to search by tags associated with pitches. [FR1 - LOW]
* The user will have the ability to search by pitch title. [FR2 - HIGH]
* The user will have the ability to search by user’s names. [FR3 - HIGH]
* Founders may set custom tags to categorize their pitches. [FR4 - MEDIUM]
* If the search terms described in a, b, and c are valid, then the system will display a list of predicted results associated with the terms. [FR5 - HIGH]

### [BR2](https://github.com/Cjbucker/StartupConnectionApp/blob/master/Design/BusinessRequirements.md)
* The system will generate graphics based on pitch page traffic. [FR6 - MEDIUM]
* Project completion(s) of a user can be viewed from their user profile. [FR7 - HIGH]

### [BR3](https://github.com/Cjbucker/StartupConnectionApp/blob/master/Design/BusinessRequirements.md)
* The system will allow users to send direct messages to other users. [FR8 - HIGH]
* The user may add a subject when sending a direct message. [FR9 - LOW]
* The user may indicate their desired role for a pitch when sending a direct message. [FR10 - LOW]

### [BR4](https://github.com/Cjbucker/StartupConnectionApp/blob/master/Design/BusinessRequirements.md)
* The user will switch to the founder role when creating a pitch page. [FR11 - HIGH]
* The user will switch to the investor role when funding a pitch. [FR12 - HIGH]
* The user will switch to the developer role when contributing to a pitch. [FR13 - HIGH]

### [BR5](https://github.com/Cjbucker/StartupConnectionApp/blob/master/Design/BusinessRequirements.md)
* Once the project is complete, the system will distribute the money to the developer. [FR14 - HIGH]
* Once the project is complete, the system will distribute the money to the founder. [FR15 - HIGH]
* Once the project is complete, the system will notify the investor. [FR16 - LOW]

### [BR6](https://github.com/Cjbucker/StartupConnectionApp/blob/master/Design/BusinessRequirements.md)
* Developers may negotiate terms of payment, based on their contributions to the pitch, with the founder. [FR17 - MEDIUM]
* Developers may negotiate, with the founder, the tech-stack used for a pitch. [FR18 - LOW]

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

## Recipe Shop
COMP 4350-A01 Group 9
### Team Members

| Name | Username in Github  |   email |
|------|---------------------|---------|
| Sachin Bhatt | SachinB0101 | bhatts1@myumanitoba.ca |  
| Meixuan Chen | njzfjiang   | chenm7@myumanitoba.ca  |
| Densson Zhu  | zhude2 | zhud2@myumanitoba.ca |
| Troy Thomas | TroyT21 | thomast9@myumanitoba.ca |
| Ifeanyi Ochiagha | Francis518 |ochiaghi@myumanitoba.ca|

### Overview

Recipe Shop is an online platform built for anyone who loves to cook or needs a hand in preparing meals. Recipe shop aims to provide convenience in the process of preparing meals and grocery shopping; and allows people of similar interests to find and share their favorite recipes.

### Vision Statement
Recipe Shop is a mobile and web based application that allows users to find recipes based on their specialized needs. The application relieves the user from the pain of having to google for recipes before each meal; and frustration when they find a recipe but did not have enough ingredients at home. With “Recipe Shop” they can simply enter the ingredients they have and have a list of recipes matching the ingredients. The main goal of Recipe Shop is to make the process of preparing meals and grocery shopping easier, and also provides a platform for recipe sharing and collecting.

### Project Proposal Powerpoint
[link for slides](https://docs.google.com/presentation/d/1PnpB_A33euk-62a8-xNr9aGnYFOGQPwSr7CioqUJycA/edit#slide=id.g3003bf0c524_0_5)


### Key features
1.  Users can create account to view and manage recipes
    
2.  The app suggest recipes based on user's input of ingredients and cooking methods
    
3.  Users can generate grocery list with their chose of recipes
    
4.  Users can search for recipes
    
5.  Registered users can upload original recipes to forum

**Non Functional**: The application can handle 20 Users sending 100 requests per minute.

### Key User Stories
(AC = Acceptance Criteria)
1. **As a user, be able to create account with valid username and password**
_AC: Given I am a new user to the application, when I am on the sign in page and I entered a valid username and password, when I click register, I can create a new account._


2. **As a user, be able to sign in to my account with correct username and password**
_AC: Given I am a registered user, when I am on the sign in page and I entered the correct username and password and clicked sign in, I will be signed in to the application._


3. **As a user, be able to search for recipes based on my preference**
_AC: Given I am a user, and I am on the main page of the application, when I put in filters and keywords in the search box, the application will provide me with a list of matching recipes to my criteria._


4. **As a user, be able to get a grocery list for the ingredients after selecting recipes**
_AC: Given I am a user, and I hit the generate grocery list button, after I selected recipes from my folder, a list of groceries that includes the recipe ingredients will be generated by the application._


5. **As a user, be able to save the grocery list for later use**
_AC: Given I am a user, after I generated a grocery list with selected recipes, I can save the list in the application so that I can view it later._


6. **As a user, be able to get a list of recipes matching to the ingredients I have and the cooking methods available to me**
_AC: Given I am a user, when I click the match recipe button and enter a list of ingredients and cooking methods, a list of recipes that contains only the ingredients I have will be generated._


7. **As a registered user, be able to upload my original recipes on to the forum**
_AC: Given I am a registered user, when I log in to the application and click the upload button, I can add text and images to create my own recipe, and upload it onto the forum for other users to view._


8. **As a registered user, be able to add & delete recipes to my favorites**
_AC: Given I am a user, I can select or unselect a favorite option on recipes to add or remove them from a list of my favorites that I can view._


### Initial Architecture
![Architecture Diagram](https://github.com/SachinB0101/COMP-4350/blob/main/Documentation/Architecture.jpg)

### Technology
**Front End**: React, Android Studio 

**API**: Express.js, Edamam

**Database**: MongoDB

**Server**: Python

**Code Management**: Github

We believe this architecture will work because it is the minimum viable solution for the application we want to deliver. Since we want to have a web-based application and a mobile application, we will have 2 different front-ends built by React and Android Studio and communicating to the back-end by 2 different APIs(one for the web application and one for the mobile version). Inside the back-end, we will have one server to handle requests from the front-end and talk to the database. Technology-wise, we chose React.js to build our front end because it is relatively easy to learn and is suitable for both web and mobile applications, also React.js is suitable for building interactive applications, which is closely associated with our app design for Recipe Shop. We chose to use python to build our server and Javascript to build our APIs because we are more familiar with the languages. Finally, for data storage and management, we chose MongoDB to create our database since we are only dealing with simple data of text and numbers for recipe objects and user accounts, comparatively, MongoDB has better performance over others. With this architecture and the technology choices we will be able to fulfill our requirements with a relatively simple design.


### Work Division

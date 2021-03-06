# Standup Notes 01 27 22

## What project do you want to do for P0?

Austin Ristau - Something involving healthcare, may default to the banking app.

Philip Wentworth - Character generation for tabletop roleplaying games.

Darrell Hamilton - Banking app.

Michael Bronzo - Banking app.

Hannah Hospital - Banking app, still considering an alternative.

Andrew Snyder - Banking app.

Josh Evans - Banking app.

## What do you want to get out of Revature Training?

Austin Ristau - Improve interviewing skills.

Philip Wentworth - Improve interviewing skills.

Darrell Hamilton - Improve interviewing skills, specifically learn how to interview well on zoom.

Michael Bronzo - Learning to code.

Hannah Hospital - Confidence with public speaking in front of large groups, interviewing skills.

Andrew Snyder - Improve technical skills.

Josh Evans - Interviewing.

# Standup Notes 01 28 22

## What project are you doing for P0?

Philip Wentworth - Character generation

Hannah Hospital - Course Registration

Darrell Hamilton - Banking Application

Michael Bronzo - Banking Application

Josh Evans - Banking Application

Austin Ristau - Healthcare Scheduling Application

 # Standup Notes 01 31 22
## Progress thus far

Philip Wentworth - finished utility package and models, currently working on services

Hannah Hospital - began brainstorming

Austin Ristau - began brainstorming

Michael Bronzo - began brainstorming

Josh Evans - prepared Menu classes for application

Darrell Hamilton - begain brainstorming

# Standup Notes 2/1/22
## Progress update 

Phillip Wentworth - Finished Exceptions and MyCharacterService, working on UserService and Menus.

Hannah Hospital - Brainstorming

Austin Ristau - Outlining and adding to-dos

Michael Bronzo - Set up and planning outline

Josh Evans - Working on menus/router

Darrell Hamilton - Brainstorming

# Standup Notes 2/2/22
## Progress update

Phillip Wentworth - working on UserService, Menus, and DAOs

Hannah Hospital - Creating outline for databases, classes, UI

Austin Ristau - Setup classes and databases

Michael Bronzo - Outlining classes and databases

Josh Evans - working on Menus, and migrating to Maven

Darrell Hamilton - Working on hashmap and implementing setting  up the bank assignment

# Standup Notes 2/3/22
## Progress update

Phillip Wentworth - finishing DAOs today. Next step is Menus, then Testing, then done!

Hannah Hospital - brainstorming DAO interface, UI, getting comfortable with SQL, and refining details to fit for user storie

Austin Ristau - Worked on reading and writing to the database

Michael Bronzo - Focusing on SQL and setting up DAOs

Josh Evans - Starting DAO, creating User model

Darrell Hamilton - Implementing setting  up the bank assignment

# Standup Notes 2/4/22
## Progress update

Philip Wentworth - features complete. Next steps are Testing with JUnit and Mokito, final step documentation.

Hannah Hospital - created structure for packages, created models, updated DAO, and cusoms collections

Austin Ristau - Should be finished with menus and working on services next

Michael Bronzo - working on connectiong to postgress sql servers

Josh Evans - Working on Services and DAO

Darrell Hamilton - Working on the on the service DAO

# Standup Notes 2/7/22
## Progress update

Philip Wentworth - P0 everything complete except unit testing. Test Suite objects built but need to write tests.

Hannah Hospital - Finished DAOS, refining all services, starting on Menus

Austin Ristau - Data persisting done just need to be able to update and then unit tests.

Michael Bronzo - Writing to database and outlining testing

Josh Evans - Working on DAO and Services, specifically writing to the database

Darrell Hamilton - Working on project testcase

# Standup Notes 2/8/22
## Progress update

Philip Wentworth - Finish test cases

Hannah Hospital - Updated all services, refining menus

Austin Ristau -  Double checking all functionality then working on tests

Michael Bronzo - finish functionality and testing

Josh Evans - DAO and Services for user bank account, unit testing on service layer

Darrell Hamilton - working on testing

# Standup Notes 2/9/22
## Project0 Reflection

Philip Wentworth - 
1. Everything went fairly well 
2. I could've asked for help to get JUnit working earlier, I spent more time than necessary troubleshooting it
3. If I'm stuck on something for longer than an hour I'll ask if anyone else has encountered and already solved the problem I'm dealing with

Hannah Hospital - 
1. What went right? 
I was able to (mostly)successfully create all of my menus and I had most of the required functionality for students and faculty. I was also able to successfully persist the data into tables of my database.

2.What could I improve upon?
I could have implemented tests for both FacultyService and StudentService. I had difficulty successfully writing test methods. I could also have better planned my blueprint for starting p0. I didn???t spend enough time truly planning out the flow of the application, and it was reflected in my implementation.

3.Going forward what steps are you going to take?
I would put more emphasis on the planning phase of SDLC. I think I might utilize Kansan boards next time. 
I also spend far too much time creating useless functionality in my services and DAOS. To improve the quality of this project, I will be getting rid of the unused functions in my DAOS and services, and I will also implement a method in the FacultyService, such that faculty members can directly view the available courses in the Registration Catalog. I would want my application to be more user friendly.


Austin Ristau -  
1 Everything that I put in functioned.
2 Work on more sound logic testing and flushing the project out
3 Create a sound plan, make a list and chip away at it.


Michael Bronzo - 
1) Got most of the functionality I needed
2) Leave myself more time so I could have had more time to finishing testing and add in other features
3) Start earlier and ask questions earlier


Josh Evans - 
1. All of the pieces came together really easily. I'm a little shocked I didn't have more trouble conecting my app to the sql database.
2. I think I would have ended up with a better functioning project if I had planned things better from the beginning.
3. Start planning early in the code wirting process.


Darrell Hamilton - Not Present

# Standup notes 2/11/2022
## p1 Discussions

Phil + Darrell: 
A feature is a service function, and a service function is considered complete when its test function runs without error.

Michael + Austin: 
A feature needs to be fully functionally and at least have most of the JDBC logic.

Hannah Hospital + Josh Evans:
Our definition of done is whenever a feature is completely functional, and the DAOs are able to return a booelan to the service layer, allowing us to know that the CRUD operations were successfully completed. 
Also, feature is a service function and it must run under test without any error.

# Standup Notes 2/14/2022
## P1 Status

Josh + Hannah: we are creating our tables for our P1 and creating the foreign key/primary key relationships. Almost have a fully completed ERD

Michael + Austin:ER diagram done. Working on code skeleton

Phil + Darrell: Created Microsoft SQL instance. Created database structure for P1. Added ERD to README.md. Created skeletons for most of the necessary source files.

# Standup Notes 2/15/2022
## P1 Status

Josh + Hannah: completed ERD

Austin and Michael:
Continuing to make class skeletons, need  to set up trello board and finish table layout

Phil + Darrell: Added DAO objects to git repo. Tweaked DB assign to maintain 3nf. Created Trello board.

# Standup Notes 2/16/2022
## P1 Status

Hannah Hospital & Josh Evans: completed all models, confirmed ERD, created empty classes for DAOs, Services, and Servlets.

Philip & Darrell: Working on UserService, UserServlet, JUnit tests for User POST GET PUT DELETE and meal order setup

Austin & Michael: Empty classes setup and all configuration done and tested connection

# Standup Notes 2/17/2022
## P1 Status

Phillip & Darrell: REST endpoints for User complete. JUnit tests for UserService complete. Still working on getting log4j to work.

Josh Evans & Hannah Hospital: working on hibernate annotations for the tables in each of the models, completed DAOs

Austin and Michael: Finish setting up empty classes and begin implementing

# Standup Notes 2/18/2022
## P1 Status

Phillip & Darrell:Finished REST calls and JUnit testss for all User objects. Now working on Wedding objects, then Asset objects


Josh Evans & Hannah Hospital: constructed a new ERD model and modified models to match it


Austin and Michael: Working on the servlets and daos


# Standup Notes 2/21/2022
## P1 Status

Phillip & Darrell: REST endpoints in place for everything except Meal selection. Working on a front end html interface.



Josh Evans & Hannah Hospital: created html pages for login and registration servlets



Austin and Michael: Finishing servlets then adding testing and logging.

# Standup Notes 2/22/2022
## P1 Status

Note taker: Philip

Philip & Darrell: Working on html front end, Menus are completed for servlets
Philip will study daily instead of only cramming on Sundays.

Josh Evans & Hannah Hospital
Created html files for login and registration. Updating the control flow of servlets to html files.

Things to improve on (Hannah): Spend 30 min a day reading notes and working on flashcards

Michael: Added functionality for services. Look at flashcards more

Austin: Working on unit testing and finishing business logic. 
Utilize breaks and extra time better to study flashcards and other resources

# Standup Notes 2/23/2022
## P1 Status

Josh Evans & Hannah Hospital: working on attendee dashboard and jsp, starting testing and logging.

Philip & Darrell: Still working on an HTML/JavaScript frontend.

Austin & Michael: Still finishing logging, testing and logic. Then attempt at caching.



# Standup Notes 2/24/2022
## P1 Status

Josh Evans & Hannah Hospital: making some adjustments to the attendee dash, testing and logging.

Philip & Darrell: Found a logging fix, applying it to all services. Have a partially complete user interface using React, will add as much functionality to that as possible.

Michael and Austin: Working on business logic and logging, will move on to testing next

# Standup Notes 2/28/2022

## P2 Proposal

Trial by Combat:

A character generation and dueling system for d20 enthuasiasts.

As a player I can register an account

As a player I can login with my account

As a logged in player I can:
- Create weapons
- Create armor
- Create potions
- Randomly generate a character
- Define a loadout
- Purchase items or a loadout for a character
- Allow a character to buy random items
- Create an entry on the challenge board with a selected character
- Browse the challenge board
- Send a character to an existing challenge, winner take all!

Models:
    Player
    Character
    Item
        Weapon
        Armor
        Potion
            Healing Potion
    Loadout (contains items)

# Standup Notes 3/2/022

## P2 Status

Make sure that operations on one object do not make changes to related objects
example: Avatar REST calls should never make changes to Player objects
example: Weapon/Armor/HealingPotion/Loadout REST calls should not make changes to Avatar objects except as part of a ChallengeAction operation
etc
- [ ] /object/all GET
-get all objects of this type
- [ ] /object/?id=1 GET
-get object by id
- [ ] /object/?id=1 DELETE
-delete object by id
- [ ] /object PUT POST
-id is included in JSON
- [ ] /object/relationship/?id=1
-get objects with relationship object by id, example /avatar/player/1 get all avatars with player id of 1

Gurman: Working on Armor

Tracy: Working on HealingPotion

Michael: Working on Weapon

Josh: Working on Loadout and LoadoutItem

Phil: Working on Player and Avatar

# Standup Notes 3/3/2022

## P2 Status

Gurman: Finished Service and DAO layers for armor, in the process of implementing test suite and servlet layers

Michael: Finished Weapon DAO/service/servlet and set up testing

Phil: Finished Player, Avatar, AvatarItem, working on ChallengeAction

Josh: Finished Loadout, working on testing endpoints for Loadout and creating LoadoutItem DAO/Service/Servlet/Test

Tracy: finishing up healing potion and testing rest endpoints

# Standup Notes 3/4/2022

## P2 Status

Gurman: Implementing Armor DAO and Service layers

Michael: Working on adding postman requests for challenge and weapon

Phil: Completed ChallengeItem. Now working on Auth system.

Josh: Completed Loadout Item, working on UI design document (React/Material UI)

Tracy: Completed the healing potion api. now working on CI/CD Pipeline.

# Standup Notes 3/7/2022

## P2 Status

Gurman: Implemented and testing the logging aspect

Michael: working on Test ErrorExceptionAspect

Phil: finished auth system, added some validation to Player, working on React UI

Josh: Connecting login page to auth endpoint

Tracy: Still working on CI/CD pipeline

# Standup Notes 3/8/2022

## P2 Status

Gurman: Ran into some issues with logging, worked on debugging but also looking into alternatives

Michael: Finished errorExceptionAspect, starting to work on UI

Phil: created registration component for react ui, working on user dashboard

Josh: Getting AvatarList Component to display on login

Tracy: Still working on ci/cd pipeline.

# Standup Notes 3/9/2022

## P2 Status

Gurman: -Finished armor pricing changes and tested the endpoint/merged -Finished armor form ui layer, currently testing and will merge when it appears functional 

Michael: defining a loadout 

Phil: -Finished creating ChallengeBoard component to list all challenges -Working on UserDashboard and functionality to create a challenge 

Josh: Getting Player Avatar List to display on login

Tracy: Still working on ci/cd pipeline.

# Standup Notes 3/14/2022

## P2 Retrospective/P3 Preferences

Overall communication was excellent. Everyone had a slice of the backend and got to work on every layer of it. Live coding pieces of the front end was very helpful for the team. Trello board was really helpful, we always knew who was working on what.

In retrospect, it's very important to let the team know when you are stuck and have made no progress, and we would've benefited greatly by visually designing the UI before we started working on it.

Gurman - Preferences: Front-end because it's a weak point for me. Testing because I think its one of my strengths, making sure we have high coverage and implementing verbose tests for endpoints etc. Nothing that I'm against getting placed into if those 2 preferences don't pan out.

Josh - Slightly prefer front-end or research.
Overall can go anywhere needed.

Michael - Open to do anything, interested in learning more about  front end

Phil - prefer security or bonus features

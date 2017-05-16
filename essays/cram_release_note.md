---
layout: essay
type: essay
published: true
title: CRAM Release Note
date: 2017-05-15
labels:
  - Web Development
  - Meteor
  - Mongo DB
  - Javascript
  - CSS
---

This is a first release note for continuing work on an app, called CRAM.  I was assigned to a group of four students to work on CRAM.  However, I am and will be working on this project by myself this semester to improve CRAM. For more information about CRAM, visit [here](https://cram-colleague.github.io)

## Release Dates
* <a href="#5-15-2017">May 15, 2017</a>
* <a href="#5-1-2017">May 1, 2017</a>
* <a href="#4-15-2017">April 15, 2017</a>
* <a href="#4-1-2017">April 1, 2017</a>
* <a href="#3-15-2017">March 15, 2017</a>
* <a href="#3-1-2017">March 1, 2017</a>
* <a href="#2-15-2017">February 15, 2017</a>
* <a href="#2-1-2017">February 1, 2017</a>
* <a href="#1-15-2017">January 15, 2017</a>



<div id="5-1-2017"></div>
   
## May 1, 2017

## What I Worked On 

Last two weeks, I was working on deployment for the cram and on updating the cram home page.



* Deployment: I created the account on Meteor and deployed the cram on the galaxy.  In order to deploy on the galaxy, first I needed the database, so I created one for the cram on sandbox Mongo DB.  After having a database for the app, I can create or update settings file for Galaxy.
* Cram Homepage: I updated cram homepage so that all the information and photos are up to date.  Some functionalities are the same yet the design changed, so I needed to update most photos.  Also, new functionalities such as calendar are added to the user guide.



## The Obstacles

The obstacle that I faced was errors when I deployed onto the galaxy.  It keeps giving me an error when I start the app so I would need to stop running and change it some part.  I would still need to figure out the error to run my app on the galaxy correctly.

Also, in the user guide, I should not have all the photos of functionalities but choose which information would be helping the users and/or be attracted to them.  


## What I Plan To Accomplish

What I plan to accomplish for next milestone (May 15) is:  



For the next two weeks, I would like to continue working on improving the cram page that interviewer might take a look.




* Deploy on Galaxy: I will continue working on deployment and make it function on the galaxy.
* Fix Bugs: I will find major bugs that pop up during the deployment and fix important bugs.





<div id="4-15-2017"></div>
   
## April 15, 2017

## What I Worked On 

Last two weeks, I was working on adjusting study sessions and related pages.



Here are main functions that I worked on the last two weeks:



* Study Session: On the last release, I was struggling with adding sensei or student through this page, but I was able to figure out.  There will be up to one teacher for each study session, and if a study session is created by a person who wants to be taught, the user can choose to be a teacher for the study session.
* Create Study Session: Users can create a study session when they want to teach or when they want to be taught.  There is a selection that they can choose either a teacher or student.  It will pass the id of the user and on the study session page, it would look for the id and print out the name.
* Edit Study Session: As I added an option to be a teacher or student to the create study session page, I implemented the same option to the edit study session page.
* User Schedule: Due to the change in the option of being a teacher and a student, the function to look for which the users are in had to be changed.  It needed to be searched by the id of the users.



## The Obstacles

The obstacle that I faced was figuring out how the one change affects the others.  At first, I was not noticing that I would need to change the user schedule page.  However, when I checked each page, I found that it was not showing the results.

Also, I was going to have some user tests.  Therefore, I needed to spend some time searching for what is the good way to test my app.  It suggested that it would be better to have well function mockup pages, about 5 to 7 testers of the app, a well-planed test plan that would take about 30 min of the participants’ time.  I just searched but not able to get the test plan yet.


## What I Plan To Accomplish

What I plan to accomplish for next milestone (May 1) is:  



For the next two weeks, I would like to work on improving the cram page that interviewer might take a look.



* Cram home page: I will make the cram home page as up to date with screenshots of working systems or pages with some realistic data.
* Deploy on Galaxy: I would try to build the cram on the galaxy and make it functions on brows.
* Fix Bugs: during the deployment, I will find major bugs that pop up and fix important bugs.





<div id="4-1-2017"></div>
   
## April 1, 2017

## What I Worked On 

Last two weeks, I was working on fixing the tutorial pages and study session pages.



Here are two main functions that I worked on the last two weeks:



* Create Study (Tutorial): I adjusted the tutorial page for creating new study session as I updated the actual creating page with input date and time and options for class, start and end time.  The user can see the exact options that are the same as the actual page.
* User Page (Tutorial): Since there are three pages for the user page, schedule, message and report, I created tutorial pages for each page.  I also added fake schedule and message so that it would be easier for users to refer to.  Because there is a tab menu on the user page, the user tutorial page also has the same tab menu and it leads to each section’s tutorial page.  There is a button to go to the actual page of the tutorial for each page as well.  It also has a fake notification in the tutorial page.
* Study Session: I updated the output for the teacher of study sessions.  It searched the owner (created) of the study session before, but I updated to check the first and last name of the teacher and print the name and its link.



## The Obstacles

The obstacle that I faced was making the teacher type array and making the option to be a teacher or student when users create a study session.  I was going to have a checkbox for it, but couldn’t figure out how to get the value by checkbox and failed to create the if statement in the function.  Also, when I was creating the tutorial page for the report, I had difficulties printing out the correct ui semantics.  I needed to redo the whole thing and it worked. 



## What I Plan To Accomplish

What I plan to accomplish for next milestone (April 15) is:  



For the next two weeks, I would like to work on allowing the user to choose being teacher or student.  I would need to figure out how to separate them.  Also, I will start planning for the user test


  
* Create Study Session: I would allow the user to choose whether they want to be a teacher of study session or students.  Now, the user can only be a teacher for the study session.
* Study Session Page: Since I allowed the user to create a study session as a student, I would need to add a button to be a teacher for the already created study sessions.
* User Test: I will start planning how to do the user test.





<div id="3-15-2017"></div>
   
## March 15, 2017

## What I Worked On 

Last two weeks, I was working on fixing the design of menu bar, admin page and user profile page.



Here are two main functions that I worked on the last two weeks:



* Menu Bar: I changed the order of menus and added icons for each menu instead of just having words.  I was looking other sites and found out that most sites have a menu section to go to the profile page on the right side of the menu bar.  Therefore, I moved it around and put the profile section and logout button on the right side.  In addition, there would be the username under the user icon on the section. I also used a drop down function to clean the header.
* Admin Page: There was only one page for the admin page and containing tables of profiles, study sessions, and the reports from the users.  However, it would look bad if there are many users and study sessions.  So I created each page for each section, profiles, study sessions and reports so that the admin will have an easier time monitoring those.  For a study session table, it displays in the order of oldest to newest and only admin can see the past sessions.
* User Page: User page had a profile, study sessions that the user assigned.  And the message page was not connected with the user profile page.  I changed it to displaying the profile picture on the left top and a simple welcome message on the side of it.  There is also a menu bar for selecting schedule, message or report.  These parts will stay whenever page a user goes within the user-only page.  When it is on the user's schedule page, it shows whether the user is a teacher or a student for the specific section, and has date and time, so that the user can prepare if they need to teach or just think about the questions that they have.


## The Obstacles

The obstacle that I faced was finding right ui semantic that I can use and adjust pages.  There were a lot of copy and paste, but I had many places to revise small details.  Also, it took time for me to figure out making the limitation on the menu bar for non-user.  It wasn't displaying correctly at first.



## What I Plan To Accomplish

What I plan to accomplish for next milestone (April 1) is:  



For the next two weeks, I would like to spend my time changing the tutoerial pages based on the past modification.



* Tutorial Page: I will need to change the tutorial for the user page and for creating new study sessions.  
* Create Study Session: I would allow the user to choose whether they want to be a teacher of study session or students.  Now, the user can only be a teacher for the study session.
* Study Session Page: Since I allowed the user to create a study session as a student, I would need to add a button to be a teacher for the already created study sessions.





<div id="3-1-2017"></div>
   
## March 1, 2017

## What I Worked On 

Last two weeks, I was working on figuring out the calendar system and on implementing reply function for the message.  During the process of fixing the calendar system, I needed to update the pages for the study session as well.



Here are two main functions that I worked on the last two weeks:



* Calendar Function: Finally it is working with the help from [Chad Morita](http://www.chadmorita.com).  Now it displays the study session on the calendar and when users click some date, the add study session page pops up and the user can create the study session.  Also, when the user clicks the study session, it brings the user to the detail of the study session.  The calendar system was not working because of the input date was not the format that the calendar function could read.
* Add Study Session Page: Due to the implementation of the calendar system, I made the options for the name of the courses and the time frame for the study session.  Also, the date is only taken from the calendar when the user clicks the date.  Since the time should be displayed in the form of am and pm, there is different objects for the value of the time and the text string of the time for both start and end time.
* Edit Study Session Page: It is almost the same change happened as the add study session page.  There is a selection for the name of the courses, the start time and the end time.  Since this page's purpose is to "edit," the value is already set, yet the user can change of course.  Also, the edit study session page allows the users to change the date as well.
* Study Session Pages: It displays the time frame for the study session in the form of yyyy-MM-dd hh:mm ~ hh:mm.  Also, if there is maximum number of students in the session, going button will be not shown.
* List of Study Session: It will display the study sessions in the order of the closest event.  Also, it will not display the past study session.
* Messaenger Function: I added a reply function. When the user gets a mail and open the message, there is a reply button on the right corner and when the user presses it, it will go to add message page(creating the message).  When the user clicks the reply button, the program will send the id of the sender to the add message page so that the id will be implemented to the receiver.
* Sent Mail Page: I created sent mail page so that the user can see the messages that they sent and to whom.  This page will be accessed from the list of message page(inbox). Between inbox and sent mail pages, it can go back and forth.  The messages are sorted from newest messages to the oldest.



## The Obstacles

The obstacle that I faced was when I change the collection of a study session, I would need to change everything that uses that collection.  Automatically, it means that I would need to fix the add study session page, the edit study session page, and the study session page.  I took a time to figuring out what I needed to change and I spent a lot of time to test my function but adding some study sessions, deleting it and so on.



## What I Plan To Accomplish

What I plan to accomplish for next milestone (March 15) is:  



For the next two weeks, I would like to spend my time changing out the design of the pages.



* Menu bar: changing out the layout and the order of it
* Admin Page: changing the layout similar to the list of message and sent mail page. Being able to switch back and forth on the same page
* User Page: changing out the layout of the user page as well. Making the page easier to see study session and message page.  I would need to make the separate page for each section.





<div id="2-15-2017"></div>
   
## February 15, 2017

## What I Worked On 

Past two weeks, I was going to continue working on calendar functionality and on fixing a collection of a study session.  I still had a difficult time implementing fullcalendar and connect to the meteor collection. 



Here are two main functions that I worked on the last two weeks:



* Message Function: I added message functionality on CRAM.  From each profile, users can send a mail to the person.  There is an orange button on the right corner.  What the program does is that taking the unique id of the profile and storing in the collection as a receiver.  Also, it will get the meteor user id and store it as a sender.  There is also the title and content section in the message collection.  Each user has a mailbox page that contains all the messages that they got from other users.  The messages are projected in a table with the name of the sender, title, content and view button.  In the content section, it will only show first couple words.  When the user gets the message, there will be a label on the header since I added another category to the profile collection to check if the message is sent or not.  There is a function called when the user sent the message.  When the user clicks to the view, it goes to a message page and project all the content.  There are delete and back buttons.
* Study Session Pages: I allowed maximum five students to attend each study session.  I changed the type of student to an array instead of a string.
* Add Study Session Page: Unifying the name of the courses when the user creates a study session so that in the future when there is a search function, it is easier to search.
* Calendar Page: Fixed some script and the study session could be added from the calendar, but not showing into the calendar.



## The Obstacles

The obstacle that I faced was still figuring out how to connect the collection of a study session to calendar system.  I found out that time setting for the study session causes the calendar not to show the schedule for the study session.  I would need to restrict the input of the time and change some categories to the collection of the study session.  Because there is a study collection before implementing the fullcalendar, it makes the implementation hard to adjust for the study session.



## What I Plan To Accomplish

What I plan to accomplish for next milestone (March 1) is:  



* Revising Calendar Functionality: I am still working on calendar system.  I was able to add study session from the calendar page, yet it was not showing up on the calendar.  Therefore, I need to find out how to show up on the calendar.  In addition, I will need to add an option to choose the time.
* Upgrading Message Function: It should have a reply button and functionality when they open the message.  If I change the receiver's and sender's id, it would be different from the regular message, so might need to have a separate collection and page.
* Fixing Study Session Page: I should not show the going button when the enrollment for the study session is full.  I will have a function to check the number of the "students" in the study session and if there is maximum number, it will show it is full.





<div id="2-1-2017"></div>
   
## February 1, 2017

## What I Worked On 

Past two weeks, I was going to implement calendar and notification systems.  I looked several calendar function that I could use and was able to implement fullcalendar to the app.  However, I was not able to connect a collection of study sessions and the calendar system.  I found that would need to fix time of the calendar and figure out how to produce the date on the create study session page.



Here are two main functions that I worked on the last two weeks:



* Notification System: I implemented the notification system that would be shown on the user home page.  When a new profile or new study session is created, there will be a notification button on the top of the user home page.  When a user clicks the button, a message will pop up on the top right corner saying that new profile is added or new study session is added.  Also, the colors for each notification would be different, so that the user will be able to tell if a new user is added or new study session is created.
* Tutorial Pages: I created tutorial pages so that the users will easily find out how to use this app.  When the user first login to the app, he/she can choose if they want to create a profile page or see tutorials.  There are tutorials for the user page, create a profile page, create a study session page, the session page, and add a report page.  Each of those pages, there in template information shown on the page and details of how to use and to see the page in purple boxes.  There are pointing hands that the user can go to previous or next tutorial page.  Also, if the user wants to go to the actual page, there is a button for that too.  After the user creates the profile, he/she can still go to the tutorial page if they need.  Each page that has tutorial has a button to click to go to the tutorial page.



## The Obstacles

The obstacle that I faced was figuring out how to connect the collection of a study session to calendar system.  I think I would need to recreate the collection of the study session in MongoDB.  While searching for how to do the implementation of those functions, most of the information I found was based on PHP, jQuery or other things.  Therefore, I would need to translate and think how to apply that information to meteor or MongoDB collection.

Also, When I apply an open source to the app, I need to spend a lot of time to figure out the functions that it has, what parameters that the function takes and so on.  For calendar and notification systems, I implemented the open source and spent hours to find out what does what.  



## What I Plan To Accomplish

What I plan to accomplish for next milestone (February 15) is:  



* Revising Calendar Functionality: I am still working on calendar system.  I would like calendar function to connect with a study session and being able to create and delete the study session from the calendar page.  I was able to add study session from the calendar page, yet it was not showing up on the calendar.  Therefore, I need to find out how to show up on the calendar. In addition, when the user adds the study session, there is no functionality to decide the time range of the study session, so I would need to implement it as well while I change the time of the calendar to Hawaii time.
* Edit A Collection Of Sessions: I would need to allow multiple users or limited amount of students to join a study session.  For now, there is only one person can join since the student category can only store a string. I will change it to list of string so that multiple students will be stored.  After that, I will have a functionality to check the number of strings stored in a student in the collection of sessions and limit it to five students.





<div id="1-15-2017"></div>

## January 15, 2017

## What I Worked On 

Past week, I looked back what my teammates and I have done so far and listed what I would need to do from now on.  There were some functionalities that were not working correctly, and also where I would need to change majorly.  I listed several issues that I would need to work on for the next couple of weeks.  
Since there were only five days till milestone 1, I fixed small issues.



* Study Session: There was a going button so that when users click it, it would add the user as a participant of a study session. However, it was showing although the users had not created a profile. Therefore, I edited not to show the going button when the users haven't created the profile.  
* Admin Page: Admin page contains the information of profile, study session and report. When there was no profile, the admin page only said that no profile has been created yet.  But there was a possibility that there would be no profile yet have a report from previous users, so I decided to have each section there on the page even though there is no profile.  
* Profile Page: There was a feedback from last semester says that the fonts of the name of users should be larger on the profile page.  I made bigger and change the position of the name to be displayed so that it would be easier to see the name.  
* List Of Profiles: When I checked each page in CRAM for various situatuion, such as when there are profiles and study sessions, when there are profiles but no study session and when there is no profile.  I noticed when there is no profile, the list of profiles page didn't say anything about it.  So, I added some description saying that there is no profile and the viewer of the page should create one :)

## The Obstacles

The obstacle that I faced was determining how long I would take to accomplish each issue.  There was not much time for this milestone, but I needed to start working something.  I decided to work on small things first and to fix minor issues that were left from last semester.  
Also, as I looked through the app, I found several places where I needed to fix and where I should have implemented.  I haven't look at the app from last semester and I needed to bring back my memory, yet it actually helped me to have a perspective of a third person to the app.

## What I Plan To Accomplish

What I plan to accomplish for next milestone (February 1) is:  



* Revising Calendar Functionality: There is a simple calendar functionality in CRAM, but it needs to fix because it is not connecting to the study session yet.  I will need to research about it and implement to CRAM since I wasn't in charge of this functionality last semester.  I would like calendar function to connect with a study session and being able to create and delete the study session.  The design of the calendar page is needed to change as well.  
* Notification System: There was a feedback about new functionality that users would like to have and that was notification system.  The users would want to be notified when new profile or new study session are created, or when there is a change in the study session that they are in.  Also, if the users is a teacher of the study session, they would like to have a notification when new students added to their sessions.  



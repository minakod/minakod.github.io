---
layout: essay
type: essay
published: true
title: CRAM Release Note3
date: 2017-02-15
labels:
  - Web Development
  - Meteor
  - Mongo DB
  - Javascript
  - CSS
---

This is a second release note for continuing work on an app, called CRAM.  I was assigned to a group of four students to work on CRAM.  However, I am and will be working on this project by myself this semester to improve CRAM. For more information about CRAM, visit [here](https://cram-colleague.github.io)



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


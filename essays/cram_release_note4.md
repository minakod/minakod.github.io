---
layout: essay
type: essay
published: true
title: CRAM Release Note4
date: 2017-03-01
labels:
  - Web Development
  - Meteor
  - Mongo DB
  - Javascript
  - CSS
---

This is a forth release note for continuing work on an app, called CRAM.  I was assigned to a group of four students to work on CRAM.  However, I am and will be working on this project by myself this semester to improve CRAM. For more information about CRAM, visit [here](https://cram-colleague.github.io)



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


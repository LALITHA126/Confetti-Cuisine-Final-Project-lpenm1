# Confetti-Cuisine-Final-Project-lpenm1
> CSCI-6655-02 Web database Appl Development Final project task-3
## PART-1
## Contents:
- About the Website
- new added added/updated pages
- changes made
- extra credits
## About the Website:
**confetti-cuisine** Is the The application code this application found in our primary textbook, Get Programming with Node.js, as the Capstone 
project found in Lesson 37 in Unit 8 in the 'finish' folder. 
-The main purpose of  semester's final project is to use this program as a starting point and modify/improve it in a variety of ways.
In this confetti cuisine we have expanded site's capabilities to include "cuisine-based culinary vacations" which revolve around learning to cook various food styles 
by vacationing while attending cooking classes hosted by well-known local chefs, both in the US and abroad.
-client interface for these new offerings should look like and function pretty much exactly like the current setup for the local course offerings 
which already exist. There should be a parallel set of vacation package views, routes, API endpoints, and a Mongoose schema model just as with the local courses.

![alt text]
## New added/updated pages:
> This project has different pages such as
> 1. Home Page
> 2. Courses Page(given in unit 8)
> 3. NEW: "Culinary Vacations" (newley added for enhancement)
> 4. Contact Page (given in unit 8)
> 5. Users(given in unit 8)
> 6. Latest courses.(given in unit 8)
In every page there is a header which shows the title of the website, home , courses , culinary vacations , contact page , users and latest courses. A navigation bar which shows  the five different pages with their categories.
**Home page contains** 
-the details of the product, productpage contains all the details of the products with prices, about pages has the details of the website and contact page has the additional information.
-Added a new button to the main navbar with the title "NEW: "Culinary Vacations" to the current home page. I also put an image and some text to the home page with a description of this new feature. This new button will send you to a new page with vacation packages.
**NEW: "Culinary Vacations**
- Here are the new/updated pages:a website where you can describe a new culinThese are exact replicas of the course's functionality. 
- To make these web pages operate properly, you'll need to construct the new vacationSchema Mongoose model for the MongoDB holiday collection, update the app's related route handling, edit its respective controller, and, of course, develop the new EJS view templates that correspond to the new pages.ary holiday package,a website that shows a list of all the packages that are currently available, a page that displays the specifics of a specific vacation and links to an editing page that allows you to completely delete the vacation package from the database and a page that allows you to alter the details of an existing holiday.
- To limit the choices a user can make when interacting with the forms, considered HTML form elements like select options, drop box, or the HTML data list tag. These would be particularly valuable in the fields of departure location and cuisine.
- supplied a "seed vacations.js" module based on the one that seeded the course collections from the textbook project It will erase all current documents from the vacations collection before executing the insertions each time you execute it with "node seed vacations."

**If we want to edit or remove the cuisine description, we must first log in.**

**courses** 
- added new button to Create New Culinary Vacation Package that takes to the edit page.
users and latest courses remain same.

## PART-2:
## extra credits : 
- To validate the departure and return dates, I used javascript. a return date will automatically follow the departure date. Validation is done in the browser using HTML form properties and JavaScript coding, Mongoose validation code.
- A logged-in user can create a new vacation package as well as change or delete an existing one. However, any user, whether authorized or not, can browse all of the current vacation postings. The interface has been updated so that only logged-in users may access the edit/delete pages. Only logged-in users can create and amend vacation descriptions, thanks to some new coding.

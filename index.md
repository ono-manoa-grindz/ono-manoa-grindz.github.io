<img src='/doc/page_banner.jpg'>

# Table of Contents
* Overview
* Approach
* Case Ideas
* Beyond the Basics
* Developer Guide
* User Guide
* Page Mockups
* Team Members

# Overview
Ono Manoa Grindz serves as the homepage for showcasing the vast variety of cuisines that is served here on the University of Hawaii - Manoa campus.  With a quick visit to our page, you will be able to view all the food service vendors along with user-submitted ratings that we hope will serve useful.

The problem: There are many food choices on campus: campus center, food trucks, Manoa Gardens, Paradise Palms, vending machines, and so forth. Let’s say you have a desire for chinese food today for lunch. What places on campus are serving chinese food menu items today? Alternatively, let’s say that you love the fresh salmon fillet at Campus Center, but that dish is only served once every few weeks. How do you find out on the day that it’s available?

The solution: The Ono Manoa Grindz enables you to login on your phone and determine:
What specific menu items will be available today at food locations in UH Manoa.

For Milestone 1, we created a basic foundation of our webpage. It consist of the landing page, navigation bar, restaurant list page, vendor home page, add vendor page, and adding a review page.

For Milestone 2, we created several issues that will help our functionality of our website and added more details to our GitHub webpage. We created and overview section, developer guide, and user guide to our GitHub webpage. We also added more functionality to our Add Review Page, filled the vendor database with default vendors, and created an option for admins to edit/delete vendors. Lastly, we added additonal documents to the MongoDB database, fixed our style and design of our website, and cleaned up the navigation bar.

### Project Links
* [Running Deployment](http://onomanoagrindz.meteorapp.com)
* [Github Project Board](https://github.com/ono-manoa-grindz/ono-manoa-grindz/projects)
* [Github Source Code](https://github.com/ono-manoa-grindz/ono-manoa-grindz)

# Approach
For this app, you will create a way to organize and present available menu items for all campus locations in a unified manner. There are three roles: Users, who can login to establish preferences for their food choices; Vendors, who can login to specify their choices of the day or otherwise modify their profile data; and Admins, who also can login to define users as having the vendor role and otherwise administer the system.

Your app should provide a consolidated, easy to use source directory of menu items taken from the UHM Food Vendors and Manoa Dining Services. In addition to organizing menus by vendor, you should also organize the data by menu item type (ethnicity, vegan, etc.).

Users should be able to indicate preferences and/or food types to exclude in their profile, which will help the app to present more useful choices.

For places with weekly or daily changing menus, vendors should be able to login to provide this data.

### Possible mockup pages:
* Landing page
* User home page
* Vendor home page
* Admin home page
* Add Vendor page
* User profile page
* Foods available right now page

# Case Ideas
Whether or not the following bullet points list all pages or not, the completed use case should show an end-to-end scenario of using the system.

* New user goes to landing page, logs in, gets home page, sets up profile. (How do they learn how system works?)
* Admin goes to landing page, logs in, gets home page, edits site.
* User goes to landing page, logs in, looks for food to buy.
* User is notified of daily menu items that match their preferences

# Beyond the Basics
After implementing the basic functionality, here are ideas for more advanced features:

* Automated updating of menu items from vendors. For example, they agree to post their daily specials via twitter, and your application retrieves their twitter feed and uses that data to update their page.
* Allow students to rate menu items.
* Integrated map functionality; note that some food trucks change their location over the course of a week.
* Provide feed of tweets from vendors (some vendors might use Twitter to advertise daily specials and locations.)

# Developer Guide (Installation)
Begin by [installing Meteor]( https://www.meteor.com/install).

Next [create a local copy of the source code from the following Github Repository](https://github.com/ono-manoa-grindz/ono-manoa-grindz).

After installing, cd into the app directory and install the required libraries with:

```
$ meteor npm install
```

Once the libraries are installed, you can run the application by invoking:

```
$ meteor npm run start
```

# User Guide
### Landing Page
<img src='/doc/userguide1.png'>After visiting our landing page, sign up and create and account to have full user privilege permission. Click Login -> Sign up located on the top right of the page.

### Sign in/Sign up Page
<img src='/doc/userguide2.png'>Here is what the sign in/sign up page looks like.

### User Landing Page
<img src='/doc/userguide3.png'>After signing in with your new account, the new landing page will look like this. You will see a new category under the navigation bar at the top. You can now view the vendors that are available to you.

### Vendor Page
<img src='/doc/userguide4.png'>Here is an overview of all the available vendors implemented into our website. In the future, users will be able to create their own appropriate reviews for each vendor on our website.

# Page Mockups
### Landing Page
<img src='/doc/Landing Page M1.png'>

### Add Review Page
<img src='/doc/Add Review M1.png'>

### Vendor Home Page
<img src='/doc/Vendor Home M1.png'>

### Vendor List
<img src='/doc/List Vendor M1.png'>

### Add Vendor Page
<img src='/doc/Add Vendor M1.png'>

# Project Milestones
### [Milestone 1](https://github.com/ono-manoa-grindz/ono-manoa-grindz/projects/1)
The purpose of Milestone 1 was to build the foundation of our website. We began building the landing page, navigation bar, restaurant list page, vendor home page, add vendor page, and adding a review page. After these were built, we deployed it to Galaxy. 

### [Milestone 2](https://github.com/ono-manoa-grindz/ono-manoa-grindz/projects/2)
The purpose of Milestone 2 was to improve our functionality of our navigation bar, restaurant list page, vendor home page, and add vendor page. We also added a few design changes to our website. After completing these tasks, we deployed our new webpage to Galaxy.

### [Milestone 3](https://github.com/ono-manoa-grindz/ono-manoa-grindz/projects/3)

# Team Members
* [Joshua Cruz](https://github.com/cruzjoshua)
* [Dennis Kim](https://github.com/shinsa2)
* [Ken Tung](https://github.com/ken-10)
* [Jason Yim](https://github.com/jygh98)

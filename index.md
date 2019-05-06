<img src='/doc/page_banner.jpg'>

# Table of Contents
* Overview
* Approach
* Case Ideas
* Beyond the Basics
* Community Feedback
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

For Milestone 3, our main goal was to improve Milestone 2's functionality. We implemented the vendor database from a credible source into our own database, improved the menu page and description page for each vendors, added a reviews database collection with an "Add review" form, implemented a search bar into our "List all vendors" home page, and we were able to render the top three rated restaurants into our landing page. We also cleaned up the footer to make it stick to the bottom of the page. Lastly, we improved our GitHub homepage.

### Project Links
* [Running Deployment](http://onomanoagrindz.meteorapp.com)
* [GitHub Homepage](https://ono-manoa-grindz.github.io)
* [GitHub Project Board](https://github.com/ono-manoa-grindz/ono-manoa-grindz/projects)
* [GitHub Source Code](https://github.com/ono-manoa-grindz/ono-manoa-grindz)

### Possible mockup pages:
* Landing page
* User home page
* Vendor home page
* Admin home page
* Add Vendor page
* User profile page
* Foods available right now page

# Community Feedback
With the help of our fellow colleagues and friends from outside of the field, we managed to receive feedback for our website. We have asked their consent to post their names on our homepage.

### Kristen Kim
*"Great website! I managed to find convenient food places in the UH Manoa Campus. I've always wanted to know what kind of food each vendor is serving."*


### Kevin Nguyen
*"My classes are always located near the Holmes building and I did not know that there were two food trucks alternating at different times! With this website, I was able to find each vendors' operating hours in UH Manoa."*


### Robert Lee
*"I do not usually purchase food on campus but when I do have a taco craving, there is a Taco truck located near Campus Center. The food truck's operating hours are 10:00 AM to 2:00 PM. Without this website, I wouldn't have satisfied my taco craving on that day. Other than that, Ono Manoa Grindz did a great job in implementing the review section of their website as is it very simple to use and navigate through."*


### Kenneth Mai
*"As a user of Ono Manoa Grindz, navigating through the website was fairly easy to understand. The entire concept of the website is similar with Yelp but with food places only on UH Manoa. I'd say they did a great job for this project assignment."*


### [Jacob Burke](https://github.com/jacobjkburke)
*"As an upcoming UX Designer at University of Washington, I can see visual improvement being added into this website however, this is still a great implementation of React/Meteor. Being born and raised in Manoa and always within the UH campus, I can't wait to use this website whenever I am visiting my parents back in Hawaii!"*


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
To get to our landing page, click [Running Deployment](http://onomanoagrindz.meteorapp.com). When you first get to the page, you will be greeted with the landing page shown below. The page will render the top three rated restaurants on this website.
<img src='/doc/newuserguide1.png'>

### Sign in/Sign up Page
Sign up with your existing account with the sign in page shown below.
<img src='/doc/newuserguide2.png'>

### Register your own account
If you do not have an account, press "Click here to register" to quickly sign up for an account. Register page is shown below.
<img src='/doc/newuserguide3.png'>

### User Landing Page
After signing in with your new account, the new landing page will look like this. You will see a new category under the navigation bar at the top. You can now view the vendors that are available to you.
<img src='/doc/newuserguide4.png'>

### Vendor Page
Here is an overview of all the available vendors implemented into our website.
<img src='/doc/newuserguide5.png'>

### Vendor Home Page
Users may now view the vendor's information and add their own review and stars to each vendors on the website. The ratings and reviews will be shown below the "Add review" form.
<img src='/doc/newuserguide6.png'>

### Admin Home Page
To become an admin, you must contact one of the project developers to be manually added as an "Admin" role for your account. If you are an admin, this is your new landing page.
<img src='/doc/newuserguide7.png'>

### Admin Add Vendor Page
Admins may add their own vendors of their own choice but for obivous reasons, they have to be located near, in, or within the UH campus.
<img src='/doc/newuserguide8.png'>

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

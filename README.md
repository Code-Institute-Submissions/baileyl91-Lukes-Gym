
# Luke's Gym Website

View the [live project here](https://baileyl91.github.io/Lukes-Gym/index.html)

This project was created as part of my Milestone Project 1 
with Code Insitute Web Application Development course.

Have decided to create a website for a made-up gym to 
demonstrate what I have learned in the course so far.

## User Experience (UX)

### User Stories

 - #### First time visitor goals:
    1. As a first time visitor, I want to be able to understand the main purpose of the site and learn more about the gym.
    2. As a first time visitor, I want to be able to easily navigate the website.
    3. As a first time visitor, I want to be able to find the contact information easily.
    4. As a first time visitor, I want to be able to find the location of the gym.
    5. As a first time visitor, I want to be able to see the opening times of the gym.
    6. As a first time visitor, I want to be able to find out what type of equipment they offer.    


- #### Returning visitor goals:
    1. As a returning visitor, I want to be able to find the membership prices.
    2. As a returning visitor, I want to be able to contact the gym with questions if needed.
    3. As a returning visitor, I want to be able to find the gym social media pages for any new information that has been posted.


### Design

**Color Scheme**

Have used two main colors in my website which are a dark navy blue for header and footers with an off white color for background and text.

**Typograpghy**

The main font I have used is the 'Roboto' for its clean minimal look, with sans-serif as a back up option if there was any problem with using the main font.

**Imagery**

I have chosen an image of the main area of the gym to display as a hero image to show the user what it looks like inside. Also have used images to show off equipment available in the gym as well as people having fun working out.

### Wireframes

* Home Page - [view](assets/wireframes/Home.png)
* Factility Page - [view](assets/wireframes/Facilities.png)
* Membership Page - [view](assets/wireframes/Membership.png) 
* Contact Us - [view](assets/wireframes/Contact.png)

## Features

There are a number of features that have been implemented into the website which are:
* Navbar to allow users to navigate the website.
* Footers to store contact information and social media links.
* Social Media links to connect users with gym social media pages.
* Contact Us form to allow users to ask any queries they may have.
* Embedded google map of the location of the gym.
* Responsive on all devices.

## Technology Used

**Language Used** 

* HTML5
* CSS3

**Frameworks, Libraries & Programs Used**

- [Bootstrap](https://getbootstrap.com/docs/4.6/getting-started/introduction/)
    * Used bootstrap version 4.6 to help with the structure of the project.
- [Google Font](https://fonts.google.com/)
    * The font Roboto was imported from Google Font.
- [Font Awesome](https://fontawesome.com/)
    * Used Font Awesome to get some social media icons to use in footer and icons to display information.
- [Gitpod](https://www.gitpod.io/)
    * Gitpod is the development environment used to develop the project.
- [GitHub](https://github.com/)
    * GitHub is used to host project code.
- [Balsamiq](https://balsamiq.com/)
    * This program was used to create wireframes of the website.
- [Google Developer Chrome Tools](https://developers.google.com/web/tools/chrome-devtools)
    * The developer tools were used to inspect elements of the page and debug any potential problems within the website.
- [Unsplash](https://unsplash.com/)
    * This website was used to get stock free images for the project.

## Testing

The testing was done by me and tested the following questions: 

* Are the navbar links working? 
    
    Yes
* Is the contact form working when correctly filled in?
    
    Yes

    ![](/assets/testing-images/form-success.png)
* Does it prompt the user to fill in the missing required field?
    
    Yes

    ![](/assets/testing-images/text-prompt.png)
* Does it prompt the user when the email field is filled in wrong?
    
    Yes

    ![](/assets/testing-images/email-prompt.png)
* Does social media links work when clicked on a link and taken to a new tab/window?
    
    Yes

The website have been tested in the following browsers to make sure it loading correctly and working:
* Chrome
* Safari
* Firefox

The website has tested on the following devices using Google Developer Tools, as I have only got access to iPhone 11.
* Samsung Galaxy S5
* Pixel 2
* iPad


### Lighthouse Report

Have tested the website using the Lighthouse via Google Developer Tools to test for its accessibility, SEO and best practice.

On desktop:

![](/assets/testing-images/desktop-lightroom.png)

On Mobile:

![](/assets/testing-images/mobile-lightroom.png)

### W3C Markup Validator Service

There were a couple of issues when tested using the markup validator.
The errors were based on the iframe element when implemented with Google Maps.
[Results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fbaileyl91.github.io%2FLukes-Gym%2Findex.html)

### W3C CSS Validator

There were few issues when tested using the CSS validator.
However I was not able to understand the issue as it seems to be in the bootstrap framework.
I have implemented the bootstrap v4.6 following the Bootstrap documentation. Therefore I did not understand why there were issues. It did not affect the website though.
[Results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fbaileyl91.github.io%2FLukes-Gym%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)



### Testing User Stories

* As a first time visitor, I want to be able to understand the main purpose of the site and learn more about the gym. 
    
    The website clearly displays that this a gym


* As a first time visitor, I want to be able to easily navigate the website.
    
    Tested on all navigation links to ensure that it was working, goes to the correct page and is easy to navigate.

* As a first time visitor, I want to be able to find the contact information easily.
    
    Scrolled down the home page, a user can see the contact information along with the address and map. There were also contact details in the footer and there is contact us page with a link in the navbar.

* As a first time visitor, I want to be able to find the location of the gym.
    
    Scrolled down the home page and the location is displayed clearly alongside a map.

* As a first time visitor, I want to be able to see the opening times of the gym.
    
    Scroll down the home page and the opening hours table is shown.

* As a first time visitor, I want to be able to find out what type of equipment they offer.
    
    Users can click on the facilities page via navbar and can find the equipment the gym offers.

* As a returning visitor, I want to be able to find the membership prices.
    
    Users can click on the membership page to find the prices.
	
* As a returning visitor, I want to be able to contact the gym with questions if needed.
    
    Users can click on the contact us page to fill in the form for any queries needed.

* As a returning visitor, I want to be able to find the gym social media pages for any new information that has been posted.
    
    When clicked on the social media icons, the links will open up in a new tab/window.

### Issues 

Throughout my development of the projects I had a couple of issues which I have tried to address.

First, I had a problem with the footer not sticking to the bottom.

![](/assets/testing-images/footer-problem.png) 

After searching through Google, found an article on FreeCodeCamp which had some potential issues.

[Found Here](https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/)

Following the advice in the article, it had the solution I needed to solve the issue.

Secondly, when the website is viewed on mobile, it creates a horizontal scroll.
In the screenshot below you can see the navbar ‘overhang’ the body of the page.
I was not able to solve this issue.

![](/assets/testing-images/overhang-mobile.png)

## Deployment 

### GitHub Pages

The project was deployed to GitHub Pages using the following steps

1.	Log in to GitHub and locate the GitHub Repository
2.	At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
3.	Scroll down the Settings page until you locate the "GitHub Pages" Section.
4.	Under "Source", click the dropdown called "None" and select "Master Branch".
5.	The page will automatically refresh.
6.	Scroll back down through the page to locate the now published site link in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes
 without affecting the original repository by using the following steps.

1.	Log in to GitHub and locate the GitHub Repository
2.	At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3.	You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1.	Log in to GitHub and locate the GitHub Repository
2.	Under the repository name, click "Clone or download".
3.	To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4.	Open Git Bash
5.	Change the current working directory to the location where you want the cloned directory to be made.
6.	Type git clone, and then paste the URL you copied in Step 3.
7.	Press Enter. Your local clone will be created.


## Credits

### Code

### Content

All the content was written by me. 

### Media

All the stock images used were found on [Unsplash](https://unsplash.com/)

### Acknowledgements

 Want to thank the Student Care and fellows students for the support. 
 Also the tremendous community on the Slack channel.
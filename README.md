# **MettUp-Galway**
The project was made a purpose for a milestone project for Code Institut.

MettUp-Galway website is a landing page for people who want to meet people, make friends, find support and explore their interests in IT .
The website targets people who are just starting their adventure with the IT industry.


Users of MettUp-Galway will be able to find information: 
- About to MettUp-Galway
- Ethos section
- Meeting times 
- Gallery of privies events 
- Contact form
- Social media links




## Features
- ### Navigation
	- In the left top corner of the page, we will find a MettUp-Galway that link to the home page
	- The rest of the links will be on the right each link Home, Gallery, Contact will open a page
	- The color and font of the navigation bar is contrasting with the background
	- Navbar shows us clearly the name MettUp-Galway and other information about the site in an easy and accessible way.
    - The navbar for mobile devices will  be slightly different



- ### Header
	- Hereder show us a name of MettUp-Galway  usig a colors : 
        gray background, yellow letters and underline
	- header tell us for MettUp-Galway it's for all of people from IT industry
	- Header provides easy to understand information about what the site and who MettUp-Galway it's for .
- ### About us section
	- This section contains the history and ethos of the creation  MettUp-Galway 
	- Section will give a new user a details about MettUp-Galway , what site offer they will explain what the participants of the meetings can offer

- ### Meetings
	- Section will display when and where its next ,meeting
- ### Gallery
	- Gallery will contains photos from old meetings
- ### The Contact form
	- Contact form will compile details of people interested in taking a part  in meetups
	- Form will collects users name, surname and  email address
- ### Footer
	- Footer will contains meila addres for contact also links as icons to Facebook , Instagram , Twitter ,
	
		
## Testing
    - The site was also manually checked:
            Navbar:
                1. After pressing the logo, the website referred me to the index of the website.
                2. After selecting Home on the navbar, site sent me to the index page.
                3. After clicking Gallery, the page sent me to the gallery page.
                4. After hitting the contact page, Navbar sent me to the contact page.

            Index:
                1. The photo has appeared on the website and is visible while changing the resolution of the screen.
                2. Ethos section is visible and readable font size changes while changing the resolution.
                3. About cards that have hover animation on devices with large screens and animation is turned off on the mobile device, card layout changes as resolution changes.
                4. Meetings are valid and their schedule changes with the change of screen resolution.
                5. The footer of the link works and takes you to the correct pages, the size of the icon changes as the resolution changes.

            Gallery:
                - The photos change the position along with the change of resolution.

            Contact:
                1. The layout of the form changes with the change of resolution.
                2. All fields of the form are required.
                3. After filling in all the fields, the form sends the user to the thank-you pages

	- The site was tested on various browsers such as chrome, firefox, safari and Microsoft Edge
	- Site was tested by  google lighthouse  (Adding a scoring from lighthouse) , 
	- Existing code HTML , CSS was validated by W3C HTML and W3C CSS. [Pictures of validation report]



## Bugs
	During manual testing, I found the following bugs:
    1. Missing navigation bar between resolution 767-992px, bug has been fixed by adding missing class to css codes.
    2. The contact form is not always sent to the thank you page, the error was fixed by changing the action in the form code.
    3. The footer does not stick to the bottom of the page on devices with a small screen, the bug was fixed by dissolving a single div in the meetings section.
		
## Deployment
This page was deployed to GitHUb pages with the following steps:

    1.Log in to GitHub
    2.Assuming you have cloned or forked the repository, go on the "Settings" link for this repository
    3.Click on the "Pages" link on the left hand side of the page
    4.Under "Source" select "Deploy from branch" from the dropdown
    5.Under "Branch" select "main" from the dropdown
    6.Click "Save" which will then refresh the page
    7.It might take a few mins before you can refresh and view the link to the site published

## Credits    
- ### Media
	- The photos were used from the site [Pexels](https://www.pexels.com/)
    - Cards in the about section [Codepen](https://codepen.io/abhishek747/pen/BbWKVa)
- ### Content

    The entire content of this page was written by Alan Zimny.
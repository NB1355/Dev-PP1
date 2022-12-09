# MOUNTAINEERING GLOBAL 
## [Phase-I]  

[Visit the Live Project here](https://nb1355.github.io/projects-c001-prd/)

This website is developing in parallel to forming a new business idea that combines mountaineering and 
professional photography services for the experts who interested in crossing over to the other domain. 
Using only HTML 5 and CSS 3 is the first choice to get a static responsive website running fas

![text](/assets/images/readme/devices.jpg)


# Table of Content
xxxxxxxxxxxxxxxxxxxxxxxx


A responsive website using only HTML 5 and CSS 3 to 

## Business
### External Users' Goals
 


### Site Owner's Goals
A

### Potential Features
Display a selection of courses, programmes, and coaching for organisations and individuals.

View existing and bespoke courses, programmes and coaching opportunities for organisations and individuals.

Check next course dates and available times, and find the "training centre" (currently my home).

Book courses (yet to be implemented using JavaScript and Python 3). Courses are currently booked via the footer middle links (Mobile, WhatsApp, Email, LinkedIn, YouTube).

## Processes

### UX

The website provides a responsive and easy-to-use visual design, based on a good representation of the elements, and with intuitive navigation.

The website follows a hierarchical Information Architecture and is navigable via the hamburger-menu, which makes it easy to navigate between the web pages.

There are three main actors/roles that use the services provided by the website: Client, Collaborator, and Individual.

* As a client, I want to improve the knowledge, skills, and attitude of my employees so that the performance of my organisation is greatly improved.
	* As a client, I want to view the training and development, and coaching opportunities provided by GaffCo Consulting so that I can plan the training and development plans of my employees.
	* As a client, I want to book the relevant programmes for the training and development for my employees so that they can perform better on-the-job.
	* As a client, I want to contact the owner (Naoise Gaffney) to discuss the details of the programmes so that I can plan the continued development of my employees.

* As a collaborator, I want to work with the owner (Naoise Gaffney) so that we can provide bespoke or off-the-shelf training and development opportunities to our clients.
	* As a collaborator, I want to view the training and development, and coaching opportunities provided by GaffCo Consulting so that I can plan the training and development plans for my clients.
	* As a collaborator, I want to book the relevant programmes for the training and development of my clients so that I can provide professional skills training.
	* As a collaborator, I want to contact the owner (Naoise Gaffney) to discuss the details of the programmes so that I can plan the continued development of my clients.

* As an individual, I want to improve my professional skills so that I can perform better on-the-job.
	* As an individual, I want to view the coaching opportunities provided by GaffCo Consulting so that I can improve my professional skills.
	* As an individual, I want to book the relevant coaching opportunities provided by GaffCo Consulting so that I can improve my professional skills.
	* As an individual, I want to contact the owner (Naoise Gaffney) to discuss the details of the coaching opportunities so that I can improve my professional skills.

The User Experience and Design MarkDown document covers the 5 planes in detail:

[User Experience and Design MarkDown](https://github.com/NaoiseGaffney/Professional-Training-Development/blob/master/docs/User%20Experience%20and%20Design.md)

Balsamiq wireframes and mockups of the website (simplified views, and not complete representations):

[Large Wireframe Diagrams of the Website](https://github.com/NaoiseGaffney/Professional-Training-Development/blob/master/docs/User-Centric%20Front-End%20Development%20Project%201.pdf)

[Small Wireframe Diagrams with Notes (Use Cases) of the Website](https://github.com/NaoiseGaffney/Professional-Training-Development/blob/master/docs/User-Centric%20Front-End%20Development%20Project%201%20-%20Includes%20Notes.pdf)




## Solution
### Features

The website enables clients (corporate and individuals) and collaborators to view and book training and coaching opportunities to suit their training and development needs.

The website provides the owner with a global on-line presence, and an ability to position and prove the value of the training and development services provided.

The website provides multiple communication channels, enabling both direct and indirect communication between clients, collaborators, and owner.

This is a layered website making use of 3 dimensions (x, y, z). The background image or colour in the Safari browser is at the bottom (`z-index: -1`). The fixed footer is on top of the background and scrollable text. The hamburger-menu and menu items are on top of the background and fixed footer (`z-index: 1` and `z-index: 2`). The course detail modal is on top of everything, closest to the user (`z-index: 4`).

[User Walkthrough Video - an Overview](https://youtu.be/YxqJtqwyjEs)

#### Existing Features
These features are shared across all web pages on the website:

- Right-top Hamburger-menu: allows users to select the most suitable training and development, and coaching opportunity by having them click on the hamburger-menu and subsequent menu choice (Home, Organisations, Individuals, Programmes).
- Fixed footer - Professional Trainer and Coach: allows users to read my resumé to add to the websites credibility ("been there, done that, and have the t-shirt") by clicking on the graduation-cap or text link or tool-tip.
- Fixed footer - Copyright 2020 GaffCo Consulting: allows users to navigate to my "training centre (home)" by clicking on the location-arrow or text link or tool-tip.
- Fixed footer - Mobile (phone-call): allows users to call me on their mobile or via Skype for Business (if installed) to talk to me about training and development, and coaching, by clicking on the FontAwesome phone icon.
- Fixed footer - WhatsApp (message): allows users to WhatsApp message me on their mobile or laptop/desktop (if installed) to message me about training and development, and coaching, by clicking on the FontAwesome WhatsApp icon.
- Fixed footer - Email (message): allows users to Email me on their mobile or laptop/desktop (if mailto: is linked) to message me about training and development, and coaching, by clicking on the FontAwesome Email icon.
- Fixed footer - LinkedIn (website --> message): allows users to send me a LinkedIn message about training and development, and coaching, by clicking on the FontAwesome LinkedIn icon.

The Fixed footer FontAwesome icons zoom-in (`transform: scale (1.5)`) when hovered over, while also featuring a tool-tip (`i[tool-tip]`) to provide additional information. This is shared across all web pages on the website.

These features are unique or different on the web pages across the website:

The [Homepage: index.html](https://naoisegaffney.github.io/Professional-Training-Development/index.html) provides the following features:

- Background image: Emotional image of success after a hard run - sets the tone of the website, "You too will be equally successful and elated after attending our courses!"
- Motivational mission statement "Organisations Achieve Greater Value through Professionally Coached Employees" - sets the tone of the website stating of a fact, the real reason users are visiting this website.

The [Organisations page: organisations.html](https://naoisegaffney.github.io/Professional-Training-Development/organisations.html) provides the following features:

- Organisations: allow users to know they're on the Organisations page, and presents them with two menus, one for Professional Courses and the other for QQI Courses.
	- Organisations H1 with FontAwesome fa-sitemap icon makes it clear on which page the user is on.
	- Professional Courses Flex Div provides the relevant clickable course options.
	- QQI Courses Flex Div provides the relevant clickable courses.
- Clickable Course Links: allows users to view course details, dates, and training location, by clicking on each link/course item.
- Course Modal: allows users to view course details and either book a course or close the modal by clicking on the 'Book Now!' button or the closing 'x'.

The [Individuals page: individuals.html](https://naoisegaffney.github.io/Professional-Training-Development/individuals.html) provides the following features:

- Individuals: allow users to know they're on the Individuals page, and presents them with two menus, one for Professional Skills Coaching and the other for Specific Coaching Occasions.
	- Individuals H1 with FontAwesome fa-user icon makes it clear on which page the user is on.
	- Professional Skills Coaching Flex Div provides the relevant clickable course options.
	- Specific Coaching Occasions Flex Div provides the relevant clickable courses.
- Clickable Course Links: allows users to view course details, dates, and training location, by clicking on each link/course item.
- Course Modal: allows users to view course details and either book a course or close the modal by clicking on the 'Book Now!' button or the closing 'x'.

The [Programmes page: programmes.html](https://naoisegaffney.github.io/Professional-Training-Development/programmes.html) provides the following features:

- Individuals: allow users to know they're on the Individuals page, and presents them with two menus, one for Professional Skills Coaching and the other for Specific Coaching Occasions.
	- Individuals H1 with FontAwesome fa-user icon makes it clear on which page the user is on.
	- Professional Skills Coaching Flex Div provides the relevant clickable course options.
	- Specific Coaching Occasions Flex Div provides the relevant clickable courses.
- Clickable Course Links: allows users to view course details, dates, and training location, by clicking on each link/course item.
- Course Modal: allows users to view course details and either book a course or close the modal by clicking on the 'Book Now!' button or the closing 'x'.

#### Features Left to Implement
- 'Book Now!' button function (JS) or --> Form (JS/Python 3).
- Additional depth of detail for each course, for example Planned Learning Outcomes.
- Client, Collaborator, and Individual Testimonials to increase credibility and trust.
- Blog/Vlog to sell visions, ideas, possibilities of value to the users, with examples of course and coaching work (2 to 3-minute snippets).
- The design decision is to rely on simple Flexbox and Grid Layouts, rather than relying on a framework such as Bootstrap 4, and still maintain a responsive web design. In future I may stick to solely to Grid with the `minmax()` function to ensure a responsive web design, or venture further into Bootstrap 4 territory. I've left the Grid layout defined in style.css as-is for future additions.

## Technology

A list of the languages, frameworks, libraries, and other tools used for this project.

### Code:
* [HTML 5.2. - W3C Recommendation, 14 December 2017](https://www.w3.org/TR/html52/)
	* The project uses HTML 5 to create the content.
* [CSS 3 CSS - Snapshot 2018 W3C Working Group Note, 22 January 2019](https://www.w3.org/TR/css-2018/)
	* The project uses CSS 3 to style the content and provide the layout.

### Development and Staging Platforms and Environments
* [GitHub / GitPod /Git / GitHub Pages](https://github.com/)
	* The project uses GitHub:
		* GitPod to create and edit the project files (HTML 5 and CSS 3).
		* Git to add, commit, and push the project files to GitHub.
		* GitHub Pages turns GitHub Repositories into Websites.
* [Code Institute GitPod Full Template](https://github.com/Code-Institute-Org/gitpod-full-template)
	* Using the GitPod Full Template from the Code Institute for my project.


### Documentation Tools


### Acknowledgements and Attributions of Used Features and Functions
* [Google Fonts: Raleway](https://fonts.googleapis.com/css?family=Raleway%7C&display=swap)
	* Using this font in different sizes for all text.

* [FontAwesome CDN](https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css)
	* Using FontAwesome font icons to add visual elements to key website features, making the website memorable and easier to navigate.

* [xxxxxxxxxxxxxxxxxxxxxx](https://cdn.pixabay.com/photo/2019/01/27/22/32/mountains-3959204_1280.jpg)
	* Using this image as the background image throughout the website.

* [CSS Before and After pseudo elements explained - part two: the content property by Kevin Powell](https://www.youtube.com/watch?v=xoRbkm8XgfQ)
	* Using the hover tool-tip function for the fixed footer FontAwesome icons: resumé, social and contact links, and location.
* 
[Pure CSS Hamburger Menu & Overlay by Traversy Media](https://www.youtube.com/watch?v=DZg6UfS5zYg)
	* Using the described hamburger menu function for my menu.

* [Target Modal from W3Schools](https://www.w3schools.com/cssref/tryit.asp?filename=trycss3_target_modal)
	* Using this modal function for my course details.

### General Knowledge and Hours of Reading
* [Website: CSS Tricks](https://css-tricks.com/)
	* A website on more than CSS, for example Articles, Videos, Almanac of CSS Features, Code Snippets, Newsletter, Jobs, and Guides all related to front-end web development. I get happily "distracted" by this site, always learning and testing new skills.
* [Master CSS Grids](https://mozilladevelopers.github.io/playground/css-grid/)
	* The best explanation, example, and walkthrough of CSS Grids I've yet to come across. It's simple, really.
* [FREE: Pro Git eBook by Scott Chacon and Ben Straub](https://git-scm.com/book/en/v2)
	* Read parts of this eBook to better understand Git.
* [FREE PDF: Elements of User Experience Design by Jesse James Garrett (second edition 2010)](https://www.academia.edu/33276128/The_Elements_of_User_Experience_-_Jesse_James_Garrett)
	* User experience design makes sure the aesthetic and functional aspects of an element works in the context of the rest of the website.

### Elixir of Life
* [Strong Black French Press Coffee](https://www.youtube.com/watch?v=st571DYYTR8)
	* Keeps me alert and on-schedule; keeps me going through the night. This is the secret source of my programming-powers. :-)

### Technological Design Decision
The design decision is to rely on simple Flexbox and Grid Layouts, rather than relying on a framework such as Bootstrap 4, and still maintain a responsive web design. In future I may stick solely to Grid with the `minmax()` function to ensure a responsive web design, or venture into Bootstrap 4 territory.

## Testing
### Manual Testing Technology
The following combination of software and hardware is used for all tests:

* Chrome on MacOSX (MacBook Pro) for both laptop/large display and mobile devices (inspect --> responsive).
* Firefox Developer Edition on MacOSX (MacBook Pro) for both laptop/large displays and mobile devices (Web Developer Tools --> Responsive Design Mode).
* Safari on MacOSX (MacBook Pro) for laptop/large display testing.
* Physical devices: Samsung Galaxy Note 10+ 5G with Chrome, Samsung Browser and Firefox. Apple iPhone 8 with Chrome and Safari.

[Test Case Walkthrough Video - A Summary](https://youtu.be/w1bz3HG6KsE)

### Manual Testing Criteria
The Acceptance Criteria are a compressed (simplified) version of the Use Cases described under section Processes --> UX:

1. View/Check Dates and Location/Book Course/Coaching/Programmes.
	1. 	Click on the hamburger-menu on the top-right corner.
	2. Click on the menu choice you're interested in: Home, Organisations, Individuals, Programmes.
	3. Click on the course of interest (course detail modal appears).
	4. Course detail modal contains the course header, the closing 'x', the course description, course Dates & Times, Location/Address, and a 'Book Now!' button.
		1. 	Click on the Course Dates & Time text link or date icon.
		2. View the Google Calendar with courses, dates and times (opens in a new tab).
		3. Go back to the website and click on Location: GaffCo Consulting or the location-arrow icon.
		4. View the Google Maps address.
		5. Go back to the website and click on the 'Book Now!' or closing 'x' button. The course details modal closes (not yet implemented a function for the 'Book Now!' button).

2. Credibility Check on Resumé
	1. Click on the Professional Trainer and Coach link text or graduation-cap icon or tool-tip (opens in a new tab).
	2. View the Resumé website (based on the Rosie Odenkirk walkthrough).

3. Location/Address
	1. Click on Copyright 2020 GaffCo Consulting or associated location-arrow or tool-tip.
	2. View the Google Maps location.

4. Call
	1. Click on the phone icon or tool-tip.
	2. On mobile devices the phone-call is added to the phone app screen or in Skype for Business or another associated app. On laptops/desktops it opens Skype for Business or another associated app.
	3. Call and talk...

5. WhatsApp
	1. Click on the WhatsApp icon or tool-tip.
	2. On mobile devices WhatsApp opens with a suggested message of 'Training and Development Opportunity'. On laptops/desktops it opens WhatsApp if installed or looks for another associated app. Will fail otherwise.
	3. Write a pleasant message and send...

6. Email
	1. Click on the Email icon or tool-tip.
	2. On mobile devices Google Mail opens with an empty email with the send-to address filled in (naoise.gaff.gaffney@gmail.com). On laptops/desktops it opens Google Mail if installed or looks for another associated app. Will fail otherwise.
	3. Write a pleasant message and send...

7. LinkedIn
	1. Click on the LinkedIn icon or tool-tip.
	2. A new tab with LinkedIn opens.
	3. If logged in, click on Message.
	4. Write a pleasant message and send...

8. YouTube
	1. Click on the YouTube icon or tool-tip.
	2. A new tab with a YouTube channel opens.
	3. Enjoy the content...

### Testing Notes
All devices and formats are tested in both portrait and landscape mode. The website is responsive and supports all tested browsers.

A couple of things to note:

* Safari does not support background images which is why a background colour is defined instead.
* On the smallest devices (Galaxy S5 and Apple iPhone 5) some of the course menus (Flex Div) slide under the fixed footer, meaning that the only way to click on the bottom-most course detail is to do so in portrait-mode.
* The course detail modal is set to `z-index: 4` to lie on top of the fixed footer and hamburger-menu. As the footer is fixed the course detail modal is scrollable to allow the user to read all the information and click on all the icons and buttons.

### HTML and CSS Validation: [Nu HTML and CSS Checker](https://validator.w3.org/nu/)

CSS Check! :-)

HTML:

* index.html: Error: Attribute tool-tip not allowed on element i at this point.
* organisations.html: Error: Attribute tool-tip not allowed on element i at this point.
* individuals.html: Error: Attribute tool-tip not allowed on element i at this point.
* programmes.html: Error: Attribute tool-tip not allowed on element i at this point.

The "Error: Attribute tool-tip not allowed on element i at this point." errors are not important as the tool-tip function is best attached to the FontAwesome icons to provide the required functionality.

## Deployment
For this project a combination of Repl-it~ and GitPod were originally used, then for the sake of speed, stability, and ease-of-use I moved over to Visual Studio Code for coding, and using the Source Code Management provider with git to synch (stage, commit, synch) my updates to GitHub.

I initially used Repl.it~ for testing and trialing new ideas and features, and GitHub/GitPod for the main stable development environment. I had issues with both Repl.it~ and GitPod which made development testing an annoyance. Repl.it~ freezes from time to time, and updates the development environment (losing connectivity) in mid-work. GitHub/GitPod can take several minutes in the worst instances to update the changes made to either HMTL or CSS files, and at times the preview didn't display the background image used for this project (worked in a separate tab).

Visual Studio Code is the development platform of choice from now on, together with GitHub for deployment and GitPages for publishing.

I'm working off of the same main branch on GitHub, though I have a staging environment on DropBox for Visual Studio Code.

When initially using Repl.it~ I did nothing beyond using the built-in features to save, deploy, and publish the website.

When using GitHub/GitPod I perform the following steps:

* Testing and Development
	* In the terminal I ran: `python3 -m http.server` to start the web server.
	* Clicked on Open Browser for port 8000 to view the web pages.
	* The preview browser doesn't show the background image, though shows all the updates immediately.
* Deployment
	* In the terminal I ran:
		* `git add .` to track all new and modified files from the working directory to the staging area.
		* `git commit -m "Relevant text goes here..."` to save all staged changes, along with a brief description from the user, in a “commit” to the local repository.
		* `git push` to push changes in the local repository to the GitHub.
* Publishing
	* [Project Repository](https://github.com/NaoiseGaffney/Professional-Training-Development)
		* Click on Settings. Scroll down to GitHub Pages.
		* Under Source click on the Select Source button, and select 'master branch'.
		* After a couple of minutes a message above Source says the following: "Your site is published at https://naoisegaffney.github.io/Professional-Training-Development/".
		* Click on the link to access the published website: [Professional Training and Development](https://naoisegaffney.github.io/Professional-Training-Development/)

Local deployment is performed in Visual Studio Code to the local LiveServer Web Server.

When using Visual Studio Code with GitHub I perform the following steps:

* Testing and Development
	* As I work in Visual Studio Code and make changes in any code, as soon as I save the changes the LiveServer Web Server automatically updates the browser to show the changes.
	* I use separate versions for testing and development.
		* Testing consists of trying new features and functions as snippets first, then in the current code, and when all works well the code is transferred to my main development environment.
* Deployment
	* To track all new and modified files from the working directory to the staging area.
		* Click on Source Control (branch-icon on the left of the screen).
		* Click on More Actions... (...) and click on 'Stage All Changes'
	* To save all staged changes, along with a brief description from the user, in a “commit” to the local repository.
		* Click on Source Control (branch-icon on the left of the screen).
		* Click on More Actions... (...) and click on 'Commit All'
		* Enter a short description in the text box and press Enter.
	* To push changes in the local repository to the GitHub.
		* Click on Source Control (branch-icon on the left of the screen).
		* Click on More Actions... (...) and click on 'Commit All'
* Publishing
	* Go to (click on link) [Project Repository](https://github.com/NaoiseGaffney/Professional-Training-Development)
		* Click on Settings. Scroll down to GitHub Pages.
		* Under Source click on the Select Source button, and select 'master branch'.
		* After a couple of minutes a message above Source says the following: "Your site is published at https://naoisegaffney.github.io/Professional-Training-Development/".
		* Click on the link to access the published website: [Professional Training and Development](https://naoisegaffney.github.io/Professional-Training-Development/)

## Credits     ?????
![GaffCo Consulting Logo](https://github.com/NaoiseGaffney/Professional-Training-Development/blob/master/docs/GaffCo%20-%20Background.png)

![Code Institute Logo](https://github.com/NaoiseGaffney/Professional-Training-Development/blob/master/docs/CodeInstituteLogo.png)

Code Institute Mentor - [GitHub: 5pence - Spencer Barriball](https://github.com/5pence)

### Content
- [GitHub: Project Repository] xxxxxxxxxxxxxxxxxxxxxxxx
-

### Media
* [FontAwesome CDN](https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css)
	* Using FontAwesome font icons to add visual elements to key website features, making the website memorable and easier to navigate.

## Acknowledgements
###  * Special thanks to my mentor Naoise Olof Seán Gaffney, for supporting me in designing and developing the concept.


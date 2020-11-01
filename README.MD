<h1 align="center">New Irish Life</h1>

Web-based travel guide for providing correct information on how easily start living and working in Ireland.
Finding work, a place to stay where to buy good cheap food in Ireland can be difficult but with the correct preparation, 
advice, and planning this task can be made a lot easier.
This website is a great starting point.

![Website Main Mockup](https://github.com/tsokac2/newIrishLife_testing/blob/master/assets/wireframes/main.png) 

## UX

**Story:**
* Four years ago, one Croatian landed in Dublin, Ireland. 
On the web, there was a lot of info about life in Ireland, but not essentials information in one place.
Well, not anymore. *

#### User Story

**As a new Irish resident, I want all NECESSARY AND IMPORTANT information for my New Irish Life in one place and available from any device connected to the internet,  so I can organize my life in a fun and simple way.**
**With New Irish Life that is extremely possible!**

* Definition by HOME section - inform the user of page usage and purpose.
* Definition by TRIP section - pitch users on quick links for travel options, regarding trip planning, prices, destinations road travel in Ireland, and major possibilities.
* Definition by WORK section - user advice of most popular web "job-hunt" services in Ireland as well as education offers.
* Definition by LIFE section - give and introduction of general "life" information in Ireland regarding accommodation, mobile networks, and food shopping 

#### Design process
* #1 Draft all mani section of the web-page - HOME, TRIP, WORK, LIFE
* #2 Brief list all pop-ups/pages - SING IN and LOG IN sub-elements
* #3 List all colors pallets - usage - background color, font color, border.
* #4 List all font styles for best UX 
* #5 Draft web-page layout using Adobe Photoshop for the main layout and Adobe Illustrator for layout components such us Logo, borders, navigation elements
* #6 List possible Fowtawesome Icon for best UX in picture experiences
* #7 List Semantic markup to structure HTML code
* #8 List CSS folder structure for SASS Preprocessor configuration

### Wireframes

General Design idea and Elements order - [View](https://github.com/tsokac2/newIrishLife_testing/blob/master/public/wireframes/w_03.png)

Responsive Layout Planning - [View](https://github.com/tsokac2/newIrishLife_testing/blob/master/public/wireframes/w_04.png)

Main Layout for Larger and Small screens - [View](https://github.com/tsokac2/newIrishLife_testing/blob/master/public/wireframes/w_02.png)

Mobile Desing for Nav Elements - **Home.html** - **Trip.html** - **Work.html** - **Life.html** - [View](https://github.com/tsokac2/newIrishLife_testing/blob/master/public/wireframes/w_01.png)


#### Main Layout
* MENU - Right navigation -- Logo -- Right menu option - Search bar - Sing in  - Log in
* MAIN SECTION AREA - Main section content following website features - HOME - TRIP - WORK - LIFE
* FOOTER -  Footer Menu links - Newsletter Subtraction - Social Media links - Copyrights 

## FEATURES

#### HOME
Simple introduction of web page purpose and what value it is bringing to an end-user. 
Formated in three main sub-sections:
* Movie reference pitch
* Welcoming "Hero" area with picture composition
* Quick box-model overview of the web page mani section

#### TRIP
Section introduction with intro reference and "call-action" headings
Formated in two main sub-sections:
* Flights booking web services quick links
* Ireland public transportation most popular options

#### WORK
Introduction and quick links of the most popular Irish online recruitment sites with an additional section for online education possibilities
Formated in two main sub-sections:
* START HERE - 6 quick links
* CV TIPS - 3 most popular online courses 

#### LIFE
Section with life essentials factors after moving to Ireland
Formatted in three main sub-sections:
* Accommodation online search agencies
* Mobile/internet networks providers
* Irish Top food chains

### Features Left to Implement
Expansion plan:
* Implementing website functionality for UX regarding Sign Up and Login forms validation
* Implementing comments section for the users, regarding specific website content
* Implement section for all necessary documentation in Ireland, regarding and PPS number, Bank Account option
* Implement section regarding social events and gathering for necessary user connection expansion 
* Connect to external API for creating user account regarding receiving news and updates - database configuration
* Offer add for recruitment agencies  - the connection between end-user and possible employer or recruitment agent

## TECHNOLOGIES USED
**HTML** - Semantic elements - nav, section, footer
**CSS3**
**SASS** - Preprocessor - tools included -
* SASS Compiler -  package.json - `"scripts" {"watch" : "node-sass -o public/css public/scss/index.scss -w" }`
* SASS interpolation
* SASS Mixins - Responsive layout functions
* SASS Variables
* SASS Nesting

**BOOTSTRAP 4.5.3**  - Mani layout control - responsive layout usage - helper classe included - example -  .mt, .pt, .d-none .d-md-block, etc...

* Libery provider: https://getbootstrap.com

* Libery URL: `<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">`

**NODE.JS** -  Open-source, cross-platform, back-end, JavaScript runtime environment - href="https://nodejs.org/en/

**NPM** - Package manager - Use package - npm i node-sass - https://www.npmjs.com/

**GIT** - Project deployment

**GITHUB** - Hosting Platform - https://github.com/

**IDE** - Visual Studio Code - https://code.visualstudio.com/

**ADOBE PHOTOSHOP** - Images pereparetion - Logo Design

**ADOBE ILLUSTRATOR** - Logo Design


## TESTING

Major testing web browsers included in project testing - Goggle Chrome - Mozilla Firefox  - Microsoft Edge 
When the website is successfully uploaded to GitHub and the website URL is generated, the testing process can start:

* STEP 1.	Copy website URL to -  **W3C Markup Validation Service**
* STEP 2.	Correct all code errors and warnings - possible source of solutions on **stack overflow** -  https://stackoverflow.com/ 
* STEP 3.	Check any console error by using Google Chrome or Mozzila Firefox  **Developer Tools** -  schorcut - Ctrl + Shift + I
* STEP 4.	By using Developers Tools chose option **Toggle device toolbar** and test the website on all devices - starting from the smallest device and working to the largest
* STEP 5.	When testing the website on multiple devices and screen sizes is recommended to check viewport rotation on mobile devices since the viewport is different for portrait and landscape orientation.
* STEP 6.	Check website breaking points for smartphones, tablets, and desktop devices
* STEP 7. 	Check paragraph margins, padding, and font sizing on small and larger devices
* STEP 8.	Make sure all external links are opening in a separate browser tab and leading the user to the correct website destination
* STEP 9.	Check Color contras for foreground and background colors by using **Contrast Checker** - https://contrastchecker.com/
* STEP 10.	Check code organization for future updates


Development and testing overview in order as follow:
* xxs max - MAX width 240px     - elemet padding - element margins - center allignmet - fluent font size
* xxs   - MIN width 240px       - elemet padding - element margins - center allignmet - fluent font size
* xs    - MIN width - 360px     - elemet padding - element margins - center allignmet - fluent font size
* sm    - MIN width - 576px     - elemet padding - element margins - center allignmet - fluent font size
* md    - MIN width - 768px     - elemet padding - element margins - center allignmet - fluent font size
* lg    - MIN width - 992px     - elemet padding - element margins - center allignmet - fluent font size
* xl    - MIN width - 1200px    - elemet padding - element margins - center allignmet - fluent font size

 ### Testing tools

MOZILLA FIREFOX -   https://www.mozilla.org/en-US/firefox/new/

GOOGLE CHROME   -   https://www.google.com/chrome 

MICROSOFT EDGE - https://www.microsoft.com/en-us/edge

GITPOD          -   https://www.gitpod.io/
* server startup: `python3 -m http.server`

CODE VALIDATION PLATFORMS - W3C Markup Validation Service - https://validator.w3.org/

CONTRAST CHECKER - https://contrastchecker.com/


### W3 Validator Error's and Solutions

**ISSUE #1** 

Error: Duplicate ID username

`<input type="text" id="username" placeholder="Username or Email">`

SOLUTION: Create unique  ID - `id="username"` for Sign Up form  - `id="username-log"` for Login form


**ISSUE #2** 

Error: Bad value public\img\Logo.png for attribute src on element img: Backslash ("\") used as path segment delimiter.

`<img src="assets\img\Logo.png" width="100" alt="New Irish Logo"></a>`

SOLUTION: `<img src="assets/img/Logo.png" width="100" alt="New Irish Logo"></a>` - change "\" to "/" 

**ISSUE #3**

The aria-labelledby attribute must point to an element in the same document. 

`<div class="modal fade" id="sing-in" data-backdrop="static" data-keyboard="false" tabindex="-1" aria-labelledby="staticBackdropLabel" aria-hidden="true">`

SOLUTION: ` <div class="modal fade" id="sing-in" data-backdrop="static" data-keyboard="false" tabindex="-1" aria-labelledby="sing-in" aria-hidden="true">`

SOLUTION SOURCE -  https://stackoverflow.com/questions/39831658/how-to-fix-the-aria-labelledby-attribute-must-point-to-an-element-in-the-same-d
 

## DEPLOYMENT

Project link - [newIrishLife](https://tsokac2.github.io/newIrishLife/)

GITPOD  -   https://www.gitpod.io/

Tools:
* GIT - `git add . | git commit -m "Description of commit" | git push | git status 

## CREDITS 

### Content
*   Intro pitch - *"The Hobbit: An Unexpected Journey"* - Wiki - https://en.wikipedia.org/wiki/The_Hobbit_(film_series)

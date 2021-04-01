# Sublime Sounds 


Sublimes sounds was created as a fictional site the inspiration is taken from Sofar sounds where they host different events in different locations with different artists . 
find link here to sofar sounds here
Same Sounds is a cultural Initiative in luxembourg belgium and the netherlands where we want to give back to the artist , not by free drinks and peanuts but actually pay them for their efforts and talents. We host 4 events every month either one night or a weekend. Each performance can be in a different location depending on the number of guests, these events can include music , singing , acapella ,poetry ,comedy. Whatever you have to offer we are to listen.

https://www.sofarsounds.com/

## Table of contents
 1. User Experience
 2. User Stories
 3. The 5 Planes
 4. Wireframes
 5. Features
 6.Technologies Used
 7. Testing
 8. Code Validation
 10. Deployment
 11. Resources


#### User Experience (UX)
1.I want to create a simple design to showcase the artist work and easy to find information. Where to sign up and where to submit their work  and the maps is to give the locations of the various places we will have events with in that time frame so it would have 4 or more different location displayed on the with in the regions of Luxembourg , Belgium and the Netherlands.

2.Interactive navigation links.

3.Interactive social links section.

4.Map controls which provide feedback to the user.

##### User Stories
1.As a first time visitor, I wanted to feel that I was apart of somewhat secret society but yet can be included so it has a bit of a darker theme with accessible information.

2.As a user if I wanted to attend I would like to know how ,when and where these events would take place.

4.As a user, if I wanted to perform i would like to know how I can submit my work/talent and where I would be able to perform.

5.As a user, if I wanted to be a host at an event e.g. bar or restaurant , I need a contact section to get more information on how this can be done. 

6.A contact section for any information that might not be covered
 
#### The 5 Planes of UX
The five planes provide a framework for discussing user experience.

1.Strategy
Discover new talent 
Have different events to appeal to people's wants /needs 
Discover new location and bars to the owners or to help struggling ones
Bring people together from different locations.

2.Scope
The primary requirements for the scope are to provide interactive elements which enable the user to initiate and control actions.

3.Functional Requirements
The functionality is provided by
One main page divided into different 5 sections 
To have a flow of instructions 
How : model pop-up that allows you to select tickets and buy them using a event     discovery API(tm/developer) to manage ticket sales 
Sign-up:Modal pop-up sign-up form for artist so they can submit work 
When : Cards with when and the next  location will be 
Where: Google maps with pins to show location 
A contact page with contact form (connected to formspree.io)
Interactive social media links to access to artist and past events 

4.Content Requirements.
The content of this page mainly comes from unsplash copyright free images used And Google fonts for heading and writing text implementation but I wanted have the opportunity to change the imagery depending on the event taking place during that month
The struggle with the content was the map inclusion as there are more the  one way to integrate it into your website and to make sure was responsive to different location was another challenge 

5.Structure.
The website needed to be well organized with minimal text , and to stay well with in the scope of what was initially thought , I wanted the website to be intuitive and images speak for themselves as there might be people who speak different languages , because a picture speaks 1000 words 

##### Interaction Design.
The website has been designed to be as interactive as possible, enabling the user to control what they see and when. User interaction is controlled through:
Buttons needed to be clear and get the user where they need to go 
Anchor links will change their appearance when the cursor hovers over them and also when clicked to indicate which is active.
Navigation  with clear and intuitive icons that will pop out .
Social Media links will be in the footer and for any more information and will have bright colours to stand out.
 
Information Design.
Jumbotron. 
About.
When and where. 
Modal pop-ups -for easy sign-up or purchase. 
Map to be under contact form. 
For mobile devices the information section displays above the map.
I had considered different layouts and concluded that this layout was better for devices with smaller viewports as the user would see some basic information about the destination before scrolling down to the map. The design wouldn't be as intuitive if the map displayed before the information.

Skeleton.
The website will comprise three main pages:
Landing | Explore | Contact
This has been intentionally reduced from a more conventional multi-page site.
Interface Design
Presenting everything in the viewport ensures all key information is available and visible to the user without any requirement to scroll. Buttons are large enough to be obvious yet not intrusive.

Navigation Design 
 One simple scroll or nav bar to help you jump around
 Information Design
 I want to use google maps to help make location more visible and people could search of different ways to have to reach the various locations of the events.
Where 
 Locators at the specific events 
 Options to view street and outside side location

##### Wireframes. 
 Wireframes for the original design concepts were created using figma the orginal idea can be found here. 
 Landing Page
 Inviting image to and that it will change from week to week depend on the artist and everyone gets their time in the limelight. 
 
##### Map 
The Map would be Centered with difference markers and i might change markers later own
Contact Page
contact page
 I used formspree to interact with the user and server side 
Copyright does need be included MIT
 
 
Typography
I wanted simple and elegant to read with a few bold headings just to grab attention of the user
Imagery

.The images of this site mainly (all) came from unsplash which served well for this purpose 

Features
Modal pop-ups and javascript incorporations 
Existing Features
Interactive website one page as the user scrolls and divided into 5 sections 
Landing page/About page/how stay updated/events/locations/contact page.
 
When the user interacts with the map buttons,they will display markers for the respective "Points of Interest" category 
 
 
#### Testing
For this I did use various resources to help me 
- W3 validations-When placed into w3 validation most of my images did not have an alt if it did not load -so I added alternative words for these images
 - images were not responsive 
 - map was not responsive 
 - Form was not valid 
 - Modal pop-up was not working I used slack-workflow to help and the problem was the path to my jquery and my script form bootstrap was not placed correclty

Testing matrix can be found here.
https://docs.google.com/spreadsheets/d/1TacAVNGg3uNkDcEx4Qw1lV2iqhafeMcGQH2WbkSOyDU/edit?usp=sharing

Manual testing.

 1.samsung 20e 
   - most of the page was responive google maps did not shrink to size.
 
 3.ipad
   - took desktop design
 
 5.iphone 6/7/8 
   - Google maps not responive. 

Google maps was a never ending of  trying to create cluster markers  but every time i did my code was involved and could not view my map at all and I used devops to help resolve these issue but options can go on for so , I had to enable my api in order for it to be viewed on my html page. 

Modal pop-up was not working I used slack-workflow to help and the problem was the path to my jquery and my script form bootstrap was not placed correclty.
 

#### Technologies Used
This website has been built using the following core technologies:
Core Coding languages
 - HTML5
 - CSS3
 - Javascript
Integrations
 - Bootstrap 4
 - Font Awesome was the source of all icons.
 - Fonts used on the website courtesy of Google Fonts
 - The project uses JQuery to simplify DOM manipulation.
Formspree for email integration
 
 
 
#### Version Control, storage and hosting

 - All of the website's code was written in the Gitpod IDE.
 - used for maintaining version control of the saved files.
 - used as the primary repository for storing the files and documentation.
Other
Hover.css for button hover effects
Dillinger was once again used to edit the markdown required for the README 
Codepen for maps examples and other animated css tricks

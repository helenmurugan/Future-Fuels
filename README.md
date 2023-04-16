# Future Fuels

![Image showing screenshots on different sized devices](documentation/screen-generator.jpg)

By Helen Murugan

[View the live site here](https://helenmurugan.github.io/future-fuels/)

This is a documentation of the development process for Future Fuels website. It is for educational purposes only, as my first milestone project for a diploma in Full Stack Software Development with Code Institute, using frontend development with HTML and CSS.

## Project Goals
Future Fuels is a site that offers a service to businesses who need to reduce their emissions from road transport. It is a B2B site which offers a solution to a real-world problem. My research has shown that this type of business does not already exist, to the best of my knowledge. Other consultancies do exist which offer a wide range of services but not specifically to reduce emissions from road transport.

* ## Site Rationale
New legislation banning the sale of petrol and diesel vehicles will provide a challenge to businesses who need to choose between and transition to new fuel technologies, the impacts of which may not be well-understood. Future Fuels addresses this problem by providing consultancy to businesses who need to find cost-effective fuel strategies that suit their business requirements, and specifically the requirements from the new fuels they adopt (range, refuel time, cost, vehicle capacity, infrastructure etc). The site provides a short description of why this service is needed, basic information on the main alternatives to conventional fuels and the pros and cons that exist for each technology. There is also an opportunity to contact Future Fuels for more information about the services provided.

* ## Target Audience
    The intended audience are businesses who have fleets of road transport vehicles. Examples of such businesses include: 
    * Delivery services 
    * Emergency services
    * Mobile services (eg. mechanics/roadside assistance)
    * Transportation of cargo

## Features

* ### Navigation
    * Featured at the top of all five pages for intuitive navigation
    * Includes the Future Fuels logo that links to the home page, as well as links to pages for Batteries, Biofuels, Hydrogen and Contact Us.
    * The navigation bar is fully responsive. At large screen sizes the links are clickable page titles. For medium and small screen sizes a hamburger menu is used.
    * For the logo a distinctive font was used for brand recognition and green was chosen as the colour inkeeping with the 'green' theme of the site.
    * The other navigation links are in a font which is consistent across the site.
    * The navigation bar makes it easy for users to navigate around the site without using the back button on the web browser.
    * Below the navigation bar is a styled title bar which lets the user know which page they are on (except for the home page where this title is not necessary).

![nav bar image](documentation/nav-bar.jpg)

* ### The Landing Page Image
    * The landing page includes a photograph with text overlay to allow the user to see a statement of purpose. 
    * Users will immediately understand where they have come and what Future Fuels provides.
    
![landing image](documentation/landing-image.jpg)

* ### Why Future Fuels Section
    * This section briefly describes a problem that businesses will face in the near future. 
    * It lays out in simple terms how Future Fuels can provide a solution to this problem.

![Image of Why Future Fuels section](documentation/why-future-fuels.jpg)

 * ### Fuel Requirements Section
    * This section uses a flexbox, icons and headings to provide a simple infographic which demonstrates the important factors when considering new fuels. 
    * This is followed by a paragraph which explains what Future Fuels can provide to the user.

![Image of Why Future Fuel REquirements section](documentation/fuel-requirements.jpg)

* ### Footer
    * This section provides links to Future Fuels social media pages to allow the user to stay connected.
    * The links will open to a new tab to allow easy navigation for the user.
    * The footer is identical across all five pages.

![footer image](documentation/footer.jpg)

* ### Favicon
    * Displays a secondary logo to strengthen the brand.
    * Makes it easier for the user to pick out Future Fuels site from the tabs.

![favicon image](documentation/favicon.jpg)

* ### Batteries, Biofuels and Hydrogen Pages
    * These three pages follow the same format for good user experience.
    * They consist of a heading which demonstrates the current or expected use of each fuel, paragraphs giving a simple description of the technology and two lists showing the pros and cons for each fuel.
    * The text is broken up into manageable short paragraphs and styled lists to keep the users attention.
    * These pages are valuable to users as they introduce new information in an intuitive and understandable way.

* ### Contact Us Page
    * The Contact Us page consists of a heading which encourages the user to fill in a form to receive back a free discovery call.
    * The form consists of input fields for first name, last name, email address, organisation, a message and a submit button.
    * This page is valuable to users as it provides a way to learn more about Future Fuels.

* ### Features Left to Implement
    * Subsequent versions of this site will include case studies/testimonials from existing clients.

## Testing
* The site has been tested and works well in different browsers: Chrome, Microsoft Edge and Safari.
* DevTools device toolbar was used to ensure the site is fully responsive and looks good across different screen sizes. 
* Media queries were added to the following features, where I could see features becoming squashed as the screen size got smaller. I have tested that features are all readable and easy to understand.
    * Navigation menu (hamburger appears at 1299px and below and page title navigation links are hidden).
    * Width of headings, images and paragraphs is increased for smaller screen sizes (incrementally at 1299 px and 700 px and below).
    * Font size for all text is reduced for screen sizes at 700px and below. 
    * Flexbox is reduced to two columns for screen sizes at 700px and below. 
* The form has been tested and requires inputs in all fields, except for the message textarea which is optional. The email address field will only accept an email address. The contact number field will accept numbers of a minimum length of 11 digits. The submit button works and links to a thanks.html page, thanking the user for getting in touch.

* ### Validator Testing
    * HTML 
        * No errors were returned when validating the code with the official W3C validator.
    * CSS 
        * No errors were returned when validating the code with the official (Jigsaw) validator.
    * Accessibility
        * I confirmed that the fonts and colours are easy to read. I used Lighthouse in DevTools to confirm that the each page scores well for accessibility.

* ### Unfixed Bugs
    * There are no unfixed bugs

* ### Deployment
    * The site was deployed to GitHub pages by the following steps:
        1. Log in to GitHub and select Future Fuels repository.
        2. Navigate to Settings tab.
        3. Navigate to Pages from the left-hand menu.
        4. In Source select "Deploy from a branch".
        5. In Branch select "main".
        6. Select Save.
        7. After several minutes the live site was deployed [here](https://helenmurugan.github.io/future-fuels/)

* ### Credits
    * Content
        * The code for the social media links was taken from the Code Institute Love Running project.
        * The code for the hamburger menu using only HTML and CSS was taken from https://dev.to/ljcdev/hamburger-css-no-js-2dfa
    * Media
        * Images were taken from [Pexels](https://www.pexels.com/)
        * The statistics in the page headings were taken from (https://www.acea.auto/), https://www.eea.europa.eu/ and  https://www.euractiv.com/.








![CI logo](assets/images/pequeno.png) 

# Chef Prime

This website was created from an idea I had while I was a private chef in the Algarve, Portugal. Our main service was to cater for families who were going on vacation in the region and wanted a private chef service in their homes.

The website will be aimed at people interested in having a premium service, such as having their own professional chef cook for them.

![Responsice Mockup](assets/media/responsive2.png)

[See deployed website](https://goncalves95.github.io/Algarve_Chef_Prime/)

## Table of content

- [Chef Prime](#chef-prime)
  - [Table of content](#table-of-content)
  - [Design and User Experience](#design-and-user-experience)
    - [Design](#design)
  - [Layout](#layout)
    - [Navbar and footer](#navbar-and-footer)
    - [Home Page](#home-page)
    - [Gallery Page](#gallery-page)
    - [Contact Page](#contact-page)
    - [Booked Page](#booked-page)
    - [Performance](#performance)
  - [Deployment](#deployment)
    - [Live Website](#live-website)
  - [Testing](#testing)
    - [Tests](#tests)
    - [Fixed Bugs](#fixed-bugs)
    - [Validator Testing](#validator-testing)
  - [Credits](#credits)
    - [Content](#content)
    - [Media](#media)
  - [Technologies used](#technologies-used)

## Design and User Experience

### Design

The design of the website is minimalist, to allow the content to show up.

Fonts:

- Poiret one - This is the brand font, so it's used for the Logo, the Wines names and the tasting expeciences names.
- Montserrat (sans serif) - Used for the headings, the menu and the footer.
- Cormorant Garamond (serif) - As serif font is used for the smaller text (paragraphh content), it's more readable.

Colours:

![colors](assets/media/rgb_colors.jpg)

- Primary color.   Secondary color.    Gold secondary color.

## Layout

There are three pages: Home page, Gallery and Contact.
In each page we have a responsive navbar on top and a footer with social media links and a coopyright section.

### Navbar and footer

Both navbar and footer change layout depending on the size of the screen.

- __Navigation bar__

  - All the navigation items are visible on larger screen (769px and up), while they are hidden in a colapsing navbar on smaller screens (768px and down).

  - The colapsing navbar has an hamburger menu icon when it's closed, and an x symbol when it's open.

![Responsice Navbar items visible](assets/media/navbar-itms-visible.png)
![Responsice Navbar hamburguer](assets/media/navbar-hamburguer.png)

- __Footer__

  - The footer contains:
    - copyrights
    - social media links

  - When clicking on the social links, this gone open in a new tab.

![Footer](assets/media/footer.png)

### Home Page

- __Hero-Image__

  - This is the landing page for our users, so it has an eye-catching hero image to grab their attention.
  - The Hero Image contains the principal message from the page. In the Home page its the message "Privet Chef's in your Home or Event"
  in the gallery page is "Privet Chef's Gallery History"
  and in the contact page "Privet Chef's Contact us!" this tops for help the user recognise where he are.

![Hero image](assets/media/header-about-content.png)

- __About__

The home page contain the information about the company. In particular it contains two distinc sections:

- The Algarve, one smal paragraph for descrive the Algarve, where is the work region of the company.

- The about, where the user can finde and read what the company do and what can expect from them.

- __Our Services__

  - In this section I have placed one cards section describing each service provided by the company.  
  - There is one section for each service.
  - It contains one image, a title and a brief description of each service.

 ![Cards's](assets/media/our-services-cards.png)

### Gallery Page

- __Images__

  - On this page you will find simplified information about the services we have already provided. Some images of events and private services provided by the company.

 ![Gallery Page](assets/media/gallery.png)

### Contact Page

- This Page contains a form to contact the company and ask one quote.
- The following fiels are required: Name, Email, Service equired,  Number of people, start and end date of the event.
- There is an additional field to add other information or some doubt. not required field.
- The select element for "Number of People" allows choosing the number of people for the events and, depending on the choice, the company's decision to hire more staff depending on the number of people attending the event, thus giving the client a better price for the service.
- in this extra field exist on I icon with extra informtion for the user know what can fill up in this field.

- __Booked Page__

  - After filling out all the mandatory field, users are redirected to a new page.
  
![Contact Page](assets/media/contact-form.png)

### Booked Page

- Have the Logo company in the Header.
- Have a small video about Algarve so that users can get to know the region they're visiting better and discover more places to visit on their holidays or when they're in the Algarve.
- Thank's message for the contact.
- Company contact in case they have more questions or they need to cancel or modify the sercvie.
- In the information existe the email, here the user can click on the link and open an email page with the company email address already filled in.  
- In the contact information field there is also an address, which when selected opens the map in a new tab for directions to the location.
- A call to action to bring the user back to the homepage, with direct link, so that users are not redirected automatically. The user can clic on the message "back to Home " or in the LOGO.

### Performance

I have tested the performance in chrome, using lighthouse:

<details>
  <summary> Desktop </summary>
  
- Home page:

   ![Desktop - home page](assets/media/home-page-desk.png)

- Gallery page:

   ![Desktop - home page](assets/media/gallery-page-desk.png)

- Contact page:

   ![Desktop - home page](assets/media/contact-page-desl.png)

- Booked page:

   ![Desktop - home page](assets/media/booked-page-desk.png)

</details>

<details>
  <summary> Mobile </summary>
  
- Home page:

   ![Desktop - home page](assets/media/home-page-mob.jpg)

- Gallery page:

   ![Desktop - home page](assets/media/gallery-page-mob.jpg)

- Contact page:

   ![Desktop - home page](assets/media/contact-page-mob.jpg)

- Booked page:

   ![Desktop - home page](assets/media/booked-page-mob.jpg)

</details>

## Deployment

### Live Website

- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab
  - From the Code and automation section drop-down menu, select the Pages.
  - In the build and deployment area, choose from source "deply from a branch" and after in Branch choosse the main branch and root and save.
  - Once this is save, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment (he take me more less 5 minutsfor appear the link).

The live link can be found here - [Live Website](https://goncalves95.github.io/Algarve_Chef_Prime/)

## Testing

To test my website I have opened it on different devices, to see if it was working as expected.

- Browser tested:
  - Chrome
  - Firefox
  - Safari

- Operating systems:
  - Android
  - iOS

### Tests

  <details>
  <summary>General</summary>

  |Action | Expected behavious | Result|
  |-------|--------------------|-------|
  |Copy url of the browser and paste it in browser. Press enter | Browser should load index.html | Pass |
  |Scale up the window | The contentent should not stretch over a certain size | Pass |
  |Scale down the window | The contentent should be visible without having to scroll horizontally | Pass |
  |Scale down under 840px width | The layout should switch from 2 to 1 column | Pass |

  </details>

  <details>
  <summary>Navigation</summary>

  |Action | Expected behavious | Result|
  |-------|--------------------|-------|
  |Scale down under 769px width | The top navigation bar should collapse into hamburger navbar | Pass |

  </details>

  <details>
  <summary>Footer</summary>

  |Action | Expected behavious | Result|
  |-------|--------------------|-------|
  |Click on the LinkedIn icon in the footer | It should open LinkedIn in a new tab | Pass |
  |Click on the Instagram icon in the footer | It should open Instagram in a new tab | Pass |
  |Click on the Facebook icon in the footer | It should open Facebook in a new tab | Pass |

  </details>

  <details>
  <summary>Form</summary>

  |Action | Expected behavious | Result|
  |-------|--------------------|-------|
  |Submit the form without any value | Browser should inform me that "Name" is a required field | Pass |
  |Submit the form without email address | Browser should inform me that "Email" is a required field | Pass |
  |Submit the form with invalid email address | Browser should inform me that "Email" field must be of email format | Pass |
  |Submit the form without choosing a date | Browser should inform me that is a required field | Pass |
  |Submit the form with all the required information | Form should be submitted and open a booked page page | Pass |

  </details>

  <details>
  <summary>Booked </summary>

  |Action | Expected behavious | Result|
  |-------|--------------------|-------|
  |Click on the email address from the booked page | It should open the email client to send an email | Pass |
  |Click on the "Bring me home" link in the booked page | User should be redirected to index.html | Pass |  
  |Click on the adress in the booked page | It shoud open a new tab with the company adress in google maps | Pass |  

  </details>  

### Fixed Bugs

Horizontal Scrolling in xs screens - Fixed with (overflow: auto;)

### Validator Testing

- HTML
  - No errors were returned when passing the final version through the official [W3C validator](https://validator.w3.org/nu/#textarea)
- CSS
  - No errors were found when passing the final version through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator)

## Credits

### Content

- Instructions on how to make the navbar sticky were taken from [Web Dev Simplified, The Forgotten CSS Position](https://www.youtube.com/watch?v=NzjU1GmKosQ)
- Some part's of the code its taken (lerned) from the LoveRun project.
- Instructions on how to apply glassmorphism to the form were taken from [Coding Artist tutorial](https://www.youtube.com/watch?v=FAfFlyaRAiI)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- Instructions on how creat a tooltip in the form were taken from [Covildodev](https://www.covildodev.com.br/artigo/css-tooltip)
- Idea for make the :root code in css for simplify the introduction on css commands with the collors and fonts (Discord chanel : Ballerini)
- The following fonts, used for the project, are from [Google Fonts](https://fonts.google.com/):
  - Montserrat
  - ADLaM Display
  - Cormorant Garamond

### Media

- The photos used for this website are from [Unsplash](https://unsplash.com/)
  - Logo created by me.
  - Company name created and registred for me.
- The video used for the booked page its from [VisitPortugal](https://www.visitportugal.com/)

## Technologies used

- HTML
- CSS

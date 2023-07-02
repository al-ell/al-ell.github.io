# Deaf Cats

![Welcome to ](documentation/) - image of homepage in different devices

![Bookworm](documentation/bookworm.png)

Deaf Cats was created as my first milestone project for the Code Institutes Level 5 Diploma in Web Application Development.

Link to deployed site: [Deaf Cats](https://web-production-b7c20.up.railway.app/)

![GitHub last commit]()
![GitHub contributors]()
![GitHub language count]()
![GitHub top language](e)

## CONTENTS

* [User Experience](#user-experience)
  * [Project Goals](#project-goals)
  * [User Stories](#user-stories)

* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Imagery](#imagery)
  * [Wireframes](#wireframes)
  * [Database Schema & User Journey](#database-schema--user-journey)
    * [User Journey](#user-journey)
    * [First Draft Database Schema](#first-draft-database-schema)
    * [Final Database Schema](#final-database-schema)

* [Features](#features)
  * [Elements Fount on Each Page](#elements-found-on-each-page)
  * [Future Implementations](#future-implementations)
  * [Accessibility](#accessibility)

* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Databases Used](#databases-used)
  * [Frameworks Used](#frameworks-used)
  * [Libraries & Packages Used](#libraries--packages-used)
  * [Programs Used](#programs-used)
    * [Google Books API](#google-books-api)
    * [Flask Blueprints](#flask-blueprints)
    * [Flask Migrate](#flask-migrate)
    * [Error Handling](#error-handling)
    * [Defensive Programming](#defensive-programming)
    * [Database Migration to ElephantSQL](#database-migration-to-elephantsql)

* [Deployment & Local Development](#deployment--local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)

* [Testing](#testing)
  
* [Credits](#credits)
  * [Code Used](#code-used)
  * [Content](#content)
  * [Media](#media)
  * [Acknowledgments](#acknowledgments)

- - -

## User Experience

### Project Goals

The idea for Bookworm was created from a need I saw that my mum had. Being a voracious reader, she never knew which books she had sat on her bookshelf at home whilst out purchasing new books. She also finds it difficult to keep track of which book she is currently on in a series, and previous authors she has read who she enjoyed and would like to try more of their work.

I felt that the project could then be taken a step further, and could also provide a way to store reviews on books read together with a rating and the dates read. It would also be nice to make notes about a book, for example, if you have loaned the book out to a friend.

### User Stories

#### __Target Audience__

The target audience for the website are people who like the bands music and want to 

#### __First Time Visitor Goals__

As a first time user of the site I want to be able to:

* Understand the putpose of the site and how to navigate to other pages.
* Find where I can play their music online.
* Find out more about the band and see pictures of them.
* See when and where they are playing live.
* Book the band to play at an event.

#### __Returning Visitor Goals__

As a returning registered user of the site I want to be able to:

* Find out about new music releases and where it can be played online.
* See when and where they are playing live.
* Book the band to play at an event.


#### __Admin User__

As an administrator for the site I want to be able to:

* Provide a way for the band can be contacted.
* Create a working form that sends messages to an email address.
* Create a ticket booking sytem (future releases).

- - -

## Design

### Colour Scheme

I have taken inspiration from the header image for the colour palette and chosen colours that complement each other.

![Colour Scheme for Deaf Cats](documentation/imagecolorpallete.png)
https://imagecolorpicker.com/en/user/shared-palette?id=753240f0-ee2b-4f3d-beba-6ac52191d34c

### Typography

I used Google Fonts to import the following fonts for use in the site:

##### Logo 
![Monoton](https://fonts.google.com/specimen/Monoton?query=monoton) 
I chose this as it has smooth curves and makes a unique logo style. 
![sample](documentation/fonts/monotonsample.png)

##### Headings 
![Ubuntu](https://fonts.google.com/specimen/Ubuntu?preview.text=Deaf%20Cats&preview.text_type=custom&query=ubun) 
The font is easy to read, has good speacing between letters and continues the curves of the logo. 
![sample](documentation/fonts/ubuntusample.png)

##### Paragraphs 
![Cabin Condensed](https://fonts.google.com/specimen/Cabin+Condensed?preview.text=Deaf%20Cats&preview.text_type=custom&query=cabin+con)
I felt this complimented the headings font well and is a sans-serif which improves legability. 
![sample](documentation/fonts/cabincondensedsample.png)

##### Icons 
![Font Awesome](https://fontawesome.com/icons)
Icons are a good way to add accessability features to a website 


### Imagery

As the site is for fans of the band I have chosen imsges of a group of people from a stockfile website. I have complimented these with musical themed images.Please view the media section for more information on where each image was sourced.


### Wireframes

Wireframes were created for mobile and desktop using Balsamiq.

#### __Home Page__

![Home Page](documentation/wireframeshomepage.png)

#### __Contact Modal__

![]](documentation/wireframes/contactus.png)

#### __Gallery Page__

![Login Page](documentation/wireframes/gallery.png)

#### __History Page__

![Profile Page](documentation/wireframes/history.png)

#### __Live Page__

![Live Page](documentation/wireframes/livedates.png)



###  User Journey

#### __User Journey__

![User Journey](documentation/user-journey.png)


## Features

The website is comprised of 4 pages which are extended from a base template.

* Home page
* Gallery page
* History page
* Live page
* Contact form modal


### Elements found on each page


* Navbar - The Navbar is displayed on all pages of the website, it allows users to navigate the site with ease. The navbar is comprised of a logo, and links to navigate within the site and a search bar.

  __Navbar__
  
  ![Navbar]()

* Footer - A footer containing the modal button and external social media icons links is displayed on all pages of the website.

__Footer__

  ![Footer](documentation/footer.png)

- - -

### Home Page

![Home Page]()

### Gallery Page

![Gallery Page]()

### History Page

![History Page]()

### Live Page

![Live Page]()

### Contact Form Modal

![Contact Form Modal]()

- - -

### Future Implementations

In future implementations I would like to:

* Create a ticket booing system/allow users to boy tickets on the website.
* Create an online shop selling merchandise.
* Add a sign up link for a mailing list.

### Accessibility

I have been mindful during coding to ensure that the website is as accessible friendly as possible. This has been achieved by:

* Using semantic HTML.
* Using descriptive alt attributes on images on the site.
* Providing information for screen readers where there are icons used and no text.
* Ensuring that there is a sufficient colour contrast throughout the site.

- - -

## Technologies Used

### Languages Used

HTML, CSS.

### Databases Used


### Frameworks Used

[Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/) - V 4.5 Css framework.

### Libraries & Packages Used



### Programs Used

[Codeanywhere] - Online code editor.

[Balsamiq](https://balsamiq.com/) - Used to create wireframes.

[Git](https://git-scm.com/) - For version control.

[Github](https://github.com/) - To save and store the files for the website.

[Google Fonts](https://fonts.google.com/) - To import the fonts used on the website.

[Font Awesome](https://fontawesome.com/)  - For the icons on the website.

[Google Chrome Dev Tools](https://developer.chrome.com/docs/devtools/) - To troubleshoot and test features, solve issues with responsiveness and styling.

[Am I Responsive?](http://ami.responsivedesign.is/) To show the website image on a range of devices.

- - - 

## Deployment & Local Development

### Deployment





### Local Development

#### How to Fork



#### How to Clone


- - -

## Testing

Please see [TESTING.md](TESTING.md) for all testing performed
- - -

## Credits

### Code Used

### Content

Content for this project was written by Alice Elliott.

### Media

* Image for gallery [street2](https://www.pexels.com/photo/man-playing-guitar-beside-woman-and-man-listening-to-him-2479320/)

* Image for gallery [street3](https://www.pexels.com/photo/man-playing-guitar-on-street-2479323/)

* Image for gallery [trumpet](https://www.pexels.com/photo/people-performing-on-stage-442540/)

* Homepage Image[street-homeimage](https://www.pexels.com/photo/two-men-and-woman-sitting-next-to-each-other-2479312/)

* Image for gallery [guitar](https://www.pexels.com/photo/two-men-and-woman-sitting-next-to-each-other-2479312/)

* Image for gallery [outdoor-concert](https://www.shutterstock.com/image-photo/jazz-musician-playing-outdoor-concert-1107297416)

* Image for gallery [outdoor-concert2](https://www.shutterstock.com/image-photo/jazz-musician-playing-saxophone-beautiful-voice-1011331978)


### Acknowledgments

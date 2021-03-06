<img src="./assets/images/kuua-logo-circle.png" alt="logocopy" class="center" />

# KUUA

## Pop Art Gallery

I've designed and built this website to display and promote Pop Art as a way of both building a business and doing good, hoping to get attention from the public and amplify what VUMc is doing.

The gallery promotes art and collaborates with VUMc in Amsterdam, a hospital devoted to advance research in chronic diseases.
KUUA donates 50% of their profits and aims to become a patron of the hospital.

Today, the work exhibited is from one painter (me), but it is the aim of KUUA to become a go-to online gallery for aspiring artists to collaborate.

KUUA is the name of a .com owned by me. 
The logo has been created by me

## UX

This website has been created as a one page front end website with scrolling behaviour for overview of different art pieces and what the gallery has to offer.
The colors pallete is in the grey spectrum with monotone approach for sobriety.

The website shows at first the logo and a painting displayed hanging on a wall in an interior, giving a hint of what the visitor can expect to see and potentially acquire on the site.

_The feature of smooth scrolling does not work in all browsers and the possibility of fixing this with a Java Script is out of scope of this MS1_

The flow goes below to a gallery statement explaining who they are and what is their mission, to engage visitors in a site that not only sells art but also helps. A link to VU Medical Centre is in this section which opens in a separate tab.

Then, the gallery section appears with a selection of paintings and drawings. This gallery displays in a modal with easy navigation in carrousel or in group.

Sections are separated by images of paintings displayed on walls with Parallax effect, giving a smooth navigation feeling.

The Contact Us section is a form with "required fields" and drop down menu to select style of painting desired.

For users unfamiliar with Amsterdam, an embedded map shows how to get to the gallery.

There are several hover effects in the footer, over the titles and in social media icons.

# User Stories

## As User

- As user, I want to see good images of paintings
- As user, I want to be able to look at the picture in detail
- As user, I want to be able to contact the gallery to ask for a particular style
- As user, I want to be able to call the gallery, so contact details are important
- As user, I want to be see how a picture would look in an interior

## As a gallery owner

- As a gallery owner I want to show a selection of the pieces that we have
- As a gallery owner I want to be able to be contacted through the page
- As a gallery owner I want to promote the work
- As a gallery owner I want to connect with art enthusiasts

# Sections

- The logo
- The navigation bar with links to the different sections
- About Us with a short introduction
- Different images of pieces displayed with parallax effect to give a dinamic an tridimentional look.
- The gallery, with clickable buttons displaying available pieces
- Contact Us, to email the gallery with questions and queries
- An embedded GoogleMaps with the location to facilitate visitors to find us.
- The Footer, with contact information and social media links

## Existing Features

- The navigation bar collapses with a burger button on smaller screens.
- The gallery displayed in a modal. This has been achieved using Fancybox.
- Contact Us with drop down menu to email the gallery with questions and queries.
- The Footer, with contact information and social media links.

## Using the Contact Us form

Go to "Contact Us"

- The contact fields are required and sending emssages without completing isn't allowed, showing a message to fill the form before sending.
- A preselected set of reasons to contact shows in a drop down menu.

## Features Left to Implement

- In a future release I would like to add a filter of paintings per style.
- I would also like to add a shopping cart and a e-commerce marketplace for customers to select, check out, pay and purchase art pieces.

# Technologies Used

## The project was build with:

* HTML, to structure the website
* CSS, to style the website
* [jQuery](https://jquery.com/), for the modal in the gallery
* [Visual Studio Code](https://code.visualstudio.com/), for the development environment
* [Github](https://github.com/), as the version control technology and GitHub Pages as the webserver technology to publish the website
* [Bootstrap](https://getbootstrap.com/), to utilize responsive elements
* [Font Awesome](https://fontawesome.com/), to utilize icons
* [Google Fonts](https://fonts.google.com/), to utilize different fonts

## Testing

- No testing has been automated. All performed manually.
- We have asked 10 people to act as potential users of the website.
- All the tests below where done manually.
- The tests where done in Chrome, Safari, Firefox and IE

### Using the website

- Open the website and to see a hint of how a large print would look on a wall
- On the Navigation Bar, the user sees the options where to navigate to. The burger button does now collapse back up again in this version. An improved version with JS will be done in next release.
- “Who" explains who KUUA is and what it stands for. It has a link to the institution that KUUA helps with 50% of the profits. by clicking the link a new tab will open with the hospital website.
- “Gallery” the user will go to a collection of paintings and prints that are available in the gallery. The gallery shows in a pop up window the selected image and it changes to different paintings by clicking the arrows right or left, making it easy to navigate.
- "Contact US" scrolls down to a form to select different reasons to contact in a drop down menu. The form offers an intuitive and easy way to get in contact with the gallery.
- "Location" has a Google Map, which worked well in the devices tested.

The website provides a complete overview of what the gallery has to offer. 

In all screens tested the website looks exactly in the desired way and responded to an imaginary user/gallery owner trying to achieve different goals in the site.

There is a display issue identified: on IphoneX Max the website works well portrait but when turned to landscape position the Parallax background images blow out of proportion.
I am currently investigating this issue and plan to fix it ASAP

There is an issue with the gallery when swiping images left or right. after second image next image doesnt show. We are planning to fix this in next release. 

## Deployment

I used Visual Studio Code to write all the code. My website is deployed on Github Pages - To visit, click [Here](https://fabibrachetta.github.io/kuua/)

In order to do this is followed the below steps:

- Create a directory on the local file system.
- In GitHub “Repositories” I’ve clicked on the green “new” button and created a repository with the name of KUUA.
- Select Clone "Clone or download" on Github, copy the link
- In VSCode , select File -> Add Folder to Workspace -> Select the newly created directory
- Select Terminal Window
- In the window, type: git config --global user.name <github userID>
- In VSCode, I’ve created the site, committed and pushed onto repository.
- On GitHub, I’ve clicked on KUUA repository.
- Under KUUA repository name, click “Settings”.
- Under "GitHub Pages", use the Source drop-down menu and select Master Branch for live url.


## Wireframes

Wireframes created in Balsamiq:

You can find the wireframes [here](https://github.com/FabiBrachetta/kuua-ms1/blob/master/wireframes/kuua-mockup.png)

# Credits

## Content

- The content of the website is created by me in its entirety.
- The gallery was created using Fancybox from [Fancyapps](https://fancyapps.com/fancybox/3/) 
- Embedded map using [Google Maps](https://www.google.com/maps/preview)
- I used modules of Bootstrap and styled to my taste

## Media

- The photos used are all created by me. I own all rights to use and publish the images.
- I authorise free use of any image for non commercial use (credits would be appreciated)

## Acknowledgements

- I want to thank in particular my mentor [@guidocecilio_mentor](https://github.com/guidocecilio) for his guidance
- [@Eventyret_mentor](https://www.github.com/Eventyret) for the peer-review adn advice
- [@Guillermo](https://github.com/GBrachetta) for some nice pointers 
- Slack Community in general for the quick and solid support.

## Disclaimer
- I have been not in contact with VUMc nor have I been endorsed. However I have the plan to collaborate with their great work.

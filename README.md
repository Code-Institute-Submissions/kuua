<img src="./assets/images/kuua-logo-circle.png" alt="logocopy" class="center" />

# KUUA

## Pop Art Gallery

A gallery showcasing pieces of art for sale. The gallery collaborates with VUMc in Amsterdam, a hospital devoted to advance research in chronic diseases.
KUUA donates 50% of their profits and aims to become a patron of the hospital.

I've designed and built this website to display and promote Pop Art as a way of both building a business and doing good, hoping to get attention from the public and amplify what VUMc is doing.

Today, the work exhibited is from one painter (me), but it is the aim of KUUA to become a go-to online gallery for aspiring artists to collaborate.

KUUA is the name of a .com owned by me. 
The logo has been created by me

## UX

This website has been created as a static, one page front end website with an overview of different art pieces.
The colors pallete is in the grey spectrum with monotone approach for sobriety.

The website shows when opening the logo and a painting displayed in an interior, giving a hint of what the visitor can expect to see and potentially acquire on the site.

_The feature of smooth scrolling does not work in all browsers and the possibility of fixing this with a Java Script is out of scope of this MS1_

The flow goes below to a gallery statement explaining who they are and what is their mission, to engage visitors in a program that not only sells art but also helps. A link to VU Medical Centre is in this section.

Then, the gallery section appears with a selection of paintings and drawings. This gallery displays in a modal with easy navgation in carrousel or in group.

Sections are separated by images of paintings displayed on walls with Parallax effect, giving a smooth navigation feeling

The Contact Us section is a form with Required fields and drop down menu to select style of painting desired.

For users unfamiliar with Amsterdam, an embedded map shows how to get to the gallery.

There are several hover effects in the footer, over the titles and in social media icons.

# User Stories

## As User

- As user, I want to see good images of paintings
- As user, I want to be able to look at the picture in detail
- As user, I want to know the price of the piece in advance
- As user, I want to be able to contact the gallery to ask for a particular style
- As user, I want to be able to call the gallery, so contact details are important
- As user, I want to be see how a picture would look in an interior

## As a gallery owner

- As a gallery owner I want to show a selection of the pieces that we have
- As a gallery owner I want to be able to be contacted through the page
- As a gallery owner I want to promote my work
- As a gallery owner i want to connect with art enthusiasts

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

- The navigation bar collapses with a burger button
- The gallery, with clickable buttons displaying available pieces. This has been achieved using Fancybox.
- Contact Us, to email the gallery with questions and queries
- The Footer, with contact information and social media links

## Using the Contact Us form

Go to "Contact Us"

- The contact fields are required and sending emssages without completing isn't allowed, showing a message to fill the form befre sending.
- A preselected set of reasons to contact shows in a drop down menu.

## Features Left to Implement

. In a future release I would like to add a filter of paintinGs per style.
. I would also like to add a shopping cart and a e-commerce marketplace for customers to select, check out, pay and purchase art pieces.

# Technologies Used

## The project was build with:

. HTML to code the content
. CSS to style
. Bootstrap to add features
. Fontawesome preset icons
. JQuery for the gallery

## Testing

No testing has been automated. All performed manually.

In all screens tested the website looks exactly in the desired way and responded to an imaginary user/gallery owner trying to achieve different goals in the site.

There is a display issue identified: on IphoneX Max the website works well portrait but when turned to landscape position the Parallax background images blow out of proportion.
I am currently investigating this issue and plan to fix it ASAP

## Deployment

I used Visual Studio Code to write all the code. My website is deployed on Github Pages - https://fabibrachetta.github.io/kuua-ms1/

In order to do this i followed the below steps:

- Create a directory on the local file system.
- Create a repo on Github.
- Select Clone "Clone or download" on Github, copy the link
- In VSCode , select File -> Add Folder to Workspace -> Select the newly created directory
- Select Terminal Window
- In the window, type: git config --global user.name <github userID>

git clone <URL from github link copied earlier>
(guidance courtesy of http://www.notyourdadsit.com/blog/2018/4/3/cheatsheet-setup-github-on-visual-studio-code)

## Wireframes

Wireframes created in Balsamiq can be found here:

<img src="./assets/assets-readme/kuua-mockup.png"/>

## Link to the image can be found here:

https://github.com/FabiBrachetta/kuua-ms1/blob/master/assets/assets-readme/kuua-mockup.png

# Credits

## Content

- The content of the website is created by me in its entirety.
- The gallery was created using Fancybox from fancyapps https://fancyapps.com/fancybox/3/
- Embedded map using Google Maps courtesy of https://google.com/
- I used modules of Bootstrap and styled to my taste

## Media

- The photos used are all created by me. I own all rights to use and publish the images.
- I authorise free use of any image for non commercial use (credits would be appreciated)

## Acknowledgements

- I want to thank in particular my mentor @guidocecilio_mentor, also @Eventyret_mentor for first peer-review, also @Guillermo for some nice pointers and the Slack Community in general for the quick and solid support.
- I have been not in contact with VUMc nor have I been endorsed. However I have the plan to collaborate with their great work.

# Portfolio-Website-New

[Website Link](https://portfolio-website-new-gilt.vercel.app/)

[Github Repo Link](https://github.com/CallanVass/Portfolio-Website-New)

[Presentation Link]()

## Description

#### Purpose

The purpose of my website to create a professional space that potential employers might visit to gain a speedy insight into my tech stack and provide an easy way for them to contact me if they so wish. It also gives me a place to store my projects, and, in a way, to provide me with a certain level of introspection. Oh, and to pass my assignment!

#### Functionality / Features

##### NAVBAR

Since every page has a navbar and footer, let's explore these first to keep this README DRY. 

The navbar sticks to the top of the screen no matter what. Upon adjustment from mobile to desktop, it goes from being centered to taking on the property of flex: flex-end, which sends it to the right side of the page.

The buttons are animated so that when hovered over they turn the pink colour of the currently navigated page, indicating to the user where they will go. This obviously changes depending on which page your on, so the user always sure where they are.

The transparent white background of the navbar container itself allows for the background image to take presedent of the visuals.

##### FOOTER 

The footer is comprised of two divs, one containing the copyright statement, and the other giving another miniature navbar of sorts. The text on the bottom div is spaced evenly with the three site navigation words. Home, Connect, and Blog. This allows for ease of access regardless of where your cursor is on the page.

The text of the second div is also animated to be pink when hovered over (originally white).

Both divs are coloured to black and stretch 100% of the viewport width. 

##### PAGES:

The site features 4 main types of pages, each with an independent background image. These are:

##### Home

The home section serves as a landing page for the site. Like all the other pages, it is colourful. However, the colours used in the home section are a very transparent orange, which suits the image behind. The features of the section are:


- An inspirational quote up the top (in case motivation runs low). This quote actually changes depending on mobile/tablet view-widths. It's achieved by having both quotes on the one HTML and setting the DISPLAY value to HIDDEN once a certain min-width is reached
- Responsive tech stack blocks that change from one column to two for mobile and desktop respectively

This page, like all the others, is designed to be responsive and therefore operates at whichever viewport size necessary. Like the other pages, it was also designed with the "mobile first" mindset, and then built upwards from there.

#### Connect

#### Blog

#### Blogpage 

### Sitemap

![Sitemap](docs/sitemap.png)

### Screenshots

**Please note that some screenshots show repitions of the background image in the page. This is due to image sizing. The site does not look like this.**




### Target Audience

Potential employers, teachers, possibly other students. People well-versed in tech.

#### Tech Stack:

- HTML for markup 
- CSS for stylesheets
- Vercel for deployment.
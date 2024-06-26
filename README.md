#   Blood Red
## Website for fictional rock band
### Portfolio Project 1 - Jamie Mcstay

![Blood Red website as it appears on all screens](docs/testing/am-i-responsive-image.png)

## **[Live site](https://jamiemcstay.github.io/Project-1/)**

## **[Repository](https://github.com/jamiemcstay/Project-1)**

## Table of contents

1. [ Project planning](#planning)
2. [ Features](#features)
3. [ Technology](#technology)
4. [ Testing ](#testing)
5. [ Bugs ](#bugs)
6. [ Deployment ](#deployment)
7. [ Credits ](#credits)
9. [ Acknowledgments ](#acknowledgements)

<a name="planning"></a>
## Project Planning

I decided to make a website on a fictional rock band and did some research into some popular bands and how their websites looked.


![Websites referenced during planning stages](docs/research/website-research.jpg)

After researching I began a UX design plan that was in line with what I had seen across numerous of the websites that I had reviewed.


## UX Strategy

### User Stories

- Are existing fans of the band.
- Are visiting the website to learn more about the band or they are potential fans.
- Want to be able to hear about the bands touring schedule.
- Want to have access to the bands music.
- Want updates on anything new that happens with the band.

### Site owners/bands goals

-  Want to promote their music.
-  Want to promote their touring schedules.
-  Want to increase their fanbase and listener base.
-  Want to keep vistors/fans updated in anything happening with the band. 

## Scope

- The website should contain a navigation menu, main content areas on each page and a footer.
- It should contain a section that promotes new music. 
- There should be some imagery of the band on the website.
- There should be information on the website about touring schedule.
- Visitors should be able to listen to the bands music.
- There should be a way that existing fans can opt-in to more integrate themselves within the bands community, and where new fans can sign up to learn more about the band. 

## Structure

I decided that the scope of the project could be met with three pages on the website:

- Home
- Tours
- Music

Across all pages as is consistent on websites, there will be a header with responsive naviagation bar, a main content area, and a footer that contains a form where fans can sign up to a newsletter. 

### Homepage

- Should serve as a summary of where the band are at currently and the most recents developments as a band.
- Should contain a welcome section/hero section that highlights the most recent development the band would like to promote in the context of a new album release, or a tour. 
- Should contain some imagery of the band. 

### Tours

- Will serve as a page where visitors can view tour dates, check availability of ticktets, and be able to buy tickets for upcoming shows. 

### Music

- Will allow visitors to be able to listen to the music of the band.
- Will allow visitors to watch videos of the band. 

## Skeleton

I used figma to build wireframes of the different pages on the site. I decided to design the website mobile first.  

![Screenshot of the homepage wireframe in figma](docs/wireframes/wireframes.jpg)

### Homepage

- Will feature an initial section thats promotes the most recent update about the band such as an album release or upcoming tour.
- Will feature some imagery of the band.
- Will feature a couple of tour dates with a link to the tours page where more dates can be seen. 

### Tours page
- Will feature a list of upcoming tour dates locations, dates and ability to purchase tickets.

### Music page

- Will feature some of the bands music that the visitors can listen to.
- Will feature some videos of the band that the visitor can watch. 

## Surface

### Typography 

When designing the surface plane in figma, I used: 
- Krona 1
- Inter

However, when making the real website I preferred the look of inter as a font on its own, so I used that soley.

### Color

To allow for the site to meet the requirments in terms of accessibity and having a good contrast ratio, I opted to use colors that I knew would stand in contrast to eachother: 
- Black 
- Red (or eventually rgb(199, 0, 0))
- White

#### Homepage

![Image of surface plane design of homepage](docs/wireframes/home-surface-plane.png) 

#### Tours page

![Image of surface plane design of tours page](docs/wireframes/tour-surface-plane.png)

#### Music page

![Image of surface plane design of music page](docs/wireframes/music-surface-plane.png)


<a name="features"></a>

## Features

### index.html 

#### Navigation menu

The navigation bar was developed mobile first following the tutorial in the Love running project to create a hamburger menu on smaller screens. Flex was used to space out the navigation menu items on larger screens. 

##### Desktop 

![Image of nav bar on desktops](docs/features/nav-bar-desktop.png)

##### Mobile

![Image of nav bar on mobile](docs/features/nav-bar-mobile.png)

#### Album release section

The album release release section shows 

- Cover art of the new album release of the band
- Reviews from popular editorials
- Links where users can stream or buy the record. 

The design moved on from my initial design as can be seen in my figma designs. I used microsoft image generator and open art AI to bring together an album cover that suited the look of the website and the image of the band.  

##### Desktop

![Album section on desktop](docs/features/album-section-desktop.png)

##### Mobile

![Album section on mobile](docs/features/album-section-mobile.png)

#### Singer Image

I wanted to break up the sections of content on the homepage, and as I had seen on multiple other band websites imagery of the band on the site can create a sense of familiarity with exisiting fans/users and let new users know who is behind the music.  

I found an image on unsplash that I used for this purpose. However, when enlarged the image was pixilated and didn't look right. I then processed the image through the open art AI application that sharpened the image, and changed the singer from male to female.

![Image of lead singer on homepage](docs/features/lead-singer.png)


#### Tours section on Home Page

This section is a summary of the main tours page, but can entice a user who is interested in going to a show to purchase a ticket, or click the more dates button and view all the dates of upcoming shows.

The tour dates information is a flex column on mobile and using flex and changed to rows to fill the surplus space on larger screens. 

##### Desktop

![Image of tour dates on the home page of the website as it appears on desktops](docs/features/tour-dates-home-desktop.png)

##### Mobile

![Image of tour dates section on the home page of the website](docs/features/tour-dates-home-mobile.png)

#### Footer 

The main purpose of the footer in this website was to provide links to social media, and a form for users to subscribe to a newsletter:

- Keep up to date with touring schedules 
- New releases 
- New developments that happen with the band 

Within the form, I used a required attribute on the input elements to ensure the user enters a name and email address befor submitting their information. 

Also, I included some links that are standard in terms of a copyright tag,  a link to the designers webpage, and a link to the  cookie policy.

##### Desktop

![Image of footer as it appears on desktops](docs/features/footer-desktop.png)

##### Mobile

![Image of footer as it appears on mobile](docs/features/footer-mobile.png)


### tours.html

The tours page inlcudes more concert dates than are featured on the homepage. 

In order to vary the aesthetic of the site and offer some variation between the pages I used the image from the homepage and fixed it to the background. As a user/fan this would again create a sense of famility with the lead singer and the band. 

##### Desktop

![Image of tours page on desktops](docs/features/tours-page-desktop.png)

##### Mobile

![Image of tours page on mobile](docs/features/tours-page-mobile.png)

### music.html

The music page features a section for listening and for watching videos of the band.
Given that Blood Red are a fictional band, I didn't have original audio and video files, or actual an actual spotify/YouTube account that I could use to embed songs or videos from.  As an alternative I used audio files that I downloaded from Uppbeat.io and used audio elements to feature them on the page. Then, I embedded some youtube videos of other bands.

#### Listen Section

The listen section features an album and single with cover art for both, and a list of the relative songs for each release. I put the album and single containers into a flex container so it would appear as a column on smaller screens, and side by side on smaller screens. This section provides value to new users as they can listen to new records, and if they like what they hear back opt to purchase the record. 

I would have preferred to have been able to style the audio controls such as the play button and playback bar, however this is not possible with audio elements. 

I think it would have suited the aethetic of the website if there was some red, white and black in these audio elements, and would be noted if building a similar site again. 

Please note that only the first three audio tracks are playable. This is due to long loading times when every audio element had a src element nested in it, and removing most of them suffiently improved the performance of the site. 



##### Desktop

![Image of listen section on desktop](docs/features/listen-section-desktop.png)

##### Mobile

![Image of listen section on mobile](docs/features/listen-section-mobile.png)

#### Watch Section 

The watch section allows users to watch music videos of the band. I inlcuded four videos and a button/link below where the user can visit the youtube page of the band.

Similar to the listen section there is a flex container for the watch section set to wrap, so there are rows of two videos on desktops, and videos in a single column on mobile devices.

This section again provides value to the user by being able to watch videos of their favourite songs or discover new music, and be linked to the bands youtube account through the watch more button to listen further. 

##### Desktop 

![Watch section on desktops](docs/features/watch-section-desktop.png)

##### Mobile

![Watch section on mobile](docs/features/watch-section-mobile.png)

### response.html 

Once the user enters their information correctly into the inputs of the 'Subscribe to newsletter' form in the footer, they are redirected to response.html which recognises their submission, and offers them a free download of a new single.

This will give the user clarificaiton that their information has been recieved and that they are signed up to the newsletter, as well as offering them something in return for their support of the band. 

Also, I added some buttons that the user can click to download the single, return to the homepage, or to the bands spotify page. 

##### Desktop

![Response page on desktop](docs/features/response-desktop.png)

#### Mobile

![Response page on desktop](docs/features/response-mobile.png)

### Features left to implemenent

In future, features that could be added to improve the site could be:

#### Store

If revisiting this project I would like to add a store where users can buy merch such as physical records or branded clothes. 

#### Gallery

With some further research more pictures that are suitable could be found and a gallery page built around those images to create a realistic image of the band. 

#### About Page

Taking influence from some other bands a brief history of the band could be created, and a suitable about page be built around that story. 

#### Buttons

I used red and white buttons across the page that would stand out from the darker backgrounds on the website.

These buttons are used as calls to action and to guide the user to the most parts of the website or to enternal sites: 

- 'Tickets' - link to ticketmaster
- 'Steam' - link spotity
- 'Buy' - link to tunes
- 'Subsribe' - links to a message in respnse to subscription
- 'Watch more' - links to Youtube
- Download, Listen, Homepage - link to itunes, spotify and index.html

I implemented a hover effect on the buttons, changing them to a brighter red, to enhance interactivity and validate user interaction. 

Also, for the sold out buttons, I disabled the cursor so they are unclickable. The contrast of the poor contract ratio of the sold out buttons is on purpose, as these buttons are relative to dates that are sold out and allow the buttons for available dates to stand out. 

![Stream and buy buttons in album section on homepage](docs/features/stream-buy-buttons.png)

![More dates button in tours section on homepage](docs/features/more-dates-button.png)

![Subscribe button on homepage](docs/features/subscribe-button.png)

![Watch more button in watch section on music page](docs/features/watch-morer-button.png)

![Tickets button on tour dates](docs/features/tickets-button.png)

![Sold out button for tour dates](docs/features/sold-out-button.png)

![Reponse page buttons](docs/features/response-page-buttons.png)

## Technology

### Figma 

I used figma to develop my designs for the web pages. 

### Html

I used html to build the structure of the webpages.

### css
I used css to add style to the front end of the website. 

### Github

I used github to host my websites code. 

### Gitpod

I used gitpod to write my code.

### Git 

Git was used as version control of the site. 

### Google Fonts

I imported the inter font into my project to use on the website. 

### Font Awesome 

I used font awesome for all icons on the site. 

### TinyPNG 

I used TinyPNG to compress my images and optimize for the website. 

### Microsoft AI image Generator

I used this generator to generate images for an album cover. 

### Open Art AI 

I used this to generate images for the website. 

## Testing 

To test the websites functionity across different browsers I utilized: 

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari 

#### Responsiveness

Throughout the development process I used dev tools in Google Chrome to test the sites responsiveness across different screen sizes. 

#### Third party testing

My three housemates were sent the link to the site and asked to:

- Click on every link/button. 
- Play the audio files.
- Enter their information into the form in the footer. 

They reported that it was intuitive, all the links worked, and the form responded as it should. 

### Google Lighthouse

When testing the score for the website through Google Lighthouse. I encountered an issue with my site being slow on the performance metric.

To fix this: 

- I tidied up my CSS file and deleted any unused images from the images folder. 

- Removed the src element from all but but the first three audio tracks/elements on the listen page, so please note that only the first three audio tracks are playable.

- Re-exported all my image files from figma at a lower file size, which resulted in a degredation of quality, but will massively improve the experience for the user.

These fixes increased the performance score from between 27%-31% to between 80%-95% across all pages. 


#### index.html

![Google Lighthouse score on index.html page](docs/testing/index.html-lighthouse.jpg)

#### tours.html 

![Google Lighthouse score on tours.html](docs/testing/tours.html-lighthouse.png)

#### music.html

![Google Lighthouse score on music.html page](docs/testing/music.html-lighthouse.png)

#### response.html

![Google Lighthouse score on response.html page](docs/testing/response.html-lighthouse.png)

### HTML Validation

When putting my html files through the html validator, there were some errors that were easily rectifiable:

- aria-labels were placed in the i elements instead of anchor element in the footer  icons, so they were moved to the anchor elements. 
- Frameborders should be moved from the iframe html element to a iframe rule with border: none in css.
- Source elements within audio elements had an incorrect type. type="audio/mpeg" was added. 

#### index.html

![Screenshot of html validation report for index.html](docs/testing/html-validation-index.png)

#### tours.html

![Screenshot of html validation report for tours.html](docs/testing/html-validation-tours.png)

#### music.html 

![Screenshot of html validation report for music.html](docs/testing/html-validation-music.png)

#### response.html 

![Screenshot of html validation report for response.html](docs/testing/html-validation-response.png)

### CSS Validation

![Screenshot of jigaw csss validation](docs/testing/css-validation.png)


## Bugs 

- Applied border: none to an iframe rule to remove frameborders from iframes. 

- Moved main element below fixed header with padding.

- Issue with image file sizes and loading speed fixed by re-exporting images at smaller file size. 

- Reducing audio src elements to three to speed up loading times on music page and increase performance score.

- Aligning buttons in album section correctly fixed with flex and media queries.

- Aligning "Watch More" button on music page fixed. 

- Removed lang=en from spotify icon hyperlink to take out of pop up when hovering over icon. 

- Replace button elements that mistakenly had hrefs with anchor to allow for correct navigation of site features. 

- Fixed file names and file paths to standardise and optimize compatability across all browsers.

- aria-labels placed incorrectly in the i elements in the footer as oppossed to the anchor elements, which was fixed. 

### Bugs not fixed 

#### Contrast ratio of small red text

When putting my site through Wave Accessibility for an evaluation of its accessibility, it reported poor contrast of the small red text in the tours section and within the reviews of the album section on the home page. 

I acknowledged this and attempted to change it to a bolder text,  but opted to leave the text as it was because I believe the text worked as part of the design, and there as good contrast with the other elements around it. 

![Wave report of of contrast score](docs/testing/wave-score.png)

## Deployment 

The steps I followed to deploy my project were as follows:

1. Accessed my gituhub respository.
2. Clicked on settings tab. 
3. Selected the pages menu in the sidebar. 
4. Under source I selected to deploy from the main branch from the dropdown menu.
5. Leave /root as default option.
6. Click Save.

I then waited for a couple of mins, refreshed the page and my sites link was accessible through the repository. 

## Credits

### Content

#### Images were sourced from unsplash.com and from using Open Art AI and Microsoft Image generator

>Album Image was made using Microft AI Image generator: 
https://create.microsoft.com/en-us/features/ai-image-generator

>Singer Image on home page is an AI edited version of this image from Melanie van Leeuwen on Unsplash: https://unsplash.com/photos/man-playing-guitar-while-singing-QA-qQfWJM0E

>Echoes of the fallen single cover art by Jon Tyson from Unsplash: https://unsplash.com/photos/black-white-and-red-abstract-painting-WB9TRkyrlzk

>Black background image is an AI edited version of this image by Brian Patrick Tagalog on Unsplash: https://unsplash.com/photos/grayscale-photography-of-rock-formation-_8hGFBxWD0A

>Youtube video 1: Tears Don't Fall by Bullet for my valentine: https://www.youtube.com/watch?v=9sTQ0QdkN3Q

>Youtube video 2: How you Remind Me by Nickelback: https://www.youtube.com/watch?v=Aiay8I5IPB8

>Youtube video 3: Kryptonite by 3 Doors Down: https://www.youtube.com/watch?v=xPU8OAjjS4k

>Youtube video 4: Wherever you will go by The Calling: https://www.youtube.com/watch?v=iAP9AF6DCu4

>Favicon from FLATICON: https://www.flaticon.com/free-icon/blood-drop_893529?term=blood+drop&page=1&

>I took a lot of inspiration from multiple websites, but in particular from the Green Day website, which can be found here: https://greenday.com/tour

>Social Media Icons were from Font Awesome: https://fontawesome.com/icons/twitter?f=brands&s=solid

>ChatGPT was used to generate the names of song and album titles for the band


### Audio was sourced through uppbeat

>Audio Track is Pursuit by Abbeynoise from Uppbeat.io: https://uppbeat.io/track/abbynoise/pursuit

>Audio Track 2 is Night Thunder by Abbeynoise from Uppeat.io: https://uppbeat.io/track/abbynoise/night-thunder

>Audio Track 3 is Into The Red by Trinity from Uppbeat.io: https://uppbeat.io/track/trinity/into-the-red

### Resources

>Nav toggle code for smaller size screens credited to Love Running Tutorial from Code Institute.

>Other resources used during the building of this site as reference include:
- MDN Web Docs
- Code Institute Content
- W3 Schools


## Acknowledgements

- Thanks to the Code Institue tutors and staff for support throughout the project.

- Thanks to my mentors Alan Bushell and Julia Konovalova for their advice through developing this project. 















 














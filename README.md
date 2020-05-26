*DISCLAIMER:* This project is for educational purposes only, there is no affiliation or connection to the real Monkees and their brand/trademarks and should not be viewed nor used as such.

# The good old Monkees!
A sixties themed website with the power of modern technology. A place where anyone can find out more about this incredible band! This site is meant to inspire and invite people to enjoy some of the content created by the Monkees. Anyone will be able to easily find out more about the bandmembers and even contact them for a possible future gig. The whole site has been themed so it's a fullon 60s experience, but not so much that it gets overwhelming.

When first opening the site, one is met with a full on image of the legendary Monkees, below that a quick view of the individuals and links to their info. Below that a video can be viewed and listened to, to get a taste of their work. A second page has been created to read more about the bandmembers. Wide open on large screens, but small on phones, with an option to expand information about the specific bandmember. The site would not be complete with some samples of the Monkees, so on the media page a caroussel with pictures and a few songs are accessable.
Lastly a way to contact the band has been created on the hire us! page.


## UX
This project will meet the demands of the band 'The Monkees!', the band needs a place where people can see and hear their music, find out more about them and the means to contact or hire them. It is a band that plays music from the 60's. The relevant audience will be looking for a place that represents this decade since the band was and still is well known for that time period. Current and potential fans of the band will be from all ages and culture, although there will be an emphasis on 40+ ages and a western background. A responsive website will be very suitable for this audience and its needs, especially since all kindgits of devices will be used to search for and enjoy the band's content (due to the large range of user age). It should look great on mobile phones up to widescreen monitors.

It will be a B2C audience mostly, so it needs to focus on emotional triggers. It needs to be abundantly clear it is a site of the Monkees, it all has to do with the 60s, maybe 70s and it's about music and/or a band. The landing page needs to make this very obvious. So the name, a big image of the band and 60s colouring is needed.
To add to clarity, it should be obvious there are a lot of media files present and there is a way to contact and/or hire the band. 
Overall, due to the intense colouring and abundance of images, it is important not to overload the site. If possible, walls of text should be avoided, especially on smaller viewports. Only when a user wants to read up, there should be a seperate and dedicated place to do so (on small viewports).

With this setup in mind the site will have bright colors, based off of the main (hero) picture on the landing page. By using an eyedropper the colors can be extracted from the image and with a color calculator the right contrast colours with the background blue color ('#c8e3ee') can be created. For the navigation menu the colour of the logo(brand) was used. This ensured that the navbar really stood out.

The site will focus on the following users:

- Fans
- Potential employer (who wants to hire the band)
- Potential fan

#### User stories
* Fan:
    * As a fan I want to see images of the band(members).
    * As a fan I want to listen to music of the bandAs a fan I want to see videos of the band.
    * As a fan I want to be able to go to social media pages of the band.
    * As a fan I want to be able to go to the spotify page of the band.

* Potential fan, applies to user stories of a fan, added to that the following:
    * As a potential fan I want to be able to get a look and feel for the band.
    * As a potential fan I want to find out more about the bandmembers.

* Potential employer, the above stories apply but also:
    * As a potential employer I want a way to contact the band.
    * As a potential employer I want a way to hire the band.

#### Mockups
I have drawn up wireframe mockups in Balsamiq, the PDF with the images can be found in two places:

* Within the project file structure at ./mockups/mockupsmilestone01.pdf
* By clicking [here](https://github.com/codewouter/milestone1-theMonkees/blob/e99fb4fcf34ac7f5e0c9ddaf211a423f6b3557fa/mockups/mockupsmilestone01.pdf)

Please note that the first three balsamiq images are the landing page (home), info page (in the final product called 'about') and media page for the mobile layout, the second set of three are for desktop/wide screens.

## Features

#### General
* A navbar that is instantly recognized for wide viewports. For phones and the like scaled down to a hamburger menu.
* Clear icons at the bottom (footer) to social media pages and spotify on every page so they can be easily visited.
* All sections on all pages seperated by a light bar, consistent through all pages.
* Box shadows on all images and large text headers. Except on the hero image which looked better without.

#### index.html
* Hero image right at loading the landing page to instantly make clear what the site is about, combined with the big brand top left.
* Bandmembers with pictures and names to create curiosity or recognition effect. Button to go directly to the about page for more info.
* Playable video to entice viewers to start listening right away. Also a button to go directly to more media content.

#### about.html
* Description and pictures of all bandmembers for more background info. On phones the text is hidden until a button is pressed and the field opens up, collapsing again when pressed again. **!Note from student: Kind of the highlight of the site for me, because I was hellbent on getting it to work without Javascript, and finally succeeded :) )**

#### media.html
* Caroussel with various images. Automatically sliding, and buttons to manually speed up the rotation.
* Four songs with the relevant album art. Playable and searchable within the song.

#### hireus.html
* Contactform to contact the band and hire them. Several features in place to prevent wrong information. Only numbers in the phone field, valid emailadress structure, no empty fields 

## Technologies Used
* HTML 
    * General markup
* CSS
    * Styling HTML
* Bootstrap 3 and 4 (https://getbootstrap.com/docs/4.0/getting-started/introduction/)
    * Obligatory because the course was largely centered around it. When I started, Bootstrap 4 was not being used yet, later it had become the staple and a lot of lessons were rewritten. I did not have time to review everything so I learned Bootstrap 4 on-the-fly. I ended up using a lot of it, but I might not be aware of certain componenents/classes that could be better used.
* Font Awesome (https://fontawesome.com/)
    * Used for several icons and fonts.
* Google fonts (https://fonts.google.com/)
    * Used for several fonts.
* Box shadow generator (https://www.cssmatic.com/box-shadow)
    * To create a feeling of depth on the site. 
* Validators
    * Validation of the HTML code: https://validator.w3.org/
    * Validation of CSS code: https://jigsaw.w3.org/css-validator/
* Color calculator (https://www.sessions.edu/color-calculator/)
    * To determine the right colors for the site in contrast to the blue background.
* Balsamiq (https://balsamiq.com/)
    * used to create the mockups.

## Testing
For testing purposes I used the following resolutions (both in portrait and landscape) from chrome's developer tools on a windows 10 PC:
- Iphone X (375x812), this is a very narrow phone which presented some layout challenges.
- Ipad (768x1024), one of the most common devices
- Laptop with HiDPi screen (1440x900), to test laptop screens
- Fullscreen (2560x1440), my personal settings for Fullscreen

Also on the following devices:
- Galaxy A5 (2017)
- Ipad Air (2015)

This way most often used screensizes can be tested. For all of the above the following has been tested.

Navigation bar (all pages):
- Layout throughout the pages. No misplaced/misaligned text or image is present in any of the tested resolutions.
- All (hyper)links  are functioning properly. Including the 'Guitar' logo as a home-link.
- Hamburger menu appears and disappears at relevant breakpoints.
- Hamburger menu collapsing/expanded correctly, all links active.

Footer bar (all pages):
- All links to social media/spotify functioning properly.
- Footer on very small phone viewports is very thin (eg. IphoneX), making the footer social icons a bit small. For purposes of this site it is acceptable (spacing is sufficient to support touch).

Landing page/Home page.
- All hyperlinks functioning properly
- All images and video (and text/buttons) scaling, postioning and reacting properly to all viewports/devices.
- Video plays correctly, including sound.
- The video will not display when loaded in the Safari Browser on the Ipad Air, when played it displays correctly.

About page
- All images and text scaling, postioning and reacting properly to all viewports/devices.
- On small viewports (eg. phones), text correctly expands/collapses at 'about' button press.

Media page
- All images, musicplayers and text scaling, postioning and reacting properly to all viewports/devices.
- Carousel aligned properly, slideshow is activating and manual previous/next slide arrows are functioning.
- All 4 musicplayers are playing sound correctly
- Download links in the players are working and downloading

Hire us! - page
- The Contactform detects empty fields and prompts the user for text. (Mandatory fields are Name and email, other fields may stay empty. )
- The contactform detects emailadresses not following basic format <text>@<text>
- Only able to fill out characters that are relevant for a phonenumber in the field phonenumber.


### Bugs/Problems Encountered
* The video on the landing page will not display when loaded in safari, when played it displays correctly.

* On may 3rd I ran into a problem with git push. It refused to push my repository because of a file was too big. The file concerned was the videofile. I removed a few seconds from the start because the start of the video was black, and so the videoplayer displayed a black screen on the landing page. Using MS Video Creator I had not noticed that the file got bloated from 16mb to 160mb. I did several commits since then. The challenge was to remove said file from the git history. After a few long sessions on slack I turned to youtube to learn more about git. In the end I used git rebase interactive to remove the file. After everything was pushed I re-added the correct file. I removed a lot of commits which were just attempts to push without anything relevant changed, I did leave the relevant history intact so the process can be seen in the git commit history.

* On the About page, the description text blocks of the bandmembers: To be able to have a toggleable block of text, I need to have specific css code linked to the 4 id's (toggleText01, 02,03,04) to set them as display: block. I set that in a media query (min 768px). Putting said display rule in as class as part of the paragraph will not display the text on wide viewscreens. I have not been able to figure out why, it's ugly code, but the only way I could find how to do it.

## Deployment
This project has been deployed through github, it is freely accessable by visiting my repository [here](https://github.com/codewouter/milestone1-theMonkees). One can find the code there and a link to the live [website](https://codewouter.github.io/milestone1-theMonkees/).
Deployement has been an ongoing process of lots of pushed commits to github. The final product has been deployement off the master branch.

When using gitpod, the site can also be previewed by typing 'python3 -m http.server' in the terminal window and selecting 'make public' in the popup window. Then the option 'Open Preview' should be clicked.

## Credits
#### Content
* All images, video and music files were supplied by Code Institute as part of the assignment, except:
    * Monkees logo: https://www.pngguru.com/search?png=Monkee
    * Favicon image from https://icons8.com/

* The text on the about page was copied from the wikipedia pages of the relevant bandmember.
    * https://en.wikipedia.org/wiki/Peter_Tork
    * https://en.wikipedia.org/wiki/Micky_Dolenz
    * https://en.wikipedia.org/wiki/Michael_Nesmith
    * https://en.wikipedia.org/wiki/Davy_Jones_(musician)

* The implementation of the embedded video was adapted from https://github.com/ananyasitlani/milestone-project
* Structure of features in README.md was copied from https://github.com/ananyasitlani/milestone-project
* Navbar code taken and adapted from a brilliant YouTube video of Academind, https://www.youtube.com/watch?v=23bpce-5s8I&t=616s
* The contactform is largely based off the CodeInstitute's Mini-project-cv
* Used video https://www.youtube.com/watch?v=kEf1xSwX5D8 for the code for the favicon


#### Acknowledgements
* I would like to thank the slack community as a whole and especially Anna Greaves and Simen Daehlin for helping me out so much.
* Many thanks to my first mentor Antonija Simic for shooting down my first attempt, harsh but needed.
* I received inspiration for this project from Ananyasitlani (https://github.com/ananyasitlani/milestone-project). This example project was supplied te me by my first mentor Antonija Simic.
* Thanks to my new mentor Gerard McBride for a kick in the procrastination and pointing out the project is good, stop adding to it and finish up already!
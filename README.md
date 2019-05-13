
solved background picture layout with Anna_lead. 

navbar code taken from bootstrap video
Form based of mini-project-cv

Videocode from other student

When I started Bootstrap 4 was not being used yet, the last weeks it had become the staple and a lot of lessons were rewritten. I did not have time to review everything so I learned Bootstrap 4 on-the-fly. I ended up using a lot of it, but I might not be aware of certain componenents/classes that could be better used.

I wanted to make a website that has the 60s feel of the band while still being a modern-style site. In my first attempt I was trying to be original but it ended up being quite 'oldschool' as my mentor put it, one of the main culprits was using scrollable div's as main text bodies. After thinking it through  I decides to go back to square one and completely redesign. The old site is still on github at:

With the new setup in mind I wanted to have the bright colors as I had them before, based off of the main picture on the landing page. Using an eyedropper I combined the colors of the image with a color calculator to get the right contrast with the background blue color I picked ('#c8e3ee'). The color calculator is at https://www.sessions.edu/color-calculator/

Parts with a lot of content (mediagallery/musicfiles, bandmember descriptions, form) I put in seperate pages, reachable through a navbar. This to avoind clutter on the landing page. I wanted, however, to put some teasers on the landing page which could also lead to the other pages. So I decided to have the bandmembers present on the landing page, and I also put the video there.

For the nav menu I used the colour of the logo that has been added as the brand. This ensured that the navbar really stood out.

On wide viewports, added margin left and right. Having the picture stretch the view-width completely was overwhelming.

On may 3rd I ran into a problem with git push. It refused to push my repository because of a file was too big. The file concerned was the videofile. I removed a few seconds from the start because the start of the video was black, and so the videoplayer displayed a black screen on the landing page. Using MS Video Creator I had not noticed that the file got bloated from 16mb to 160mb. I did several commits since then. The challenge was to remove said file from the git history. After a few long sessions on slack I turned to youtube to learn more about git, 
in the end I used git rebase interactive to remove the file. After everything was pushed I re-added the correct file. I removed a lot of commits which were just attempts to push without anything relevant changed, I did leave the relevant history intact so the process can be seen in the git commit history.

media query based on aspect ratio for carousel and video. Would not fit in screen with relatively low height (xl screens and phones in landscape mode). Could not use query based on width because some phones in landscape have a width that is smaller than an Ipad on portrait.

Using an aspect ratio media query for better carousel size.

Remaining bugs:
*The video will not display when loaded in safari, when played it displays correctly.


*On the About page, the description text blocks of the bandmembers: To be able to have a toggleable block of text, I need to have specific css code to the 4 id's (toggleText01, 02,03,04) to set them as display: block. I set that in a media query (min 768px).
Putting said display rule in as class as part of the paragraph will not display the text on wide viewscreens. I have not been able to figure out why, it's ugly code, but the only way I could find how to do it.

*Footer on very small phone viewports is very thin, making the footer social icons a bit too small.

This site is for educational purposes only etc.

ToDO:

Hover effects on buttons landing page
Navbar layout when not collapsed

solved background picture layout with Anna_lead. 

navbar code taken from bootstrap video

Videocode from other student

I want to make a website that has the 60s feel of the band while still being a modern-style site. In my first attempt I was trying to be original but it ended up being quite 'oldschool' as my mentor put it, one of the main culprits was using scrollable div's as main text bodies. After thinking it through  I decides to go back to square one and completely redesign. The old site is still on github at:

With the new setup in mind I wanted to have the bright colors as I had them before, based off of the main picture on the landing page. Using an eyedropper I combined the colors of the image with a color calculator to get the right contrast with the background blue color I picked ('#c8e3ee'). The color calculator is at https://www.sessions.edu/color-calculator/

For the nav menu I used the colour of the logo that has been added as the brand. This ensured that the navbar really stood out.

On wide viewports, added margin left and right. Having the picture stretch the view-width completely was overwhelming.

On may 3rd I ran into a problem with git push. It refused to push my repository because of a file was too big. The file concerned was the videofile. I removed a few seconds from the start because the start of the video was black, and so the videoplayer displayed a black screen on the landing page. Using MS Video Creator I had not noticed that the file got bloated from 16mb to 160mb. I did several commits since then. The challenge was to remove said file from the git history. After a few long sessions on slack I turned to youtube to learn more about git, 
in the end I used git rebase interactive to remove the file. After everything was pushed I re-added the correct file. I removed a lot of commits which were just attempts to push without anything relevant changed, I did leave the relevant history intact so the process can be seen in the git commit history.

All images, videos and sound files were provided by the Code Institute.



This site is for educational purposes only etc.

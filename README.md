# Sew Social

Sew Social allows people interested in sewing to find information about sewing classes in the inishowen area.  The website is for all levels of sewers, with differnt levels of classes offered in two seperate locations. Users will be inspired by looking at photos of previous creations made in previous classes by looking at the gallery page.

The site will also show how the classes encourage social interaction and mutual support in each class. The site will allow users interested in starting sewing to borrow a sewing maching before commiting to the expense of buying a machine.

![Responsive screens](/assets/media/amiresponsive.png)  

link to the live site here:https://frysop.github.io/sewsocial


## Features 

### Colour Scheme
- I generated a color palette from https://coolors.co
    ![Palette colours](/assets/media/palette.png)  
### Typography
- I chose **Madimi one** and **Roboto** from https://fonts.google.com Google Fonts, with Sans Serif as a backup font in case the fonts are not imported into the site correctly. The fonts are easy to read and attractive for this less formal website.
    ![Fonts](/assets/media/fonts.png)

    
### Navigation Bar


- Featured on all three pages, the fully responsive navigation bar includes links to the Home page, Gallery and Sign Up page and is identical in each page to allow for easy navigation and a positive user experience. There is a toggle feature for mobile devices. 
- Clicking on the logo will return the user to the home page.
- The active bar under each page link allows the user to see clearly what page they are on.
- This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 
 
**Mobile Screen Display-**

![Nav Bar for mobile scereens](/assets/media/navMobile.png)

**Larger Screen Display-**

![Nav Bar for Larger Screens](/assets/media/navTablet.png)


### Hero Image  

- The large colourful background image is designed to catch the users attention. It demonstrates exactly what the site is all about. 
- The Logo and Location are displayed clearly in a text overlay to allow the user to see if the classes are suitable for their needs.
![Landing Page](/assets/media/heroimage.png)

### Reasons to Sew Section
 - This section allows users to see the types of classes available and gives them an idea of what new skill they can learn in each class.
 - Users will see the social side of the classes with a link to the gallery page, showing pohots of other users socialising. 
 - Users can access the gallery from this section to see what previous class attendes have made, encouraging them to imagine what they could create if they took up sewing.

![Reasons to Sew](/assets/media/sewReasons.png)

### Class Times Section
- This section will allow the user to see exactly when and where the classes will happen. They can choose a class based on time, location and or ability. 
- This section will be updated if there are time/location changes or more classes are added. 

![Class times/location](/assets/media/classtimes.png)

### The Footer
  - The footer section includes links to the relevant social media sites for Sew Social. The links will open to a new tab to allow easy navigation for the user. 
  - Users are encouraged to search for pictures class creations on social media using #sewsocialmakes on the reasons to sew section of the page.
  ![Footer](/assets/media/footer.png)

### Gallery
  - The gallery will provide the user with images of previous classes' creations, 
  - The images will show the user what they can aspire to create by attending the class.
  - The User will see photos of a class socialising and drinking coffee on breaks, emphasising the friendly, supporting ethos of each class.

![Gallery](/assets/media/gallery.png)

### The Sign Up Page

  - This page will allow the user to get signed up to their class of choice and start their sewing journey. The user will be asked to submit their full name and email address. The user can also request to borrow a sewing machine.

![Sign Up](/assets/media/signup.png)

### Features Left to Implement

- I would like to add direct links to social media pages showing class creations.
- As the class numbers grow I would like to offer longer sewing workshops (day/weekend) focusing on a specific design, such as bag making, formal wear etc. There would be seperate HTML pages and signup sections for this.

## Testing 
 - Tested on Chrome, Firefox and Safari -correctly displayed and responsive on all browsers. 
 - Tested on IPhone, IPad, Macbook, laptop and android mobile phone-correctly displayed on all devices.

    - All links to social media are working and open in a new page.
    - All internal links work.
    - The Line under the links in the nav bar is active on each correct page.
    - The signup form works as expected and returns the Code Institute form dump page.
 - Code was tested during writeup and errors were fixed at the time.
        - I found a solution to removing the small line under each picture in the gallery from [geeksforgeeks.com](https://www.geeksforgeeks.org/how-to-get-rid-of-the-gap-under-the-image/) by setting the line height to zero.



### HTML-Testing
All HTML pages were tested through the official [W3C validator](https://validator.w3.org/nu)
 - The index.html page returned no errors.![Html No Error](/assets/media/htmlNoErrors.png)
 - The gallery.html page returned a syntax error: ![Gallery Error](/assets/media/galleryhtmlerrors.png) I corrected those errors and ran the code again. It returned a warning error:![Gallery Warning](/assets/media/gallerywarning.png) I added a headding and made it invisible using css. This cleared all errors. ![Gallery No Error](/assets/media/galleryNoError.png)
 - The signup.html page returned the following error:![Signup error](/assets/media/formerrors.png) I removed the duplication and it cleared the error.![Signup No Error](/assets/media/signupNoError.png)

### CSS-Testing
  - One error was found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator):![CSS error](/assets/media/csserror.png). I corrected the syntax and the error cleared.![CSS Error Cleared](/assets/media/cssNoError.png)

### Lighthouse
Lighthouse revealed a weak performance especially in the gallery page due to the large images used. I changed the images for smaller sizes resulting in an improvement in performance.

 - Home page:![Index Lighthouse](/assets/media/indexLighthouse.png)
 - gallery page before change in image size:![Gallery LH before](/assets/media/imagelighthousebefore.png)
 - Gallery page after changes:![Gallery LH after](/assets/media/galleryafter.png)
 - Signup page before image size change:![Signup before](/assets/media/lighthouseSignup.png)
 - Signup page after changes:![Signup after](/assets/media/signupafterlighthouse.png)

### Unfixed Bugs
- N/A

### Deployment

- The site was deployed to GitHub pages. 
- The link to the github repository can be found here -https://github.com/frysop/sewsocial.git
    1. Log in to [github](https://github.com/)
    2. Search for the repository frysop/sewsocial or click on the link above.
    3. Select the settings menu.
    4. In the left hand menu under Code and Automation, select the pages tab.
    5. Under the Build and Deployment section, select main from the branch menu. Then select root from the dropdown folder tab and save.
    6. The URL for the live site will be listed at the top of the page(It may take a few minutes to appear and a browser refresh).
- link to the live site here:https://frysop.github.io/sewsocial

## Credits 

### Code Used

- Line removal under pictures in gallery-[geeksforgeeks.com](https://www.geeksforgeeks.org/how-to-get-rid-of-the-gap-under-the-image/)
- Code Institute Love Running module.
- All Icons used were taken from [Font Awesome](https://fontawesome.com/)
- Hex colours to RGC converted on [rapidtables.com](https://rapidtables.com)
- convert jpg images to webp [pixelied.com](https://pixelied.com/)
- -compress images to make site more responsive[tinyPNG.com](https://tinypng.com/)
- [coolors.co](https://coolors.co)- used hero image to generate pallettes https://coolors.co

### Content
- Text content written by myself
### Media
 - All images are from [pexels.com](https://pexels.com)
 
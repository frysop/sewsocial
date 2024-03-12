# Sew Social

Sew Social is a site that allows people interested in sewing to find information about sewing classes in Carn and Clonmany Community Centers.  The website id for all leves of sewers, with differnt levels of classes offered in two locations.

The site will also show how the classes incorporate social interaction and mutual support in each class. The site will allow users without their own sewing machine to rent one from a limited number of stock if they want to try sewing before buying a machine.

![Responsive screens](/assets/media/amiresponsive.png)  

link to the live site here:https://github.com/frysop/sewsocial


## Features 

### Colour Scheme
- I generated a color palette from https://coolors.co
    ![Palette colours](/assets/media/palette.png)  
### Typography
- I chose **Madimi one** and **Roboto** from https://fonts.google.com Google Fonts, with Sans Serif as a backup font in case the fonts are not imported into the site correctly. The fonts are easy to read and attractive for this less formal website.
    ![Fonts](/assets/media/fonts.png)

    
### Navigation Bar  


- Featured on all three pages, the fully responsive navigation bar includes links to the Home page, Gallery and Sign Up page and is identical in each page to allow for easy navigation and a positive user experience. There is a toggle feature for mobile devices. Clicking on the logo will return the user to the home page.
- This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 
 
  **Mobile Screen Display-**

![Nav Bar for mobile scereens](/assets/media/navMobile.png)

**Larger Screen Display-**

![Nav Bar for Larger Screens](/assets/media/navTablet.png)


### Hero Image  

- The large background image is designed to catch the users attention. It demonstrates exactly what the site is all about.  The colours of the background image were used to generate a palette of colours for use in the styling of the website, further improving the user experience and reinforcing the brand image.  

- The Logo and Location are displayed clearly in a text overlat to allow the user to see exactly if the location of the classes are suitable for their needs.

![Landing Page](/assets/media/homehero.png)

### Reasons to Sew Section

 - This section allows users to see the classes available and gives them an idea of what new skill they can learn in each class.
 - Users will see the social side of the classes with a link to the gallery page, showing pohots of other users socialising. 
 - Users can access the gallery from this section to see what previous class attendes have made, encouraging them to imagine what they could create if they took up sewing.


![Reasons to Sew](/assets/media/sewReasons.png)


### Class Times Section


- This section will allow the user to see exactly when and where the classes will happen. They can choose a class based on time, location and or ability. 
- This section will be updated if there are time/location changes or more classes are added. 

![Class times/location](/assets/media/classtimes.png)

### The Footer

  - The footer section includes links to the relevant social media sites for Sew Social. The links will open to a new tab to allow easy navigation for the user. 
  - Users are encouraged to search for pictures class creations on social media using #sewsocialmakes.
  ![Footer](/assets/media/footer.png)

### Gallery

  - The gallery will provide the user with images of previous class mates creations. 
  - The  images will show the user what they can achieve at the classes.
  - The User will see photos of class members socialising and drinking coffee on breaks emphasising the friendly, supporting ethos of the classes.

![Gallery](/assets/media/gallery.png)

### The Sign Up Page

  - This page will allow the user to get signed up to their class of choice and start their sewing journey. The user will be asked to submit their full name and email address. Th.e user can also request to borrow a sewing machine

![Sign Up](/assets/media/signup.png)

### Features Left to Implement

- I would like to add direct links to social media pages showing class creations.
- As the class numbers grow I would like to offer longer sewing workshops focusing on different ideas, such as bag making, formal wear etc. There would be seperate html pages and signup sections for this.

## Testing 

 - Tested on Chrome, Firefox and Safari -correctly displayed and responsive on all browsers.
        - All links to social media are working and open in a new page.
        - All internal links work..
        - The Line under the links in the nav bar is active on each correct page.
        - The signup form works as expected and returns the Code Institute form dump page.
 - Code was tested and during writeup and errors  were fixed at the time.
        - I found a solution to removimg the small line under each picture in the gallery from stackoverflow.com. I set the line height to zero.

### Validator Testing 

#HTML
 - All HTML pages were tested through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
    - The index.html page returned no errors.
    - The gallery.html page returned a syntax error: ![Gallery Error](/assets/media/galleryhtmlerrors.png) I corrected those errors and ran the code again. It returned a warning error:![Gallery Warning](/assets/media/gallerywarning.png) I added a headding and made it invisible using css.
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

hex to RGB color converter rapidtables.compixelied.com-convert jpg images to webp
tinyPNG.com-compress images to make site more responsive
All images are from pexels.com
coolors.com- used hero image to generate pallettes. https://coolors.co/palette/8b79ab-965190-53316a-dee6ed-bd889e



### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)


### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 

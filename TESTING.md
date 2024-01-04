# TESTING


## Compatibility

In order to confirm the correct functionality and appearance of the site, it was tested on the following browsers: Chrome, Firefox, Edge and Safari. The videos for each browser show the website is displaying correctly and all features are working as intended.

  - Chrome:

  ![Chrome](LINK TO VIDEO HERE)

  - Edge:

  ![Edge](LINK TO VIDEO HERE)

  - FireFox:

  ![FireFox](LINK TO VIDEO HERE)

  - Safari:

  ![Safari](Link to video here)

## Responsiveness


+ The website was checked by devtools implemented in Firefox and Chrome browsers.

    - Main Page:

    ![Chrome](INSERT LINK HERE)
    ![Firefox](INSERT LINK HERE)

    - Music Page:

    ![Chrome](INSERT LINK HERE)
    ![Firefox](INSERT LINK HERE)

    - Tour Page:

    ![Chrome](INSERT LINK HERE)
    ![Firefox](INSERT LINK HERE)

    - Contact Page:

    ![Chrome](INSERT LINK HERE)
    ![Firefox](INSERT LINK HERE)

    - Response Page:

    ![Chrome](INSERT LINK HERE)
    ![Firefox](INSERT LINK HERE)

+ The website was also checked with [Responsive Website Design Tester](https://responsivedesignchecker.com/). A video showing the website displaying responsively across a range of different desktop, tablet and mobile device screen sizes is below.

    ![Responsive test](LINK TO VIDEO HERE)
  

---
## Validator testing
+ ### HTML
  #### Home Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Home Page HTML Validator](INSERT LINK HERE)
    
  #### Music Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Music Page HTML Validator](INSERT LINK HERE)

  #### Tour Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Tour Page HTML Validator](INSERT LINK HERE)

  #### Contact Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Contact Page HTML Validator](INSERT LINK HERE)

    #### Response Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Response Page HTML Validator](INSERT LINK HERE)
    
+ ### CSS
  No errors or warnings were found when passing through the official W3C (Jigsaw) validator]

  ![CSS Validator](INSERT SCREENSHOT HERE)


+ ## LightHouse report

    - Using lighthouse in devtools I confirmed that the website is performing well, accessible and colors and fonts chosen are readable.
    
  ### Home page

  ![Home Page Lighthouse](INSERT SCREENSHOT HERE)

  ### Music page

  ![Music Page Lighthouse](INSERT SCREENSHOT HERE)

  ### Tour page

  ![Tour Page Lighthouse](INSERT SCREENSHOT HERE)

  ### Contact page

  ![Contact Page Lighthouse](INSERT SCREENSHOT HERE)

  ### Response page

  ![Response Page Lighthouse](INSERT SCREENSHOT HERE)

---
​
## Bugs
+ ### Solved bugs
    1. The tour table was too large to have all of the information displayed on mobile devices
    
        *Solutions:* a css property of overflow-x: auto; was added to the container housing the table. I learned about this fix from a stack overflow question (https://stackoverflow.com/questions/1471210/handling-overflow-in-tables)

    2. The submit button on the contact form does not observe the spacing from the form that was shown on all other browsers tested
    
        *Solutions:* I added a firefox only CSS rule following the guidance in this thread (https://stackoverflow.com/questions/952861/targeting-only-firefox-with-css).

        This solution generated a warning in the CSS validator that the moz-appearance query is a vendor extension, but it still passed the validator with no errors.

        ![Warning image](INSERT SCREENSHOT LINK HERE)

    3. text area resize

    4. contrast
   
    ---
+ ### Unsolved bugs
    - Mention the issue of my css styles not starting with small mobile devices in mind
+ ### Mistakes
    - I used past simple tense in commit messages due to the habit when I just started working on this project.
    - While progressing in my code I learned to use present simple tense in commit messages.

---
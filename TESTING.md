# TESTING


## Compatibility

In order to confirm the correct functionality and appearance of the site, it was tested on the following browsers: Chrome, Firefox and Safari. The links for each browser show the website is displaying correctly and all features described in the readme are present.

  + Chrome:

    - Homepage:

  ![Homepage](documentation/images/chrome_test_homepage.png)

    - Music page:

  ![Music page](documentation/images/chrome_test_musicpage.png)

    - Tour page:

  ![Tour page](documentation/images/chrome_test_tourpage.png)

    - Contact page:

  ![Contact page](documentation/images/chrome_test_contactpage.png)

  + FireFox:

    - Homepage:

  ![Homepage](documentation/images/firefox_test_homepage.png)

    - Music page:

  ![Music page](documentation/images/firefox_test_musicpage.png)

    - Tour page:

  ![Tour page](documentation/images/firefox_test_tourpage.png)

    - Contact page:

  ![Contact page](documentation/images/firefox_test_contactpage.png)


  + Safari:

    - Homepage:

  ![Homepage](documentation/images/safari_test_homepage.jpg)

    - Music page:

  ![Music page](documentation/images/safari_test_musicpage.jpg)

    - Tour page:

  ![Tour page](documentation/images/safari_test_tourpage.jpg)

    - Contact page:

  ![Contact page](documentation/images/safari_test_contactpage.jpg)


## Responsiveness


+ The website was checked for responsivenewss via the Responsive viewer chrome extension.

    - Main Page:

    ![Main page](documentation/images/homepage_responsive_screenshot.png)

    - Music Page:

    ![Music page](documentation/images/musicpage_responsive_screenshot.png)

    - Tour Page:

    ![Tour page](documentation/images/tourpage_responsive_screenshot.png)

    - Contact Page:

    ![Contact page](documentation/images/contactpage_responsive_screenshot.png)

    - Response Page:

    ![Response page](documentation/images/reponsepage_responsive_screenshot.png)
  

---
## Validator testing
+ ### HTML
  #### Home Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Home Page HTML Validator](documentation/images/html_validator_homepage.png)
    
  #### Music Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Music Page HTML Validator](documentation/images/html_validator_music.png)

  #### Tour Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Tour Page HTML Validator](documentation/images/html_validator_tour.png)

  #### Contact Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Contact Page HTML Validator](documentation/images/html_validator_contact.png)

    #### Response Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Response Page HTML Validator](documentation/images/html_validator_response.png)
    
+ ### CSS
  No errors or warnings were found when passing through the official W3C (Jigsaw) validator

  ![CSS Validator](documentation/images/jigsaw_css_validator.png)


+ ## LightHouse report

    - Using lighthouse in devtools I confirmed that the website is performing well, accessible and colors and fonts chosen are readable.
    
  ### Home page

  ![Home Page Lighthouse](documentation/images/homepage_lighthouse.png)

  ### Music page

  ![Music Page Lighthouse](documentation/images/music_lighthouse.png)

  ### Tour page

  ![Tour Page Lighthouse](documentation/images/tour_lighthouse.png)

  ### Contact page

  ![Contact Page Lighthouse](documentation/images/contact_lighthouse.png)

  ### Response page

  ![Response Page Lighthouse](documentation/images/response_lighthouse.png)

---
​
## Bugs
+ ### Solved bugs
    1. The tour table was too large to have all of the information displayed on mobile devices
    
        *Solutions:* a css property of overflow-x: auto; was added to the container housing the table. I learned about this fix from a stack overflow question (https://stackoverflow.com/questions/1471210/handling-overflow-in-tables)

    2. The submit button on the contact form does not observe the spacing from the form that was shown on all other browsers tested
    
        *Solutions:* I added a firefox only CSS rule following the guidance in this thread (https://stackoverflow.com/questions/952861/targeting-only-firefox-with-css).

        This solution generated a warning in the CSS validator that the moz-appearance query is a vendor extension, but it still passed the validator with no errors.

    3. My text area box on the form was able to manipulated by the user, so I had to fix this so it was not expandable or contractable.

        *Solutions:* a css property of resize: none was added to text area element

   
    ---
+ ### Unsolved bugs
    - None
+ ### Mistakes
    - I used past simple tense in commit messages due to the habit when I just started working on this project.
    - While progressing in my code I learned to use present simple tense in commit messages.
    - I did not write the styles with mobile as the primary viewing method, but I styled with desktop first and had to implement media queries for smaller devices. If I was doing the project over again I would write the smalled device query styles as the main section of the CSS file, and have media queries only for changes to accommodate larger devices.

---
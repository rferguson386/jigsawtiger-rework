# Jigsawtiger

Jigsawtiger is a website for (my friend) the Glasgow music producer, singer and DJ, Jigsawtiger. This site is a rework of an existing website for the artist, which can be viewed via this link (https://www.jigsawtiger.com/). My version of her site uses some of the same assets but aims to present them in a responsive way for all devices, and with a colour-scheme which is better for accessibility. The site aims to give information about Jigsawtiger to three distinct groups of users:

 - People who have just discovered Jigsawtiger and want to hear more of her music or find out more about her
 - Long-term fans of Jigsawtiger who want to quickly find her latest releases or DJ sets, and see when she is touring
 - Music promoters who would like to have a convenient way to get in touch with Jigsawtiger about booking her for a show.

![Responsive Mockup](https://github.com/rferguson386/jigsawtiger-rework/blob/f48461cc1ea219a6fd4e1e4d0647cc205bd5917d/documentation/Jigsawtiger.png)


## Features 

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

- __Navigation__

  - Featured on all pages of the, the full responsive navigation bar includes a logo on the left-hand side of the screen (this logo is also a link to the home page of the site), Home page link, Music page link, Tour page link and Contact page link. The navigation is always present on screen, and fully responsive with the links being collapsed into a toggle-able menu on devices below 768px.


![Nav Bar Collapsed](https://github.com/rferguson386/jigsawtiger-rework/blob/311ed1bab70de2d605135aa1b537a09e068f55c4/documentation/Navbar_collapsed.png)

![Nav Bar Expanded](https://github.com/rferguson386/jigsawtiger-rework/blob/311ed1bab70de2d605135aa1b537a09e068f55c4/documentation/Navbar_expanded.png)

- __The home page__

  - The home page includes information about Jigsawtiger to allow users to find out more about the artist. At the bottom of the "about" section, there are links to keep the user journey going without requiring them to find the links in the nav bar. It also includes quotes from media outlets about Jigsawtiger.
  
![Home Page screenshot 1](https://github.com/rferguson386/jigsawtiger-rework/blob/311ed1bab70de2d605135aa1b537a09e068f55c4/documentation/Homepage_1.png)

![Home Page screenshot 2](https://github.com/rferguson386/jigsawtiger-rework/blob/311ed1bab70de2d605135aa1b537a09e068f55c4/documentation/Homepage_2.png)

- __The music page__

  - The music page is split into two sections, one for displaying links and embedded media relating to music that Jigsawtiger has recorded or DJ sets she has uploaded, and one for embedded music videos and videos of DJ sets.
  - This section will help new users get an idea of what Jigsawtiger sounds like, and be a hub for existing fans to find all of her latest music. 

![Music page screenshot 1](https://github.com/rferguson386/jigsawtiger-rework/blob/311ed1bab70de2d605135aa1b537a09e068f55c4/documentation/Music_page_1.png)

![Music page screenshot 2](https://github.com/rferguson386/jigsawtiger-rework/blob/311ed1bab70de2d605135aa1b537a09e068f55c4/documentation/Music_page_2.png)

- __The tour page__

  - This section will allow users to find information about when and where Jigsawtiger is touring. Each tour date listing contains links to the venue to allow the user to buy tickets.
  - This section will be updated as and when more tours are announced, or when dates have passed.

![The tour page](https://github.com/rferguson386/jigsawtiger-rework/blob/311ed1bab70de2d605135aa1b537a09e068f55c4/documentation/Tour_page.png)

- __The contact page__ 

  - The contact page includes a form with 3 fields for users to send a message to Jigsawtiger. The name and email fields are required fields.
  - The top of the page features suggestions of instances/reasons why users might want to get in touch with Jigsawtiger.

![The contact page screenshot 1](https://github.com/rferguson386/jigsawtiger-rework/blob/311ed1bab70de2d605135aa1b537a09e068f55c4/documentation/Contact_page_1.png)

![The contact page screenshot 2](https://github.com/rferguson386/jigsawtiger-rework/blob/311ed1bab70de2d605135aa1b537a09e068f55c4/documentation/Contact_page_2.png)

- __The response page__

  - Users are directed to a page reponse.html after submitting the form. The page displays a thank-you message acknowledging receipt of their enquiry, and a link back to the music page to continue interacting with the site.

![The response page](https://github.com/rferguson386/jigsawtiger-rework/blob/311ed1bab70de2d605135aa1b537a09e068f55c4/documentation/Response_page.png)

- __The Footer__

  - The footer section is uniform on every page, with relevant outbound links categorised into two sections, social profiles, and music. Each of the links opens up the target webpage in a new browser tab

![The Footer one column](https://github.com/rferguson386/jigsawtiger-rework/blob/311ed1bab70de2d605135aa1b537a09e068f55c4/documentation/Footer_one_column.png)

![The Footer two columns](https://github.com/rferguson386/jigsawtiger-rework/blob/311ed1bab70de2d605135aa1b537a09e068f55c4/documentation/Footer_two_columns.png)


### Features Left to Implement

- Fully functioning contact form which directs enquiries to an SQL database and generates email notifications

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
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

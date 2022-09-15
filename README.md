# __Portfolio Project 1 - A History Website__

The Monumental History website is a site that aims to inform those interested about historical places, and on this specific website we are showcasing Mount Rushmore. The website is also created to share information aobut Mount Everest for those interested in learning more about the place.

![Responsive Mockup](/assets/images/am-i-responsive.png)

## __Wireframes__
Before starting the project I created a couple basic wireframes to have an idea of what my final product would look like. I created a mobile wireframe and a desktop wireframe.

<img>

![Mobile wireframe](/assets/images/mobile-wireframe-2.png) ![desktop wireframe](/assets/images/desktop%20wireframe-2.png)

---

## __Features__
There are several features on this website and we will now take a closer look at them.

### __Existing Features__


- __Navigation Bar__
    - Starting with the top of the page, I have created a __Navigation Bar__. The navigation bar is there for the user to use as a reference point between all pages and to know which page they are on. The active page will appear with an underline. The navigation bar also include links to other pages throughout the website. 
    - The navigation bar is also responsive and the form will change depending on what screen size you are on. 

![Navigation Bar](/assets/images/nav-bar.png)


- __The Landing Page Image__
    - The landing page grabs the viewers attention by showing an image of Mount Rushmore. The goal of the image and overlay text is to give an immediate understanding to the viewer what the website will be about.

![Landing page picture](/assets/images/landing-page-image.png)



- __A Brief Timeline__
    - This section will give a brief introduction to the process behind the creation of Mount Rushmore. The viewer will be able to learn about what some of the major events were during the creation of the historic place.

![Excerpt of the timeline](/assets/images/timeline-excerpt.png)

- __The Four Presidents Section__
    - This section includes more in-depth information about the faces that are carved into the mountain and the reason why these Presidents were specifically chosen. 

![President Info Card](/assets/images/president-info-cards.png)

- __Bottom Navigation Bar__
    - This feature is included for easy accesability for users to navigate either back to the top of the page or to any other page thats connected within the website. 
    - This navigation bar will only be found on pages with more content, such as the gallery page and home page.

![Bottom Navigation Bar](/assets/images/bottom-navigation-bar.png)

- __The Page Footer__
    - The footer is consistent throughout all pages. The footer includes social media links for Facebook, Twitter, YouTube and Instagram.

![social media footer](/assets/images/social-media-footer.png)

- __YouTube Video__
    - The first feature you will see on the gallery page is an embedded YouTube video. The video will provide additional information about Mount Rushmore but in addition will give spectacular views in motion of the historical site.
    - The video is able to be played in fullscreen, to start the video you need to hit play and it will automatically be muted. To have sound you need to increase the volume.

![Embedded Video](/assets/images/embedded-video.png)

- __Gallery__
    - The gallery provides additional visual imagery of the historical site. The goal with the gallery is to spark even greater interest and a eagerness to learn more about it and even better, for the viewer to want to visit.

![excerpt of the gallery](/assets/images/excerpt-of-gallery.png)

- __Sign Up Page__
    - This feature will allow website visitors to sign up for a tour.

![sign up form](/assets/images/sign-up-form.png)

- __Thank You Page__
    - This part of the website will thank the user for signing up, and there clicking the button will bring you back to the home page. A user can use that button or the existing nav bar at the top of the page. 

![thank-you-message](/assets/images/thank-you-page.png)

- __Color Palette__
    - A color palette generator was used based on my hero-image on the front page to help me create a set of colors that would merge well with my website.

![color-palette](/assets/images/Color-Palette.png)

### __Technologies Used__
- HTML
- CSS

### __Features left to Implement__
- In the future I would like to add a feature where different types of tours could be viewed. For exmaple: self-guided tour, museum + guided tour, guided tour, group tour, all-inclusive tour, etc.
- More responsive design for larger screens.
- I got a suggestion to add a "burger menu" for my navigation bar, but I quiete like how my navigation bar looks on mobile view. So this feature is still a maybe until I am further convinced.
---

## __Testing__
All features above have been tested on the depoyed website. Navigations are working as inteded, links to social media websites are working. The form is working as it should, and buttons perform the given actions. 

As a user of the website I want to be enticed to learn more about the historical site. Through the way that the website is created I believe I have achieved that. I used interesting formats for portaying the information through timelines and information cards, and even added visual elements such as a video and gallery page. 

The greatest challenge I faced for this website was creating a responsive design and making my flexboxes do what I wanted them to do. I was able to create a responsive design going down in screen size. However, for larger desktop screens I still need to develop a new media query.

### __Lighthouse Testing__
I will be using lightouse to check the performance of my home page and gallery page for mobile devices.

- __Home page__: 
    - The low performance is due to large image dimensions.

![home-page-lighthouse-results](/assets/images/home-page-lighthouse-results.png)
    
- __Gallery page__:
    - Again, the low performance is due to large image dimensions.
    - According to the report, the low score for best practices is due to browser erros and something to do with cookies and loading up the YouTube video.

![gallery-page-lighthouse-results](/assets/images/gallery-page-lighthouse-results.png)


### __Lighthouse Testing After A Few Updates__
Because of the performance levels above, I have gone back and compressed my images. Performance levels are now at __97__ for the homepage and __100__ for gallery page.

### __Validator Testing__

- __HTML__
    - __Index Page__ validation:
        - First time running the HTML through the [W3B validator](https://validator.w3.org/) I recieved one error and one warning.
    
        ```
        Error: Attribute alt not allowed on element div at this point.

        From line 44, column 9; to line 44, column 65 
        <div class="hero-image" alt="picuture of mount rushmore"> 
        ```
        ```
        Warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections, or else use a div element instead for any cases where no heading is needed.

        From line 155, column 5; to line 155, column 13

        -->↩↩    <section>↩
        ```
        - The error and warning were fixed immediately. 
        - Second time running the validator there were no errors. [Link to validation](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Favtpepper.github.io%2Fproject1_history_website%2Findex.html#textarea).

    - __Gallery Page__ validation:
        - First time running the validation I recieved 11 errors and 2 warnings. 
        ```
        Erros:
        1. Attribute "alt" not allowed on element "iframe" at this point.
        2. The "frameborder" attribute on the "iframe" element is obsolete. Use CSS instead.
        3. Bad value for attribute "srcset" on element "img": Must contain one or more image candidate strings. (9)

        Warnings:
        1. Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections, or else use a div element instead for any cases where no heading is needed. (2)
        ```
        ```
        Errors:
        1 and 2.
        <iframe class="player" src="https://www.youtube.com/embed/juhjnealXxY?mute=1" alt="a video with history and scenic views of Mount Rushmore" frameborder="0" allowfullscreen>
       
        3. <img src="assets/images/gallery/george-washington-black-and-white-mount-rushmore.jpg" alt="" srcset="">
        ```
        - The errors and warnings were fixed immediately. 
        - Second time running the validator there were no errors. [Link to validation](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Favtpepper.github.io%2Fproject1_history_website%2Fgallery.html).

    - __Sign Up Page__ validation:
        - First time running the validation I recieved 1 error:
        ```
        Error:
        1. The value of the for attribute of the label element must be the ID of a non-hidden form control.

        From line 67, column 25; to line 67, column 55

          <label for="tour" class="tour">Choose
        ```
        - The error was fixed immediately. 
        - Second time running the validator there were no errors. [Link to validation](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Favtpepper.github.io%2Fproject1_history_website%2Fsignup.html).

    - __Thank You Page__ validation:
        - First time running the validation I recieved 3 errors:
        ```
        Error:
        1. Error: End tag p seen, but there were open elements.
        From line 50, column 81; to line 50, column 84
        story Crew</p></em>

        2: Error: Unclosed element em.
        From line 50, column 30; to line 50, column 33
        <br> <em>Best R

        3. Error: No em element in scope but a em end tag seen.
        From line 50, column 85; to line 50, column 89 
        y Crew</p></em>     
        ```
        - The errors were fixed immediately. 
        - Second time running the validator there were no errors. [Link to validation](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Favtpepper.github.io%2Fproject1_history_website%2Fthankyou.html%3Ffirst_name%3Dasdf%26last_name%3Dasdf%26email_address%3Dasdf%2540asdf%26type-of-tour%3Dother-historical-sites#l67c55).
- __CSS__
    - __styles.css__ validation:
        - First time running the validation I recieved 2 errors and 5 warnings.
        ```
        Error:
        1. 58	Value Error : padding auto is not a padding value : auto
		2. 468  Value Error : padding auto is not a padding value : auto
        ```
        - Both errors were fixed immediatley. 

        ```
        Warning:
        1. Imported style sheets are not checked in direct input and file upload modes.
        2.  448	.btn	Same color for background-color and border-top-color
            448	.btn	Same color for background-color and border-right-color
            448	.btn	Same color for background-color and border-bottom-color
            448	.btn	Same color for background-color and border-left-color
         ```

         - Warning number 1 is there because the validator wont check google fonts for anything actually wrong.
         - Warning 2 is a styling decision I have made, so that when the person hovers over the button the button stays the same size but the colors become different. 
         - Second time running the validator there were no erros but the warnings remain: [Link to validation](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Favtpepper.github.io%2Fproject1_history_website%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
---
## __Deployment__

This project was delopyed on GitHub. Below are the steps I followed to be able to deploy the website:
1. In the GitHub repository, navigate to the Settings tab.
2. Scroll down until you see GitHub pages.
3. From the source section drop-down menu, select the main branch.
4. Once the main branch has been selected hit the save button.
5. Finally when the page is refreshed there will be a detailed ribbon display to indicate the successful deployment.

The live link can be found here: https://avtpepper.github.io/project1_history_website/index.html

---
## __Credits__
### Content
- All information about Mount Rushmore was taken from [The National Park Service Website](https://www.nps.gov/index.htm).
- Icons in the header and footer were taken from [Font Awesome](https://fontawesome.com/icons)
- Inspiration was taken from this website for the sign up form. [Link](https://softauthor.com/css-flexbox-responsive-registration-form-with-source-code/).
- For coding questions I used [w3schools.com](https://www.w3schools.com/) and the slack community.
- For flex-box issues I kept refferring to [css-tricks.com](https://css-tricks.com/snippets/css/a-guide-to-flexbox/).

### Media
- Color Palette was generetad using [Coolers](https://coolors.co/).
- Images were takent from [Pexels](https://www.pexels.com/) and [The National Park Service Website](https://www.nps.gov/index.htm).
- The video is from YouTube.
---
## __Special Thanks__
Specials thanks goes out to:
- My mentor Maranatha Ilesanmi for guiding me through the project.
- The "Augies" in the Code Institute slack community for answering my questions.
- Chris Williams from the Code Institute community for helping with specific issues throughout the project.



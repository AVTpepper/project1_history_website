# Portfolio Project 1 - A History Website

The Monumental History website is a site that aims to inform those interested about historical places, and on this specific website we are showcasing Mount Rushmore. The website is also created to share information aobut Mount Everest for those interested in learning more about the place.

![Responsive Mockup](/assets/images/am-i-responsive.png)

## Features
---
There are several features on this website and we will now take a closer look at them.

### Existing Features


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


### Features left to Implement
- In the future I would like to add a feature where different types of tours could be viewed. For exmaple: self-guided tour, museum + guided tour, guided tour, group tour, all-inclusive tour, etc.
---

## __Testing__
All features above have been tested on the depoyed website. Navigations are working as inteded, links to social media websites are working. The form is working as it should, and buttons perform the given actions. 

As a user of the website I want to be enticed to learn more about the historical site. Through the way that the website is created I believe I have achieved that. I used interesting formats for portaying the information through timelines and information cards, and even added visual elements such as a video and gallery page. 

The greatest challenge I faced for this website was creating a responsive design and making my flexboxes do what I wanted them to do. I was able to create a responsive design going down in screen size. However, for larger desktop screens I still need to develop a new media query.

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
    - These errors were fixed immediately. 
    - Second time running the validator there were no errors. [Link to validation](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Favtpepper.github.io%2Fproject1_history_website%2Findex.html#textarea).



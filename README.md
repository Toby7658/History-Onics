# **_HistoryOnics_**

HistoryOnics is a tourist history website which focuses on each provence of Ireland. 
The site aims to provide information about Irelands history and interesting places 
to visit for both local and international tourists.The site provides maps and videos 
of each county, within each provence and links to social media for users to interact 
with the site. The User can also contact the site should they have more queries. 

![Hero image](./assets/images/hero-image.jpeg)

Link to live site - [HistoryOnics](https://toby7658.github.io/History-Onics/)

# Table of Contents

* [**User Experience UX**](<#user-experience-ux>)
    * [Wireframe](<#wireframe>)
    * [Structure of Site](<#structure-of-site>)
    * [Typography](<#typography>)
    * [Colour Scheme](<#colour-scheme>)

* [**Existing Features**](<#existing-features>)
    * [Navigation Menu](<#navigation-menu>)
    * [Hamburger Bar](<#hamburger-bar>)
    * [Logo](<#logo>)
    * [Hero Image](<#hero-image>)
    * [Navigation Blocks](<#navigation-blocks>)
    * [Social Media](<#social-media>)
    * [Videos](<#videos>)
    * [Maps](<#maps>)
    * [Contact Us](<#contact-us>)
    * [Form Submission](<#form-submission>)
    * [About Us](<#about-us>)
    * [Footer](<#footer>)

* [**Future Features**](<#future-features>)

* [**Technologies Used**](<#technologies-used>)
  * [HTML](#html)
  * [CSS](#css)
  * [Google Fonts](#google-fonts)
  * [Font Awesome Icons](#font-awesome-icons)
  * [balsamiq](#balsamiq)
  * [GitHub](#gitHub)
  * [Git](#git)
  * [Gitpod](#gitpod)
  * [Adobe Color](#adobe-color)
  * [Gimp](#gimp)
  * [Slack](slack)
  * [Visual Studio](visual-studio)
  * [volusion](#volusion) 
  * [pxhere](#pxhere)
  * [Google Maps](#google-maps)
  * [Youtube](#youtube)
  * [Code Institute](#code-institute)
  * [Google Images](google-images)
 

* [**Testing**](<#testing>)

- [Lighthouse Testing](#lighthouse-testing)
- [W3c](#https://jigsaw.w3.org/css-validator/)

* [**Deployment**](<#deployment>)

* [**Credits**](<#credits>)

* [**Code Used**](<#code-used>)
  * [HTML](#html)
  * [CSS](#css)
  * [JAVA SCRIPT](#java-script)

* [**Acknowledgment**](<#Acknowledgment>)


# User Experience UX
## Wireframe
The mock-up for this project was created using [Balsamiq](https://balsamiq.com/wireframes/).
Aspects of the mock-up have changed during production due to increasing user experience and 
visual effects. Changes include moving the Logo to the centre and creating a Nav menu bar
which is replaced by a Hamburger bar as devices become smaller.

### Home Page for wide screen devise
![Wireframe image home page](./assets/images/wireframe-home-wide.jpg)

### Visit Page for wide screen devise
![Wireframe image visit page](./assets/images/wireframe-visit-wide.jpg)

### About Us Page for wide screen devise
![Wireframe image about us page](./assets/images/wireframe-about-wide.jpg)

### Contact Page for wide screen devise
![Wireframe image contact page](./assets/images/wireframe-contact-wide.jpg)

### Submit Page for wide screen devise
![Wireframe image submit page](./assets/images/wireframe-submit-wide.jpg)


### Home Page for small screen devise
![Wireframe image home page](./assets/images/wireframe-home-small.jpg)

### Visit Page for small screen devise
![Wireframe image visit page](./assets/images/wireframe-visit-small.jpg)

### About Us Page for small screen devise
![Wireframe image about us page](./assets/images/wireframe-about-small.jpg)

### Contact Page for small screen devise
![Wireframe image contact page](./assets/images/wireframe-contact-small.jpg)

### Submit Page for small screen devise
![Wireframe image submit page](./assets/images/wireframe-submit-small.jpg)

[Back to top](<#Table of Contents>)

# Structure of Site
The site is made up of eight pages. They are constructed of:
1. * [Home page](index.html)
2. * [Visit Munster page](munster.html)
3. * [Visit Connacht page](connacht.html)
4. * [Visit Leinster page](leinster.html)
5. * [Visit Ulster page](ulster.html)
6. * [About Us page](about.html)
7. * [Contact Us page](contact.html)
8. * [Submit page](submit.html)

The site opens with a landing page which presents a [Hero Image](./assets/images/hero-image.jpeg) with zoom effect. For wide screens, there is a navigation menu at the top right hand side. This turns into a hamburger-bar for smaller screens and is placed on the left of the screen. The logo is also used as a navigational tool on each page to bring the user
back to the landing page. The nav bars are provided on each page to guide the user and are responsive on all screen sizes.

The centre structure of the page provides a short introduction to the site. The heading used for this piece also incorporates fixed
icons of a person strolling, this is to complement the tatle 'A Stroll Back In Time'. 
At the bottom of the landing page is also another navigation block which is broken into four seperate 
images with access to four seperate pages. The images change colour to grayscale when hovered over to allow
the user to know which block they are choosing.
The footer holds the social media icons, which are responsive on all screens throughout each page of the site.

The visit pages provides a short intro to each county with a map and youtube video guide. 
The map can be clicked upon and opens to a new window. The videos each play within the existing site page.

The About Us page introduces the user to the team and provides a brief description and biography of the 
site owners. Images of the team have also been added to the page.

The contact page provides a query box and requires the user to complete various fields including
Name, Phone and Email. These boxes are required fields and have a * to indicate this to the user.
The email address provided by the user must be correctly structured inorder to submit a query.

The submission page appears after the user submits a query via the contact page. The page provides a message stating that the 
query has been received. The user can then navigate away from this page by clicking on the Logo or nav bar provided.

[Back to top](<#Table of Contents>)

# Typography
The body of the site uses font style "Lato", "sans-serif". This is in contrast with the logo and headings which
uses font style "Cormorant SC", "sans-serif". Initially, Cormorant SC was used throughout as the style provides 
a more ancient feel to the history site. However, this font appears only as uppercase and therefore the body was 
replaced with Lato typeface to provide a more natural read for the user. Sans-serif is inplace as a secondary default option
should either of the first options fail. Fonts were taken from [Google Fonts](https://fonts.google.com/).

[Back to top](<#Table of Contents>)

# Colour Scheme

The colour scheme is inspired by the traditional color of Ireland, green. The shade "rgb(226, 238, 204)" was 
chosen as this colour is soft yet also provides a more ancient feel within a green tone.
The text is set as #2f4f4f, which again is inkeeping with the green tones and historic feel of the site.
Grayscale has also been used when hovering over the navigational block of images at the bottom
of the landing page. To contrast against the green tone, #f1f1f1 has been used for the text on all navigation
bars and blocks. Finally, #45a049 has been used when hovering over the submit button on the contact page. 
The colour scheme was guided by [Adobe Color](https://color.adobe.com/create/color-wheel).

![Colour rgb(226, 238, 204)](./assets/images/colour-rgb-226238204.jpg)
![Colour #2f4f4f](./assets/images/colour-2f4f4f.jpg)
![Colour #f1f1f1](./assets/images/colour-f1f1f1.jpg)
![Colour #45a049](./assets/images/colour-45a049.jpg)


[Back to top](<#Table of Contents>)

# Existing Features

## Navigation Menu
A top navigation menu bar has been put in place for screens 950px and wider. Originally, a hamburger-bar
menu was put in place for all screens, as this seems to be a common theme with other sites currently through further research, however, in-order to show adaptability with building this site, the hamburger-bar was set in place for screens smaller than 950px. This also shows the responsiveness as the screens are minimized. 
The top navigation menu bar sits at the top right-hand side of the screen and allows the user to navigate 
through seven pages (the eight page being the submission button which cannot be accessed unless pressing 'submit' on the
contact page). Each element becomes underlined as the user hovers over the tabs seperately. This aspect was influenced
by the Love Running Module via [Code Institute](https://codeinstitute.net/ie/)

![Navigation Menu Bar](./assets/images/nav-menu-bar.jpg)


## Hamburger Bar

A hamburger bar has been placed for small screens including tablets and mobile devices. This button sits
at the top left-hand corner of the screen and provides the user with a full list of pages, as per the top navigation menu bar.
The icon can be recognised by the three lines visable, upon the user clicking on this, the button changes colour and opens to
provide a list of pages. The X on the open tab of the menu must then be clicked to close the hamburger-bar. This aspect was
influenced by [W3School Collapsed Sidepanel](https://www.w3schools.com/howto/howto_js_collapse_sidepanel.asp).

 ![Hamburger bar closed](./assets/images/hamburger-button-closed.jpg)
 ![Hamburger bar open](./assets/images/hamburger-button-open.jpg)

[Back to top](<#Table of Contents>)

## Logo

The logo 'HistoryOnics' is a play on words. Histrionic, meaning overly dramatic and theatrical 
is inkeeping with the dramitic history and storytelling of Ireland. The font, "Cormorant SC" may
also be seen as dramatic, coupled together with colour #2f4f4f brings a bold effect, inkeeping with
an Irish historical theme. Upon clicking on the logo, the user is brought back to the landing page.
The logo is responsive with all screens.

![Logo Image](./assets/images/logo-image.jpg)

[Back to top](<#Table of Contents>)

## Hero Image
The [Hero Image](./assets/images/hero-image.jpeg) is of the Cliffs of Moher and is synonymous with Ireland accross the globe and presents an immediate interaction with the user with the zoom-in effect. The zoom-in effect is responsive with all screen sizes. The Hero Image was sources via [Google Images](https://images.google.com/) from [Cliffs of Moher](https://www.cliffsofmoher.ie/unesco-global-geopark/education/learning-resources/).

[Back to top](<#Table of Contents>)

## Navigation Blocks

The navigational block is provided for further interaction with the user. The user can hover over each image, which will then become grayscale, and upon clicking on the chosen box, the user will be directed to the chosen page. Famous aspects of each provence 
have been used for imagery with bright colours to further attract the user visually. This block is responsive with all screens. Images are sourced via [Google Images](https://images.google.com/) via: [Connacht Image](https://theplanetd.com/poulnabrone-dolmen-ireland/), [Munster Image](https://www.atlanticwaytouring.com/product/quin-abbey/), [Leinster Image](https://www.meetingselect.com/en/venue/trinity-college-university-of-dublin), [Ulster Image](https://www.posterlounge.com/p/738259.html)

 ![Nav Block Menu](./assets/images/nav-block-menu.jpg)

 [Back to top](<#Table of Contents>)

## Social Media
The social media icons can be accessed on all pages and will bring the user to four seperate external sites
including [Twitter](https://twitter.com/), [Instagram](https://www.instagram.com/?hl=en), [Facebook](https://www.facebook.com/) and [Youtube](https://www.youtube.com/). The setting of these icons have been influenced by the Love Running module
as per [Code Institute](https://codeinstitute.net/ie/). Icons were accessed by [Font Awesome](https://fontawesome.com/icons).

![Social Media Icons](./assets/images/social-media-icons.jpg)

[Back to top](<#Table of Contents>)

## Videos

Videos have been incorporated as part of the Visit Pages for each county with in Provences. All video material have been sources 
via Youtube. Each video provides information as per the county it is relating to. The videos were originally 
to be placed on the left-hand-side of the page, however, this was not as visually appealing as when it is placed on the right. 
Each video is responsive on all screens and will play within the page, without increasing in size. 
Videos are sourced from:
* [Youtube - County By County Show](https://www.youtube.com/results?sp=mAEB&search_query=county+by+county+ireland+show)

[Back to top](<#Table of Contents>)

## Maps

Maps have been incorporated on to each Visit Page, under each county seperately. The maps are responsive on
all screens, however, must be clicked within the middle of the map for small mobile devices (eg. iPhone 5). Otherwise, all 
maps will open and respond to 'View Larger Map' where indicated on map. Maps will also be responsive when clicked anywhere
on map for all screens. Maps are sourced by accessing:

* [Google Maps](https://www.google.com/maps/@52.8603236,-9.6709686,9z)

[Back to top](<#Table of Contents>)

## Contact Us
The contact page is a simple structure which allows the user to provide required and non-required information. 
The required elements are indicated by * after the element name. This includes First Name, Last Name, Email.
The phone and query box are not set as required. The email element must be correctly formatted so as to be accepted.
The query box is the only aspect which has a placeholder to provide further instruction to the user. This page is
accessable via the navigation menu on a wide screen and Hamburger Bar via a smaller device.

[Back to top](<#Table of Contents>)

## Form Submission
The form submission page is presented upon the user submitting a query via the contact page. This page has access to a navigational menu/hamburger-bar and Logo which will bring the user back to previous pages of the site. A message is in place acknowledging receipt
of the query. Social media icons are also present at the footer of the page.

## About Us

The about Us page provides information about how the site was established as the opening paragraph. This paragraph was 
created using a text creator via [volusion.com](https://www.volusion.com/) 
Below the opening paragrapg, there is a meet the team. This aspect provides a brief description of the team and provies images of the team-members.
Public domain images are sourced via [pxhere.com](https://pxhere.com/)

## Footer
The footer appears at the bottom of each page. The social media icons are centered within the footer and can be 
clicked on to interact with. 


## Future Features
- An e-commerce element would be included where the user can book a specific tour per provence. The tours would be broken up into bus and bicyle tours.
- A page dedicated to where users can find the best pubs/restaurants off the beaten track and away from the tourist traps.
- An e-commerce element which sells experiences, eg. spending an afternoon cooking traditional food in a host kitchen.

## Technologies Used
  * [HTML](https://en.wikipedia.org/wiki/HTML5) - HTML the most basic building block of the Web. This is the main language used to develop the site. 
  * [CSS](https://en.wikipedia.org/wiki/CSS) - CSS describes how HTML elements are to be displayed on screen. This has been used to develop the stlye of the site.
  * [Google Fonts](https://fonts.google.com/) - Google Fonts is a directory of font-families which was incorporated during development of the site.
  * [Font Awesome Icons](https://fontawesome.com/icons) - Font Awsome is a directory of icons which was used to incorporate icons for social media, text and headings.
  * [balsamiq](https://balsamiq.com/wireframes/?gclid=CjwKCAjwi8iXBhBeEiwAKbUoferdHodwIX8rhZQq6jDFB9i1ffpeC04Iv0ROTwgZLHrOEP1rmCqzjhoCUsMQAvD_BwE) - Balsamiq was used to create a mock-up wireframe for large and small screen devices.
  * [GitHub](https://github.com/about) - Github is used to host the source code for the site.
  * [Git](https://git-scm.com/) - Git is used to manage and keep track of the source code history throughout development. 
  * [Gitpod](https://www.gitpod.io/) - Gitpod creats connections between Gitpod and GitHub account. Gitpod continuously builds git branches to facilitate the coding process.
  * [Adobe Color](https://color.adobe.com/create/color-wheel) - Adobe Colour has been used to navigate colour charts for the site during development.
  * [Gimp](https://www.gimp.org/) - Gimp was used to edit and resize images before loading to the site. 
  * [Slack](https://slack.com/intl/en-ie/) - Slack was utilized by seeking advise and knowledge from students and mentors.
  * [Visual Studio](https://visualstudio.microsoft.com/) - Visual Studio was used in the very early phase to gain further understanding of how to properly implement code while gaining confidence with Github.
  * [volusion](https://www.volusion.com/) - Volusion is a site which drafts copy for paragraphs. 
  * [pxhere](https://pxhere.com/) - Pxhere was used to sourse images for the About Us page.
  * [Google Maps](https://www.google.com/maps/@52.8603236,-9.6709686,9z) - Google Maps was used to source the map links for each visit page.
  * [Youtube](https://www.youtube.com/) - Youtube was the sourse for each video on the Visit Pages.
  * [Code Institute](https://codeinstitute.net/ie/) - Influence with styling the landing page was taken from the Love Running module available via the Programme Overview.
  * [Google Images](https://images.google.com/) - Google Images provided images for the Hero Image and Navigation  block on the landing page.
 
## Testing
- [Lighthouse Testing](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=en)
- [Web Page Test](https://www.webpagetest.org/)
- [W3 Markup Validation Service](https://validator.w3.org/)
- [W3 CSS Validation Service](https://jigsaw.w3.org/css-validator/)

## W3 Validation Results:
* Home Page html - [Error Free Home Page](./assets/images/error-free-home-html.jpg)
* Munster Page html - [Error Free Munster Page](./assets/images/error-free-munster-html.jpg)
* Leinster Page html - [Error Free Leinster Page](./assets/images/error-free-leinster-html.jpg)
* Connacht Page html - [Error Free Connacht Page](./assets/images/error-free-connacht-html.jpg)
* Ulster Page html - [Error Free Ulster Page](./assets/images/error-free-ulster-html.jpg)
* About Page html - [Error Free About Us Page](./assets/images/error-free-about-html.jpg)
* Submit Page html - [Error Free Submit Page](./assets/images/error-free-submit-html.jpg)
* Contact Page html - [Error Free Contact Page](./assets/images/error-free-contact-html.jpg)
* CSS - [Error Free CSS](./assets/images/error-free-css.jpg)

## Lighthouse Testing Results:
* Landing Page - Performace: 98, Accessability: 96, Best Practise: 100, SEO: 89.
* Visit Munster Page - Performace: 99, Accessability: 92, Best Practise: 92, SEO: 89.
* Visit Leinster Page - Performace: 98, Accessability: 96, Best Practise: 100, SEO: 89.
* Visit Connacht Page - Performace: 100, Accessability: 92, Best Practise: 92, SEO: 89.
* Visit Ulster Page - Performace: 98, Accessability: 96, Best Practise: 100, SEO: 89.
* About Us Page - Performace: 98, Accessability: 96, Best Practise: 100, SEO: 89.
* Contact Us Page - Performace: 98, Accessability: 96, Best Practise: 100, SEO: 89.




## Deployment


## Credits


## Code Used
 * [HTML](https://en.wikipedia.org/wiki/HTML5)
 * [CSS](https://en.wikipedia.org/wiki/CSS)
 * [Java Script](https://en.wikipedia.org/wiki/JavaScript)

## Acknowledgment


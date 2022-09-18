# Barra Barista

Responsive Mockup goes here

----

Barra Barista is an informational website about the Barra Barista coffee shop. The website will be targeted towards customers and potential new customers of Barra Barista coffee shop that are looking to know more about Barra Barista and to get more information about the coffee shop (ie. What is in the menu, opening hours, etc.)

![Responsive Mockup](/assets/images/responsive_mockup.PNG)

----

## Features

In this section, I will be going through the different parts of the website and I will provide descriptions for each feature and what the feature do. 

### Current Features

- _Navigation Bar_
    - Available in all five pages of the website, the full responsive navigation bar includes the links to the Logo (Landing page), About Us page, Menu page, Find Us page and Contact page and is similar through all pages to help users navigate through the site easily.
    - A site user can click on the any links of the navigation bar and it would bring them to the page that they clicked on. The navigation bar helps site users navigate through each page from all devices without having to use the "back" button to revert back to a previous page.
    - A link in the navigation bar will be underlined once the site user is in that specific page, this will help site user identify which page he/she is currently in.

![Navigation Bar](/assets/images/navbar.PNG)

- _Landing Page_
    - The landing page is the first page a site user will see when he/she opens the website. It contains an logo image of Barra Barista with it's slogan and a button that will 
    - It contains a background image of what the Barra Barista counter to give site users and idea what to expect (ie. the ambience) if they decide to visit Barra Barista.
    - It also contains an logo image of Barra Barista with it's slogan and a button that a site user can click to bring him/her to the menu page.  
    - A site user can access the landing page again by clicking the Logo in the navigation bar.

![Landing Page](/assets/images/landingpage.PNG)

- _About Us Page_
    - About us page can be accessed by a site user through one of the links (About Us) in the navigation bar.
    - This section contains a short story about why the owner of Barra Barista started and opened his own company (Barra Barista) and an image of what it looks like inside of the cafe. These helps a site user get more insight about the goal of the owner and an idea of what the cafe looks like.

![About Us Page](/assets/images/about_us_page.PNG)

- _Menu Page_
    - A site user can go to the menu page from clicking the Menu link in the navigation bar or from clicking the button "Check it!" in the landing page.
    - This section contains the different food and drink options with the prices for each that a site user could order in Barra Barista. 
    - The food and drink options are separated in 4 menus and each menu get enlarged when a site user hovers over it, this helps site user to see the menu more clearly.

![Menu Page](/assets/images/menu_page.PNG)

- _Find Us Page_
    - This section can accessed by a site user through the Find Us link in the navigation bar.
    - A site user can find the opening and closing times and the address of Barra Barista coffee shop. The Find Us page also contains a google map with the location of Barra Barista already set to help site users get the directions to the coffee shop. 

![Find Us Page](/assets/images/find_us_page.PNG)

- _Contact Page_
    - A site user can conveniently send a message to Barra Barista throught the Contact page, which can be accessed by a site user through the Contact link in the navigation bar.
    - The site user will be asked to enter their full name, mobile number and email, so that someone from Barra Barista knows who and where to reply back or call back if required.

![Contact Page](/assets/images/contact_page.PNG)

- _Header_
    - The header section is available in the About Us, Menu, Find Us and Contact page.
    - It contains an image of some barra barista products with a text overlay in the middle of the section to also help site users confirm which page they are currently in.
    - The header also contains the navigation bar at the very top of the section.

![Header](/assets/images/header.PNG)

- _Footer_
    - This section is available in the About Us, Menu, Find Us and Contact page. 
    - The footer section contains the social media links of Barra Barista, which gives the user the oppurtunity to follow Barra Barista in different social media platforms and it also gives site users an oppurnity to reach out to someone in Barra Barista. A site user can click on each links and it will open a new tab to the corresponding social media page of Barra Barista.
    - It also contains a copyright message.

![Footer](/assets/images/footer.PNG)

### Future Development Plans 
    - To add more content (ie. Activities done by Barra Barista that has help the community, any active charities they are supporting, etc.) in the About us page.
    - To create a centralized email address from Barra Barista for the contact us form, this helps checking or following-up on each message more effeciently.
----

## Testing

### Validator Testing

- _HTML_
    - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjddelara01.github.io%2Fbarra-barista%2F)

- _CSS_
  - No errors were found when passing through the official [(Jigsaw) validator]

### Known Issues

- The image size
    - The image in the about us page is overlapping from the div container it belonged to. So it made the picture bigger than I expected. 
- The font sizes (All pages)
    - The font sizes does not adjust automatically to fit different media devices and browser sizes.
- Footer issue
    - The footer is not sticking at the bottom of the page.
- Divs are not aligned correctly
    - When using the float parameter, some divs does not looked aligned.

### Resolved Issues
To help with the debugging with this project, I mostly used [Chrome Devtools](https://developer.chrome.com/docs/devtools/). I also used chrome devtools to see and compare what the website will look like in different devices or browser sizes.

- The image size
    - By testing using the Chrome Devtools, I was able to identify that removing the height parameter of the div where the image is in it helped resolved the overlapping issue. Also, I have set the parameter of the image to "width:100%" and "height:auto" to make sure that the image will fit in whatever the div size will be.
- The font sizes (All pages)
    - I was able to resolved this issue but changing the font size unit to rem. Eventhough that the font size is responsive/adjusts automatically I still have to check how it looked like in different devices or browser sizes (via Chrome tools again) and adjust the font size parameter accordingly.
- Footer issue
    - Searching through google helped me resolved this issue. I found this page [Stackoverflow](https://stackoverflow.com/questions/14427703/footer-not-sticking-to-bottom) and it helped me.
- Divs are not aligned correctly
    - Started using flex instead of float parameters and it helped me resolved the alignment issues and also made it easier for me to design the website moving forward.

### Unresolved Issues
_N/A_

### Page Design in Different Devices/Browser Sizes
As the website is designed for desktop size device/browser, the images the feature section should be the same. So I will only include tablet device size / mobile device size in this section.

| Features             | Tablet (950px and below) |  Mobile (600px and below) |
| -------------------- |:------------------------ | :------------------------ |
| Navigation Bar       | - The four links About Us, Menu, Find Us and Contact are changed into an <br> hamburger menu. <br> - The Logo size will automatically adjust to fit the device/browser size. | - The four links About Us, Menu, Find Us and Contact are changed into an <br> hamburger menu. <br> - The Logo size will automatically adjust to fit the device/browser size. |                                          
| Landing Page         | - The Barra Barista image and font size size will automatically adjust to fit the device/browser size. | - The Barra Barista image and font size size will automatically adjust to fit the device/browser size.|
| About Us Page        | - The image in the about us page will go underneath the paragraph. <br> - The image and font size will adjust automatically to fit the device/browser size.                 | - The image in the about us page will go underneath the paragraph. <br> - The image and font size will automatically adjust to fit the device/browser size. |
| Menu Page            | - The menu images will automatically adjust to fit the device/browser size. | - The menu images go underneath each other and will almost fill the whole width of the page. |
| Find Us Page         | - The font size and the map will automatically adjust to fit the device/browser size. | - The font size and the map will automatically adjust to fit the device/browser size. |
| Contact Page         | - The font size and the form will automatically adjust to fit the device/browser size. | - The font size and the form will automatically adjust to fit the device/browser size. |

-----

## Deployment
As the site was static, it was deployed using *GitHub Pages*.  The steps to deploy are as follows:

- In the GitHub repository, navigate to the *Settings* tab
- In the Source section select *Deploy from a branch* option in the drop-down menu
- In the Branch section select *main* option in the drop-down menu
- Keep directory set to the */root*.
- The page will reload with a link to the live site

The live link can be found here - https://jddelara01.github.io/barra-barista/

![Github Deployment Page](/assets/images/deployment.PNG)

-----

## Technologies Used

### IDE
- [GitPod](https://gitpod.io/)

### Languages and Frameworks/Resources
- [CSS3](https://www.w3.org/Style/CSS/Overview.en.html)
- [HTML5](https://developer.mozilla.org/en-US/docs/Learn/HTML)

### Project Management and Deployment
- [GitHub](https://github.com/)

### Other
- [Chrome DevTools](https://developer.chrome.com/docs/devtools/)
- [Google Fonts](https://fonts.google.com/)
- [Fontawesome 6](https://fontawesome.com/)
- [Slack](https://slack.com/intl/en-ie/)

-----

## Credits
 
### Content
- The icons in the footer were taken from [Fontawesome 6](https://fontawesome.com/)
- The icon for the hamburger menu in the navigation bar was also taken from [Fontawesome 6](https://fontawesome.com/)
- Guide on how to stick the footer in the bottom of the page was taken from [Stackoverflow](https://stackoverflow.com/questions/14427703/footer-not-sticking-to-bottom)
- Landing page idea was taken from [Soumed Studio](https://www.youtube.com/watch?v=MaIjOMx7A7I&t=280s&ab_channel=SoumedStudio)
- The fonts used were taken from [Google Fonts](https://fonts.google.com/)

### Media
- Some images were taken from an free open source site [Pexels](https://www.pexels.com/) and the other images were provided by the Barra Barista owner Vincent Regidor (regidorvincent@rocketmail.com)
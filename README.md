# Craftworks – Portfolio Project 1

![Website mockup covering a range of devices](docs/testing/mockup.png)

## [Link to live web application]( https://beratzorlu.github.io/Craftworks/)

---

## Project Documentation
### Welcome to Craftworks

Craftworks is a web development project developed as a part of Code Institute’s full-stack web development curriculum. It is structured around creating an interactive front-end web application while mainly using HTML5 and CSS3 languages from the ground up.

This documentation covers information about the central principles that drove the project. As a synopsis, the reader will learn more about UX/UI development, application testing and deployment, code structure and maintainability, bug fixes, the overall design process and the future plans for the project.

The subject of this project, Craftworks, is a fictional woodworks workshop based in Dublin that offers services to customers that help build their household furniture projects. More details about the design of the website and Craftworks as a company will follow in the remainder of this documentation.

The principles of CARE had a significant impact on the creation of this project where cohesion, accessibility, responsivity and essentiality were key notions that directly influenced the end product.

---

## Table of Contents

-   [User Experience (UX)](#user-experience-ux)
    -   [User Stories](#user-stories)

-   [Design Process](#design-process)
    -   [User Experience Design (UXD)](#user-experience-design-uxd)
    -   [Wireframes](#wireframes)
    -   [Colour Palette](#colour-palette)
    -   [Typography](#typography)
    -   [Images](#images)

-   [Website Features](#website-features)
    -   [Shared Elements](#shared-elements)
    -   [Home](#home)
    -   [Gallery](#gallery)
    -   [About](#about)
    -   [Order](#order)
    -   [Thank You](#thankyou)
    -   [404 Page](#404-page)

-   [Future Features](#future-features) 

-   [Testing](#testing)
    -   [User Stories Testing](#user-stories-testing) 
    -   [Browser Testing](#browser-testing)
    -   [Device Testing](#device-testing)

-   [Validation](#validation)
    -   [HTML](#html)
    -   [CSS](#css)
    -   [Lighthouse](#lighthouse)
    -   [Accessibility](#accessibility)
    -   [Mobile Compatibility](#mobile-compatibility)

-   [Bug Fixes](#bug-fixes)

-   [Deployment](#deployment)

-   [Future Features](#future-features)

-   [Technologies Used](#technologies-used)
    -   [Hardware](#hardware)
    -   [Software](#software)
    -   [Platforms](#platforms)

-   [Credits and References](#credits-and-references)

-   [Closing Remarks](#closing-remarks)

---

## User Experience (UX)

This project aims to achieve the core purpose of directing a user interested in buying custom wooden furniture in Dublin to the functionality available on this web application.

### User Stories

- User Stories

    - As a user, I want to be able to see a section about the ethos and philosophy of the company.
    - As a user, I want to be able to see previous work produced by the workshop.
    - As a user, I want to be able to view the workshop opening times, location, and contact details.
    - As a user, I want to be able to place an order.
    - As a user, I want to be able to see how to follow the workshop on social media.

- Objectives

    - Client Objectives:
        - For potential customers to find the workshop.
        - For potential customers to place an order by telephone or form.
        - To represent a positive brand image for attracting potential customers to the shop.
        - To provide examples of products to promote transparency.
        - To encourage current customers to stay up-to-date about their orders.

    - First Time Customer Objectives:
        - To easily locate the physical workshop.
        - To see examples of furniture available.
        - To easily find contact information.
        - To place an order.
        
    - Frequent Visitor Objectives:
        - To follow the workshop's social media channels to further connect with the company.
        
    - Returning Customer Objectives:
        - To have the most recent contact and customer feedback information.

---


## Design Process

### User Experience Design (UXD)

The five pillars of user experience discussed in Code Institute's curriculum heavily informed the user experience design process. These are namely strategy, scope, structure, Skeleton and surface.

- ### Strategy 

    Having no prior knowledge of the woodworks industry, research surrounding the active businesses in the woodworks industry that operate in Dublin was paramount. As a result, two companies stood out as prominent and inspirational examples to understand the expectations in terms of web design: [Custom Furniture Ireland](https://www.customfurniture.ie/) and [Diamond Furniture Ireland](https://www.diamondfurniture.ie/). While these two companies did not have direct a impact on the choice of elements and features, they informed the project of the overall functionality that the website of a custom woodworks company would need.

- ### Scope

    User stories and objectives inform the overall scope of this project. While it is important to research the existing entities in the same industry in Dublin, it is possibly more so to understand the potential needs of a user. Thus, there was a close relationship between the user stories and feature design throughout the entirety of the project.

- ### Structure

    In regards to the structure of the website, much of the implementations followed the conventions in web design. However, it is important effectively take advantage of this situation by organizing content that makes them easier to find and inviting to interact with. Examples of this available in the project are using hover effects on page links and adding zoom to the gallery items.

- ### Skeleton

    The design approach in this area was minimalistic with an emphasis on a balance between form and function. Across all the pages, a user will find concise information with a welcoming tone of language accompanied by interactive and visual elements. This allows the users to obtain and digest relevant information as soon as possible without spending too much time navigating across the website. Each page of the project contains unique elements that promote a feeling of familiarity from the user.

- ### Surface

    In keeping with the approach to the incorporation of the skeleton plane, the surface plane contributes to this project in the form of situating features and elements into a "clean" and "spacious" visual design approach. Because of this, users will find white space and thin font styles that do not carry much weight on the screen but offer aesthetic value without sacrificing readability.

---

## Wireframes

Wireframes were designed using software named Balsamiq.

### Home Page

- Desktop 
    - ![wireframe-home-desktop](docs/Browser%20Homepage.png)
- Tablet
    - ![wireframe-home-tablet](docs/Ipad%20Homepage.png)
- Phone
    - ![wireframe-home-phone](docs/IOS%20Homepage.png)

### Gallery Page

- Desktop 
    - ![wireframe-gallery-desktop](docs/Browser%20Gallery.png)
- Tablet
    - ![wireframe-gallery-tablet](docs/Ipad%20Gallery.png)
- Phone
    - ![wireframe-gallery-phone](docs/IOS%20Gallery.png)

### About Page

- Desktop 
    - ![wireframe-about-desktop](docs/Browser%20About%20Us.png)
- Tablet
    - ![wireframe-about-tablet](docs/Ipad%20About%20Us.png)
- Phone
    - ![wireframe-about-phone](docs/IOS%20About%20Us.png)

### Order Page

- Desktop 
    - ![wireframe-order-desktop](docs/Browser%20Order%20Form.png)
- Tablet
    - ![wireframe-order-tablet](docs/Ipad%20Order%20Form.png)
- Phone
    - ![wireframe-order-phone](docs/IOS%20Order%20Form.png)

---

---

### Colour Palette

Implementation of a colour palette that prioritized maintaining a balance between aesthetic quality and readability produced a result that satisfied the needs of this project.

[Coolors](https://coolors.co/) was a highly beneficial resource in this regard which provided significant help in identifying
matching colours that also have appropriate contrast.

![Colour Palette](docs/pp1_colour_scheme.png)

---

### Typography

[Code Institute](https://codeinstitute.net/ie/)'s recommended approach to choosing fonts on [Google Fonts](https://fonts.google.com/about) was sufficient in finding satisfactory font families. Below is the list of fonts used to stylize the text content of the project;

- Headings: Lora (Normal 400)
    ![Lora](docs/lora.png) 
- Smaller Headings: Josefin Slab (Light 300)
    ![Josefin Slab](docs/josefin_slab.png)
- Text: Frank Rurl Libre (Light 300)
    ![Frank Rurl Libre](docs/frank_ruhl_libre.png) 

However, while this list provided a consistent aesthetic for the website, there have been situations where some of the font types were used outside of their determined purpose. For example, using Lora and Josefin Slab interchangeably at times for purposes of cohesion.

---

### Images

The overall imagery present on the website consists of pictures that have at least a minor connection with the theme of woodworks.
Conveying a welcoming and organized visual language was the main approach towards deciding what images to choose specifically. However, at the same time as this idea, it was equally important to ensure that the pictures displayed the physical actions associated with craftsmanship while also displaying a positive outlook towards similar labour. This is most apparent in the hero images sections.

[Pexels](https://www.pexels.com/) and [Pixabay](https://pixabay.com/) were the platforms that this project resourced its image files.

---

## Website Features

The design considerations that impacted the envisioned features were mainly structured around conventional website design. While there were more features planned in the initial stages of the project, some were not entertained to the benefit of serving the needs referenced in the [User Stories](#user-stories) section. Thus, it was important to focus on a minimum viable project rather than prioritizing the implementation of further features for the sake of it. This would only bloat the website without adding much value to the user experience overall.

### Shared Elements

The below elements are available to be experienced by the user across the website as a whole.

- #### Navigation

![navigation bar](docs/nav_bar.png)

Taking a straightforward and practical approach resulted in the creation of the navigation element provided above. All elements have hover effects to provide user feedback and underlines to display the active page. The order page has unique styling to emphasize the core function of the project; to encourage customers to make use of the services provided by Craftworks by placing an order. The logo is displayed at all times to motivate a feeling of familiarity in the user.

- #### Hero Image and Text Card

![hero image](docs/hero_image.png)

In keeping with the points available in the [Images]{#images} section, the choice of hero image here represents a positive outlook towards the actions associated with woodworks. By displaying a laughing lady holding a wooden material, the hero image section aims to instil a sense of welcome from the user.

While the content inside the text card is not identical the framework itself is shared across the website. This serves multiple purposes by both welcoming and reassuring the users of which page they are currently displaying on their respective devices.

- #### Footer

![footer](docs/footer.png)

The footer represents a minimalistic design philosophy. The social media websites of the company are displayed openly and clearly by providing appropriate spacing and medium-size social media logos. There is also a signature text provided in the bottom centre of the footer to refer users to the developer responsible for this project. ([Berat Zorlu](https://github.com/beratzorlu/Craftworks))

- #### Favicon

![favicon](android-chrome-192x192.png)

Designing a favicon for the website was a process that required a series of trials and errors to find the design that fit the project most appropriately. Providing image sizes that also fit different browsers and devices is an important concern in this area. 

[Canva](https://www.canva.com/) was the service that allowed the design and creation of this element.

### Home

![home](docs/home_page.png)

The home page mainly serves the purpose of communicating the core purpose and motivations of Craftworks both as a company and as a social community. Through the "Our Promises" section, users can learn about the quality of the products, delivery assurance as well as the enthusiasm of the company to work alongside their customers to produce an end product.

### Gallery

![gallery](docs/gallery_text.png)

Users are greeted to the section with a box of text inviting them to interact with the following gallery feature and learn more about the production quality of the company. This provides transparency about the capacity of the company to deliver on its promises mentioned in the [home](#home) section.

- #### Gallery Grid

![grid](docs/grid.png)

This element is practically the critical component of this project. The gallery grid serves to compel the users and provide them with an aesthetically pleasing viewing experience during their time exploring the website. Having found an interactive gallery element displaying instances of successful products, it is more likely for the users to view the order form.

### About

![about](docs/about_page.png)

Structurally the about page shares designs visible in the previous pages, however, the section itself includes key details for users to successfully communicate with and locate the workshop.

- #### Key Details Info Card

![key details](docs/key_details.png)

This information card provides all the necessary details for a customer or user to effectively interact with the company. Thus, the about section specifically refers to this need by displaying this element as its content. This straightforward approach allows the user to directly access all the information they need about the company. 

While it would have been practical for the user to find this information on the home page, it was more fitting to recognize user agency by allowing them to display such information *if* and *when* they want by clicking on the about link.

### Order

![order page](docs/order_page.png)

Once users reach the order page they will find a unique hero image accompanied by a text box detailing the ordering process. By displaying hands working on a wooden material, the order page aims to communicate that work is about to begin. It also features a background image of a workshop to further reinforce this idea.

- #### Order Form

![order form](docs/order_form.png)

The order form represents the core function of the website. It is how the users establish a direct connection with the services that the company offers. The form includes all necessary details and input for a user to communicate their design ideas and demands as well as their contact information and choice of payment. All these elements combined allow for the submission of a complete and informative experience for both sides. 

- #### Order Button

![order button](docs/order_button.png)

While this is not a necessary feature for the form to function as intended, it allowed for an opportunity to demonstrate my aptitude regarding the implementation of HTML and CSS into the project. Moreover, providing a button that reacts and responds to the interactions of the user improves the overall experience gained from submitting the form.

### Thank You

![thank you](docs/thank_you.png)

The thank you page shares its structure with the [Order Form](#order-form) page. Its main purpose is to reassure the user that the form worked as intended and completed the query initiated by the customer. Thus, ensuring that everything is functioning properly and that there is no cause for concern.

### 404 Page

![404](docs/404_page.png)

404 pages are elements that are not commonly visible to the user. Thus, this page aims to help navigate users back to the home page to prevent them from feeling lost. The 404 page is a unique element within the project is it leverages the fact that it will not be commonly visible to the users by displaying a puppet as comic relief.

---

## Future Features

- ### Iframe Google Maps
    - This will provide visual feedback for the locational information of the website. While originally planned as a feature, this idea was later scrapped in favour of ensuring the production of a minimum viable product.
- ### Back to Top Button
    - This will help with easier navigation.
- ### Interactive Infographic for Ordering Process
    - Users will be able to access and digest relevant information.
- ### Order Tracking & Updates
    - It is beneficial for both parties to ensure there is constant communication between the company and the customer. Providing real-time information about their order is an effective way to achieve this.
- ### Creative Club Section
    - Another section that invites customers to sign up to learn about woodcrafts would provide another stream of income as well as another intractable form element on the website. 
- ### Hero Video
    - This would improve the overall look of the website by providing a more professional aesthetic to the webpage. The video would need to be muted and looped.

---

## Testing 

The testing procedure began immediately after the deployment of the website on [GitHub Pages](https://pages.github.com/). Early deployment was important to ensure the reliability of the features available in the project before moving on to implementing further elements. Friends and family were important players in the testing process who were happy to constantly play with the deployed website to see if they can find issues and suggest improvements; I am grateful for their commitment and help.

- ### User Stories Testing 

    - As a user, I want to be able to see a section about the ethos and philosophy of the company.
        - ![home](docs/home_page.png)
    - As a user, I want to be able to see previous work produced by the workshop.
        - ![grid](docs/grid.png)
    - As a user, I want to be able to view the workshop opening times, location, and contact details.
        - ![key details](docs/key_details.png)
    - As a user, I want to be able to place an order.
        - ![order form](docs/order_form.png)
    - As a user, I want to be able to see how to follow the workshop on social media.
        - ![footer](docs/footer.png)

- ### Browser Testing
- Three major internet browsing applications were used for the browser testing process producing an overall satisfactory result.
    - Firefox
        - ![firefox](docs/firefox_test.png)
    - Chrome
        - ![chrome](docs/chrome_test.png)  
    - Edge
        - ![edge](docs/edge_test.png)

- ### Device Testing
- The devices provided below are items that were available at the time of the device testing process. While there was a gap in the number of platforms accessible at the time, the test outcome incorporates 2 main mobile platforms and a powerful gaming laptop. 
    - Monster Abra A5 V13.4 15.6" Laptop
        - ![monsterabra](docs/firefox_test.png)
    - Apple iPhone 7 Plus
        - ![iphone7+](docs/iphone_test.jpg)
    - Samsung Galaxy A51
        - ![galaxya51](docs/samsung_test.jpg)

---

## Validation

### HTML

- Home
![indextest](docs/html_index_validation.png)
- Gallery
![gallerytest](docs/html_gallery_validation.png)
- About
![abouttest](docs/html_about_validation.png)
- Order
![ordertest](docs/html_order_validation.png)
- Thank You
![thankyoutest](docs/html_thankyou_validation.png)
- 404
![404test](docs/html_404_validation.png)

### CSS

- styles.css
![csstest](docs/css_validation.png)

### Lighthouse

- Mobile 
    - ![lighthousedesktop](docs/lighthouse_mobile.png)
- Desktop 
    - ![lighthousemobile](docs/lighthouse_desktop.png)

### Accessibility

- Home
![homeacc](docs/acc_home.png)
- Gallery
![galleryacc](docs/acc_gallery.png)
- About
![aboutacc](docs/acc_gallery.png)
- Order
![orderacc](docs/acc_order.png)
- Thank You
![thankyouacc](docs/acc_thankyou.png)
- 404
![404acc](docs/acc_404.png)

### Mobile Compatibility

- Mobile-Friendly Test
    - ![mbt](docs/mobile_friendly_test.png)

---    

## Bug Fixes

- Gallery Grid Image Load Failure
    - Fixed by removing the "/" present before the relative path declarations in the associated HTML code.
- Navigation Bar Responsivity
    - Fixed by removing <code>position:absolute</code> and adding <code>display:flex</code>.
- Home Text Overflow
    - Fixes by implementing media queries to add a whitespace that accommodates the text flowing downwards.  

---

## Deployment

This project was deployed utilizing GitHub pages using the following procedure;

1. After creating a repository for the project, select the settings tab indicated by a :gear: icon.
2. Navigate to the "Code and Automation" section on the left side of the page and click on the "Pages" link.
3. Having done this, select "Main" and then the "root" folder from the drop-down branch menu.
4. Hit "save" to ensure that your changes are recognised by the service.
5. Finally, if previous steps were followed correctly GitHub will create a page and present a URL to the deployed website.

---

## Technologies Used

### Hardware

- Monster Abra A5 V13.4 15.6" Laptop
- Samsung VA 1920x1080 144Hz Curved Gaming Monitor
- iPhone 7 Plus
- Samsung Galaxy A51

### Software

- Mozilla Firefox: Main browser used for development, testing and device simulation.
- Google Chrome: Secondary browser for testing and device simulation.
- Microsoft Edge: Tertiary browser for testing.
- Firefox Mobile: Mobile testing of the deployed site.
- Chrome Mobile: Mobile testing of the deployed site.
- Safari Mobile: Mobile testing of the deployed site.
- GIMP: Used for converting .jpg and .png files to .webp for site optimization.
- Balsamiq: Used for wireframing.
- Windows Snip & Sketch: Capturing screenshots for readme and archiving identified bugs.
- Microsoft Snipping Tool: Fallback screen capture software when MS Snip & Sketched became unresponsive.

### Platforms

- GitHub: Version control and site deployment.
- GitPod: Integrated Development Environment (IDE) chosen for this project.
- Pexels: Primary source for high-quality royalty-free images.
- Pixabay: Secondary source for high-quality royalty-free images.
- Google Fonts: Finding and exporting third-party fonts for the website.
- CodePen: For quickly testing out ideas before carrying them to 
DevTools.
- Font Awesome: For importing fonts to further decorate text elements.
- Coolors: For creating a matching colour palette that has appropriate contrast.
- Code Beautify: For looking for differences between two pieces of code. This helped me identify my mistakes.

---

## Credits and References

- [Code Institute](https://codeinstitute.net/): I would like to thank Code Institute for their support and guidance throughout the development of this project.
    - The [Love Running](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LR101+2021_T1/courseware/4a07c57382724cfda5834497317f24d5/f2db5fd401004fccb43b01a6066a5333/) project was helpful in providing a place to start developig my project.
- [UCD Professional Academy](https://www.ucd.ie/professionalacademy/): I would like to thank UCD PA for their facilitator and masterclass sessions in partnership with Code Insitute. These have been invaluable in better understanding relevant theory and practice elements.
- [Stack Overflow](https://stackoverflow.com/): This project heavily made use of Stack Overflow for troubleshooting problems that occurred throughout the development process. Below is an entry that I used to fix an ordering issue in the navigation bar;
    - [Menu appears in reverse order](https://stackoverflow.com/questions/17964749/menu-appears-in-reverse-order) (This post is active at the time of writing this documentation.)
    - [Navigation item styling exception rule](https://stackoverflow.com/questions/53241566/how-to-make-exceptions-to-css-rules) (This post is active at the time of writing this documentation.)
- [Adam Gilroy](https://github.com/adamgilroy22/happy-dog-cafe): Adam's Happy Dog Cafe project has been an inspiration for me. More specifically, his approach to implementing an info card was interesting to me and I wanted to see how I could do the same for my project.
- [Joseph Smith](https://github.com/jts272/pp1-happy-bees-cafe): Joseph's approach towards developing a gallery grid was intriguing to me. I wanted to implement a similar structure to my website by changing and adding to his approach to make it my own. 
- [W3Schools](https://www.w3schools.com/): W3S was an excellent resource in understanding and practicing CSS and HTML frameworks
before implementing them into my project. The code I implemented from them is as follows;

    - [CSS List Without Bullets](https://www.w3schools.com/howto/howto_css_list_without_bullets.asp)
    - [Background Position](https://www.w3schools.com/csSref/pr_background-position.php )
    - [CSS Button Animation](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_buttons_animate3)

- [Envato Tuts+](https://www.youtube.com/watch?v=qhhbybFPTbU): A video from a channel named Envato Tuts+ was helpful in understanding how to align items with flex.
- [Alvaro Trigo](https://alvarotrigo.com/blog/css-transition-duration/): Alvaro's blog post about CSS transition durations helped make the ease-in-out effect for the gallery grid work as intended. 
- [Kinsta](https://kinsta.com/blog/responsive-web-design/): This blog on Kinsta.com allowed me to better understand using resolution breakpoints while developing my media queries for website responsivity.
- [Web.Dev](https://web.dev/centering-in-css/): Web.Dev's blog about centring in CSS allowed me to fix an issue that I was encountering while working on making the navigation bar responsive.

--- 

## Closing Remarks

Overall, developing the Craftworks project has provided myriad opportunities to learn and practice using HTML and CSS to build an industry-level website. This has greatly impacted my capacity to understand the frameworks associated with implementing various techniques regarding the front-end aspect of web development.

The development process overall has been more non-linear than initially foreseen. It was often the case where a particular issue would take a long period to solve as the solution would behave differently in other platforms. Regardless, this ultimately provided an important learning point where patience is key in finding an appropriate issue in development overall. Without a sound understanding and practice of this notion, one will find it difficult to effectively manufacture solutions to problems that will appear during the development process. 

Having the support of my fellow students on the official Code Institute Slack channel and my mentor Rohit Sharma was an invaluable asset to have.

I am grateful to have been able to come to these learning points through this project and feel accomplished to have designed and developed my Craftworks projects from the ground up. 

---
 [Back to Top](https://github.com/beratzorlu/Craftworks/)
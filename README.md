# Craftworks – Portfolio Project 1

![Website mockup covering a range of devices](docs/testing/mockup.png)

## [Link to live web application]( https://beratzorlu.github.io/Craftworks/)

---

## Project Documentation
### Welcome to Craftworks

Craftworks is a web development project developed as a part of Code Institute’s full stack web development curriculum. It is structured around creating an interactive front-end web application while mainly using HTML5 and CSS3 languages from ground up.

This documentation covers information about the central principals drove the project. As a synopsis, the reader will learn more about the UX/UI development, application testing and deployment, code structure and maintainability, bug fixes, overall design process and the future plans for the project.

The subject of this project, Craftworks, is a fictional woodworks workshop based in Dublin that offers services to customers that help build their household furniture projects. More details about the design of the website and Craftworks as a company will follow in the remainder of this documentation.

Principles of CARE had a significant impact on the creation of this project where cohesion, accessibility, responsivity and essentiality were key notions that directly influenced the end product.

---

## Table of Contents

-	[User Experience (UX)](#user-experience-ux)
    -	[User Stories](#user-stories)

-	[Design Process](#design-process)
    -	[User Experience Design (UXD)](#user-experience-design-uxd)
    -	[Wireframes](#wireframes)
    -	[Colour Palette](#colour-palette)
    -	[Typography](#typography)
    -	[Images](#images)

-	[Website Features](#website-features)
    -	[Home](#home)
    -	[Menu](#menu)
    -	[Gallery](#gallery)
    -	[About](#about)
    -	[Order](#order)
    -	[Thank You](#thankyou)
    -	[404](#404)

-	[Testing](#testing)
    -	[Features Testing](#features-testing)
    -	[User Stories Testing](#user-stories-testing)

-	[Validation](#validation)
    -	[HTML](#html)
    -	[CSS](#css)
    -	[Lighthouse](#lighthouse)
    -	[Accessibility](#accessibility)
    -	[Mobile Compatibility](#mobile-compatibility)

-	[Bug Fixes](#bug-fixes)

-	[Deployment](#deployment)

-	[Version Control](#version-control)

-	[Future Features](#future-features)

-	[Technologies Used](#technologies-used)
    -	[Hardware](#hardware)
    -	[Software](#software)

-	[Credits](#credits)

-	[Closing Words](#closing-words)

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
        - To encourage current customers to stay up-to-date about their order.

    - First Time Customer Objectives:
        - To easily locate the physical workshop.
        - To see examples of furnitures available.
        - To easily find contact information.
        - To place an order.
        
    - Frequent Visitor Objectives:
        - To follow the workshop's social media channels to further connect with the company.
        
    - Returning Customer Objectives:
        - To have the most recent contact and customer feedback information.

---


## Design Process

### User Experience Design (UXD)

The five pillars of user experience discussed in Code Institute's curriculum heavily informed the uxer experience design process. These are namely strategy, scope, structure, Skeleton and surface.

- ### Strategy 

    Having no prior knowledge of the woodworks industry, research surrounding the active businesses in the woodworks industry that operate in Dublin was paramount. As a result, two companies stood out as prominent and inspirational examples to understand the expectations in terms of web design: [Custom Furniture Ireland](https://www.customfurniture.ie/) and [Diamond Furniture Ireland](https://www.diamondfurniture.ie/). While these two companies did not have direct a impact on the choice of elements and features, they informed the project of the overall functionality that the website of a custom woodworks company would need.

- ### Scope

    User stories and objectives inform the overall scope of this project. While it is important to research the existing entities in the same industry in Dublin, it is possibly more so to understand the potential needs of a user. Thus, there was a close relationship between the user stories and feature design throughout the entirety of the project.

- ### Structure

    In regards to the structure of the website, much of the implementations followed the conventions in web design. However, it is important effectively take advantage of this situation by organizing content that make themselves easier to find and inviting to interact with. Examples of this available in the project are using hover effects on page links and adding zoom to the gallery items.

- ### Skeleton

    The design approach in this area was minimalistic with an emphasis on a balance between form and function. Across all the pages, a user will find concise information with a welcoming tone of language accompanied by interactive and visiual elements. This allows the users to obtain and digest relevant information as soon as possible without spending too much time navigating across the website. Each page of the project contains unique elements that promote a feeling of familiarity from the user.

- ### Surface

    In keeping with the approach to the incorporation of the skeleton plane, the surface plane contributes to this project in the form of situating features and elements into a "clean" and "spacious" visual design approach. Because of this, users will find white space and thin font styles that do not carry much weight on the screen but offer aesthetic value without sacrificing readability.

---

### Wireframes



### Colour Palette

Implementation of a colour palette that prioritized maintaining a balance between aesthetic quality and readability produced a result that satisfied the needs of this project.

[Coolors](https://coolors.co/) was a highly beneficial resource in this regard which provided significant help in identifying
matching colours that also have appropriate contrast.

![Colour Palette](docs/pp1_colour_scheme.png)

---

### Typography

[Code Institute](https://codeinstitute.net/ie/)'s reccomended approach to choosing fonts on [Google Fonts](https://fonts.google.com/about) was sufficient in finding satisfactory font families. The below is the list of fonts used to stylize the text content of the project;

- Headings: Lora (Normal 400)
    ![Lora](docs/lora.png) 
- Smaller Headings: Josefin Slab (Light 300)
    ![Josefin Slab](docs/josefin_slab.png)
- Text: Frank Rurl Libre (Light 300)
    ![Frank Rurl Libre](docs/frank_ruhl_libre.png) 

However, while this list provided an consistent aesthetic for the website, there have been situations where some of the font types were used outside of their determined purpose. For example, using Lora and Josefin Slab interchangibly at times for purposes of cohesion.

---

### Images

The overall imagery present on the website consists of pictures that have at least a minor connection with the theme of woodworks.
Conveying a welcoming and organized visual language was the main approach towards deciding what images to choose specifically. However, at the same time as this idea, it was equally important to ensure that the pictures displayed the physical actions associated with craftsmanship while also displaying a positive outlooks towards similar labour. This is most apparent in the hero images sections.

[Pexels](https://www.pexels.com/) and [Pixabay](https://pixabay.com/) were the platforms that this project resourced its image files from.

---

## Website Features

The design considerations that impacted the envisioned fatures were mainly structured around convential website design. While there were more features planned in the initial stages of the project, some were not entertained to the benefit of serving the needs referenced in the [User Stories](#user-stories) section. Thus, it was important to focus on a minimum viable project rather than prioritizing the implementation of further features for the sake of it. This would only bloat the website without adding much value to the user experience overall.

- ## Home





















### Features

- Mobile First Design
    - To cater for the most popular devices used by people across the world.

- Homepage
    - Header
    - Hero image
    - Welcome card
    - Ethos
    - Working hours
    - Contact details
    - Order form link
    - Footer

- Gallery
    - Header
    - Organized images of previous work
    - Call to action (For ordering)
    - Footer

- About Us
    - Header
    - Company history
    - Contact information
    - Location (iframe)
    - Footer

- Order 
    - Header
    - Sticky background image
    - Form
    - Footer
    - ---> Thank you message

- Errors
    - Custom 404 page & message

### Future Features
- Back to top button
- Ordering process horizontal plane
- Order tracking & updates 
- Creative club
- Hero video

### Typography and Color Scheme

#### Typography 

The idea behind the creation of this web application stems from a family business. Having a relative who owns a company in the custom woodworks sector, it was appropriate to develop a web application that would complement their experiences. This allowed for a means of access to feedback regarding the potential expectations of companies and customers working custom woodworks. Information of this kind was expecially helpful during the visual design process which informed the typography and colour scheme choices of this project.

I wanted a modern and classy look. To find this, I used Google Fonts to find the most appropriate font for my needs. Lora matched my expectations suitably and I decided that I would use it for main headings. After this point, I used Fontjoy.com to find pairings that complimented Lora. <--> and Josefin Slab worked well in this case where I used the former for hero cards and the latter for paragraphs.

#### Colour Scheme

The thinking process behind this colour scheme involved choosing colours that complimented shades of brown. My idea was that choosing the most common colour associated with the most common material of woodworks would fit theme of this web application. Thus, to achieve this, I used coolors.co
to bring together a colour palette appropriate for my needs. Flexibility in this area was an important aspect of the design process as well. I wanted the colours to be usable individually if used on their own.

{Provide the colour scheme jpg here.}

Ultimately, I decided on a collection of colours that I am contend with that also appropriately fit the purposes of this project.

### Wireframes

{Provide the wireframe jpgs here.}

===== Before Code/implementation ===
7. Technology
8. testing
   8.1 code validation
   8.2 test cases (user story based with screenshots)
   8.3 fixed bugs
   8.4 supported screens and browsers
9. Deployment
   9.1 via gitpod
   9.2 via github pages
10. credits
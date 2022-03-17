# CODE REFACTOR PROJECT
*This assignment is to update the index.html and style.css for the Horiseon website with accessability syntax

- [CODE REFACTOR PROJECT](#code-refactor-project)
  - [Screenshot](#screenshot)
  - [Link to website](#link-to-website)
  - [Requirements](#requirements)
  - [My Process](#my-process)
    - [Semantic Elements](#semantic-elements)
    - [Keeping the Structure of the Site](#keeping-the-structure-of-the-site)
    - [Alt Attributs](#alt-attributs)
    - [Heading Atribute Order](#heading-atribute-order)
    - [Title Description](#title-description)
  - [Resources](#resources)

## Screenshot
![Alt text](./assets/images/Screenshot%20(25).png "Horiseon Screenshot")

## Link to website
[Horiseon Site!](https://nbrown225.github.io/code-refactor/)

## Requirements 
* Assure that the source code has Semantic HTML Elements
* Assure that the elements do not change the structure of the site styling / positioning
* Assure Icons and Images h ave Alt Attributes to meet accessibility standards
* Assure the Heading Attributes are in sequential order
* Assure the title is concise and descriptive

## My Process

### Semantic Elements
- Changed ```<div>``` to the ```<header>```, ```<body>```, ```<footer>```to give more information to the browser
- Also added ```<article>``` so accessibility will know the difference in the sections of the page
### Keeping the Structure of the Site
- Changing the classes/id's in HTML to match CSS
  - ``` <h1>Hori<span id="seo">seo</span>n</h1>``` which correlated to ```header h1 #seo ``` in the CSS. This put emphasis on the "SEO" in Horiseon.
  
  - ```<section class="hero">``` and ```.hero {
    height: 800px;
    width: 100%;
    margin-bottom: 25px;
    background-image: url("../images/digital-marketing-meeting.jpg");
    background-size: cover;
    background-position: center;
}``` which to the page to add the Hero image and giff it 800 px height, 100% width so it will fit the whole page etc.

### Alt Attributs
- added ```<alt>``` and discriptions to each ```<img>```
  - ```<img src="./assets/images/search-engine-optimization.jpg" alt="work desk with laptop, coffee and work supplies. pens, notbook, magnifying glass" class="float-left" />```
### Heading Atribute Order
- made sure ```<h1>``` was only included on the most important tags and the rest of the page was given ```<h2>``` or ```<h3>```
### Title Description
- Changed the title from "website" to "About Horiseon"
   
## Resources
* Github
  * to create the repository
* Git bash
  * to run updates
* VS Code
  * to update the code
* Google and Youtube
  * for assistance on the assignment  





# A  Profile Website
Wildlife Society, this is community blog dedicated to promoting environmental awareness and sustainable living website build with HTML and CSS. It includes sections for Home, About, Project, Team, Galery, and Contact.

## Table of Contents
1. [Introduction](#home)
2. [About Us](#about)
3. [What We Do](#project)
4. [Team](#team)
5. [Galery](#galery)
6. [Contact Us](#contact)


## Features of Wildlife Society Blog
1. User-Friendly Navigation with intuitive layout and design for easy browsing.
2. Commenting System alow reader to leave comments and feedback.
3. Galery about news and developments in wildlife conservation content.
4. Regular Project and Programe for world between people and nature.
5. Contact Form with service section.
6. Footer with copyright information.

## Technologies Used
- HTML5 and CSS

## Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/revou-fsse-oct24/module-2-ferianai.git
    ```
2. Navigate to the project directory:
    ```bash
    cd module-1-ferianai
    ```
3. Open the `index.html` file in your browser:
    ```bash
    open index.html
    ```
4. **Image Folder** (img folder will located in the repository module-1-ferianai) to call it into html you can use " img/ " :
    ```bash
    
    <img src="img/tiger-banner-web.jpg" alt="tiger">
    ```

## Code
- This web aplied with custome font using embed : Plus Jakarta Sans

>html code
```bash
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:ital,wght@0,200..800;1,200..800&display=swap" rel="stylesheet">
```
>css code
```bash
    body{
      font-family: "Plus Jakarta Sans", Arial, Helvetica, sans-serif;
      font-weight: 400;
    }
```

- We aplied text-shadow to text  and list style to the list
>html code text-shadow and list style combine with tailwindcss
```bash
    <div class="pb-16">
      <h3 class="text-xl font-bold drop-shadow-xl"> More Project Categories: </h3>
      <ul class="list-disc pl-8">
        <li><a class="hover:underline hover:text-blue-600" href="#">Kitchens & Dining Areas</a></li>
        <li><a class="hover:underline hover:text-blue-600" href="#">Living Rooms Inspirations</a></li>
        <li><a class="hover:underline hover:text-blue-600" href="#">Bedrooms</a></li>
        <li><a class="hover:underline hover:text-blue-600" href="#">Bathrooms Oasis</a></li>
        <li><a class="hover:underline hover:text-blue-600" href="#">Small Spaces & Studios</a></li>
        <li><a class="hover:underline hover:text-blue-600" href="#">Outdoor Spaces & Patios</a></li>
      </ul>
    </div>
```
- Have responsive background image with cover size :
```bash
  .projectpage{
    background-image: url(img/bg-about-bw.jpg);
    background-size: cover;
    background-position: center;
  }
```
> capture
![backgroundimage](/documentation/background-img.png)

- Have responsive image with picture + source + srcset  method
```bash
  <picture>
    <source class="w-full" media="(max-width: 400px)" srcset="img/banner-living01-hp.jpg" alt="livingroom" >
    <source class="w-full" media="(max-width: 800px)" srcset="img/banner-living01-tablet.jpg" alt="livingroom" >
    <img class="w-full" src="img/banner-living01.png" alt="livingroom">
  </picture>
```

- Asymmetrical Grid for Galery 
> capture

![grid](/documentation/grid.png)


- Animation with transition and animation method


## 🔗 Links
[![WildlifeSocietyWeb](/documentation/logo.png)](https://ferianai.github.io/WildlifeSociety/)


## Page Overview applying Responsive Design with media query 

### Desktop Template
![Desktop](/documentation/desktop.png)

### Tablet Template
![Tablet](/documentation/tablet.png)

### Mobile Template
![Mobile](/documentation/mobile.png)




<!-- 
[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/mEdQF3Ol) -->

# Product_informations
This project is a page with 3 colomns, informing about the subject. In my project i wrote about 3 car models.
The purpose of improving the page would be to click on the button would show more information and photos of the car.


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview


### The challenge

The users should be able to:
- See informations about the cars.
- Click on button to more informations.
- View the optimal layout depending on their device's screen size.

### Screenshot
![image](https://user-images.githubusercontent.com/117602073/213932536-43a762f9-e5f1-4385-8b1d-f46c96dffbdf.png)

### Links

- https://product-informations.vercel.app/


## My process

### Built with

- Semantic HTML 
- CSS custom properties
- Flexbox
- Responsiveness
- Pseudo-classes
- Media query
- Optimization, writing equal codes for more than one element

### What I learned

I dedicated my time to apply Pseudo-classes and media query, become my website responsive.
That way it doesn't matter where it'll be opened, in cell phone or notebook.

```CSS
@media  (max-width:800px) {
    .box_container {
        min-width:initial;
        max-width: initial;
        max-height: initial;
        display: initial;
        margin-top: 20%;
        width: 270px;
        height: 100%;
    }

    .box_sedans, .box_suvs, .box_luxury {
        min-width: initial;
        width: 100%;
        min-height: initial;
        height: 380px;
        box-sizing: border-box;
        padding: 30px 35px;
    }

    .box_sedans {
        border-radius: 7px 7px 0 0;
    }
    
    .box_luxury {
        border-radius: 0 0 7px 7px;
    }
}
}
```

### Continued development

i'll learn how to use JS on my projects, this language it's important to development.

### Useful resources

This resource helped me a lot to understand how to do what I wanted.
https://www.w3schools.com/css/css3_mediaqueries.asp
https://www.w3schools.com/css/css3_mediaqueries_ex.asp

## Author

- Linkedin - https://www.linkedin.com/in/helcio-anicio/ 
- Vercel - https://vercel.com/helcioanicio


<!-- ## Acknowledgments -->
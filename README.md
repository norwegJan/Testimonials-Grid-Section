# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size


### Links

- Solution URL: https://github.com/norwegJan/Testimonials-Grid-Section
- Live Site URL: https://norwegjan.github.io/Testimonials-Grid-Section/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow



### What I learned

- How to create responsive grids using grid-template-areas.
- How to create scaleable fluid typography using the clamp()-fuction.


```css
.testimonials-grid {
        margin: auto;
        display: grid; 
        grid-template-columns: 1fr 1fr 1fr 1fr;
        grid-template-rows: auto auto;
        grid-template-areas:
            "Daniel     Daniel      Jonathan       Kira"
            "Jeanette   Patrick     Patrick        Kira";   
        
        gap: 1.5rem;
        max-width: 1250px;
        }

h1 {
    font-size: clamp(2.3rem, 1.8vw + 1.5rem, 3.5rem);
    }
```


This was a challenging, but fun challenge to work on! Very satisfying when things falls into place after struggling for a while, and beging to understand how concepts works 🤓😄💪
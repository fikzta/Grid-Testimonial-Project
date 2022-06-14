# Grid-Testimonial-Project
Grid Testimonial webpage from frontend mentor
# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot Solution
![CSS Screenshot]
<img src="images/css.png" alt="CSS Solution" />
![HTML Screenshot]
<img src="images/html.png" alt="HTML Solution" />

### Links

- Solution URL: 
[HTML]
(https://github.com/fikzta/Grid-Testimonial-Project/blob/main/Frontend%20Testimonial.html)
[CSS]
(https://github.com/fikzta/Grid-Testimonial-Project/blob/main/Frontend%20Testimonial.css)

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid 

### What I learned

I started this project while watching Brad Traversy's CSS Grid crash course. It was nerve racking since wathing Brad do it with ease and efficiency made it easy for me to follow. Once I tried to do the project without looking over his tutorial was like a crutch taken away. I got stuck a few times did some research online about how to align center elements using flexbox. Specifying font sizes, colors, etc. It's really all about the mindset and consistency when it comes to finishing this project. After i completed this project, I had to compare my code to Brad's CSS and I learned that I need to make my css selector usage more efficient and cleaner since he only has to use a few selectors to style all elements in the project. I also needed to polish and get a better understanding my usage of classes and ids in order group style elements and avoid styling separately for more efficiency.

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:


```css
<h1>I'm proud of all the CSS code I implemented since I made it all work without looking over Brad's tutorial</h1>
<h2>I know i have a lot more to learn with cleanliness and efficiency. Less is more.</h2>
```
```css
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

.grid_container {
    font-size: 13px;
    font-weight: 500;
    font-family: 'Barlow Semi Condensed', sans-serif;
    max-width: 1440px;
    padding: 20px;
    display: grid;
    gap: 30px;
    grid-template-columns: repeat(4, 1fr);
}

.testimonials {
    box-shadow: 40px 60px 50px -47px rgba(72, 85, 106, 0.24378);
    border-radius: 8px; 
    padding: 30px;
    margin-bottom: 10px;
}

.student_info {
    display: flex;
    flex-direction: row;
    align-items: center;
}

.student_info h3 {
    font-weight: 600;
    color: #ffff;
    line-height: 13px;
}

.student_info p{
    font-size: 11px;
    line-height: 11px;
    opacity: 0.5;
    color: #ffff;
}

.student_lead_quote {
    font-weight: 600;
    font-size: 20px;
}

.student_lead_quote {
    color: #ffffff;
}

#patrick_lead_quote {
    color: #ecf2f8;
    font-size: 20px;
    font-weight: 600;
}

.jonathan_patrick_review_color {
    color: #ffff;
    opacity: 0.7; 
}

img {
    border:#733fc8 2px solid;
    border-radius: 50%;
}

#daniel_review {
    color: #cfcfcf;
    opacity: 0.7;
}

#daniel-profile-pic {
    border-color: #a775f1;
}

.testimonials:nth-of-type(1) {
    background-color: #733fc8;
    background-image: url(images/bg-pattern-quotation.svg);
    background-repeat: no-repeat;
    background-position: top right 5%;
    grid-column: 1 / 3;
}

.testimonials:nth-of-type(2) {
    background-color: #48556a;
}

.testimonials:nth-of-type(4) {
    background-color: #19202d;
    grid-row: 2;
    grid-column: 2 / 4;
}

/* .testimonials:nth-of-type(3){
    grid-row: 2 / 4;
} */
.testimonials:nth-of-type(3) p{
    color: #48556a;
}

.testimonials:nth-of-type(5) {
    grid-column: 4;
    grid-row: 1 / 3;
    
}

.testimonials:nth-of-type(3) h3{
    color: #48556a;
}

.testimonials:nth-of-type(3) div{
    color: #48556a;
}

.testimonials:nth-of-type(5) p{
        color: #48556a;
}
.testimonials:nth-of-type(5) h3{
    color: #48556a;
}
.testimonials:nth-of-type(5) div {
    color: #48556a;
}

footer {
    text-align: center;
}

@media (max-width: 390px) {
    .grid_container {
    grid-template-columns: 1fr;
    width: 100%;
    }

    .testimonials:nth-of-type(1) {
        grid-column: 1;
    }

    .testimonials:nth-of-type(2) {
        grid-column: 1;
        grid-row: 2;
    }

    .testimonials:nth-of-type(3) {
        grid-column: 1;
        grid-row: 3;
    }

    .testimonials:nth-of-type(4) {
        grid-column: 1;
        grid-row: 4;
    }
    .testimonials:nth-of-type(5) {
        grid-column: 1;
        grid-row: 5;
    }



}
```

### Continued development

I definitely to learn more about how to be efficient with my class, ID, element usage as selectors. Specificity in order to be more efficient with my code and make it cleaner. Less is more. Also being more comfortable with how media queries, grid, different types of selectors. That will all come with practice as i build more projects

### Useful resources

- [Inserting local screenshot img in markdown](https://stackoverflow.com/questions/42961712/how-to-include-image-as-markdown-in-visual-studio-code#:~:text=As%20the%20plugin%20suggests%20you,cmd) - This particular thread helped me insert screenshots inside my markdown
- [Brad Traversy's CSS Grid Crash Course](https://www.youtube.com/watch?v=0xMQfnTU6oo&t=1336s) - This is an amazing video by Brad which helped me finally understand CSS Grid. I'd recommend it to anyone still learning this concept.

## Author

- Github - [Kevin Paul Aguilar](https://github.com/fikzta)
- Frontend Mentor - [@fikzta](https://www.frontendmentor.io/profile/fikzta)
- Twitter - [@kevinpaula09](https://www.twitter.com/kevinpaula09)

## Acknowledgments

I just want to thank Brad Traversy for all the content he puts out on Youtube. As well as Frontend Mentor all the challenges they create for me to practice and slowly build my confidence to hopefully overcome my impostor syndrome. 

# Frontend Mentor - Social proof section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


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


### Screenshot

![desktop](https://github.com/mgkh286/four-card-feature-section-master/blob/master/images/desktop.PNG)
![Mobile](https://github.com/mgkh286/four-card-feature-section-master/blob/master/images/mobile.png)

### Links

- Solution URL: [solution URL](https://www.frontendmentor.io/solutions/fourcardfeaturesectionmaster-using-html-css-7_KfDMOya7)
- Live Site URL: [live site](https://mgkh286.github.io/four-card-feature-section-master/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Accessibility
- background properties
- position layout

### What I learned

```html
<section class="card">
            <h3>Supervisor</h3>
            <p>Monitors activity to identify project roadblocks</p>
            <div class="icon">
              <img src="./images/icon-supervisor.svg" alt="Supervisor" />
            </div>
          </section>
```

```css
.cards .card:nth-last-of-type(1) {
  border-color: var(--Blue);
}

.cards .card:nth-last-of-type(2) {
  border-color: var(--Orange);
}

.cards .card:nth-last-of-type(3) {
  border-color: var(--Red);
}

.cards .card:nth-last-of-type(4) {
  border-color: var(--Cyan);
}
```

### Continued development

i will focus on using flexbox layout in the future projects. These concepts am comfortable with and i found tit very useful .

i will focus on using relative units vh or vw it helps me to write short and clean code .

i will focus on specificity using class or id selectors .

i will focus on  using color variables  .

i will focus on  using background properties .

i will focus on  mobile first design .

### Useful resources

- [w3schools 1](https://www.w3schools.com/css/css3_flexbox.asp) - This helped me for centering elements . I really liked this pattern and will use it going forward.
- [w3schools 2](https://www.w3schools.com/cssref/css_units.asp) - This is an amazing article which helped me finally understand Relative length units . I'd recommend it to anyone still learning this concept.
- [mdn 3](https://developer.mozilla.org/en-US/docs/Web/CSS/background) - This helped me for dealing with backgroundg elements . I really liked this pattern and will use it going forward.
- [csstricks 4](https://developer.mozilla.org/en-US/docs/Web/CSS/background) - This helped me for dealing with positioning layout elements . I really liked this pattern and will use it going forward.

## Author

- Website - [Mohamed khalifa](https://github.com/mgkh286)
- Frontend Mentor - [@mgkh286](https://www.frontendmentor.io/profile/mgkh286)
- Twitter - [@mmd1790](https://twitter.com/mmd1790)



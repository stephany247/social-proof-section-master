# Frontend Mentor - Social Proof Section Solution

This is my solution to the [Social Proof Section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). I built this project to practise creating responsive layouts with HTML and CSS while improving my understanding of CSS Grid, Flexbox, and accessible markup.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The Challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size.
- See a clean and organised presentation of customer ratings and testimonials.
- Experience a layout that adapts from mobile screens to desktop screens.

### Screenshot

![Social Proof Section screenshot](./images/screencapture-desktop%20(2).png)
![Social Proof Section screenshot](./images/screencapture-mobile%20(2).png)



### Links

- **Github Repo URL:** [Github Repo URL](https://github.com/stephany247/social-proof-section-master)
- **Live Site URL:** [Live Demo](https://stephany247.github.io/social-proof-section-master/).

## My Process

### Built With

- Semantic HTML5
- CSS custom properties (variables)
- CSS Grid
- Flexbox
- Mobile-first workflow
- Responsive media queries
- Accessible markup
- Google Fonts — League Spartan

### What I Learned

One of the main things I learned from this project was how to combine CSS Grid and Flexbox effectively instead of relying on only one layout method.

I used CSS Grid to organise the main introduction, rating section, and testimonial cards. Flexbox helped align the star icons and customer information within individual components.

I also practised using CSS custom properties to keep colours consistent and make the stylesheet easier to maintain.

For example, defining reusable colour variables made it easier to apply the same colours throughout the project:

```css
:root {
  --very-dark-magenta: hsl(300, 43%, 22%);
  --soft-pink: hsl(333, 80%, 67%);
  --dark-grayish-magenta: hsl(303, 10%, 53%);
  --light-grayish-magenta: hsl(300, 24%, 96%);
  --white: hsl(0, 0%, 100%);
}
```

Another important lesson was starting with the mobile layout and progressively adjusting the design for larger screens using media queries.

### Continued Development

Going forward, I want to keep improving my skills in:

- Building more complex responsive layouts with CSS Grid and Flexbox.
- Writing cleaner, more maintainable CSS.
- Improving accessibility through semantic HTML and meaningful screen-reader text.
- Matching reference designs more accurately across different screen sizes.
- Testing layouts at different viewport widths to catch overflow and spacing issues early.

### Useful Resources

- [Frontend Mentor](https://www.frontendmentor.io/) — Provided the design challenge and an opportunity to practise building a realistic interface.
- [MDN Web Docs — CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout) — Helped me understand how to organise content into rows and columns.
- [MDN Web Docs — Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout) — Useful for aligning elements within components.
- [MDN Web Docs — Responsive Design](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Responsive_Design) — A useful reference for adapting layouts to different screen sizes.

### AI Collaboration

I used ChatGPT as a supporting tool during development to review my CSS structure, discuss layout choices, and identify potential improvements to responsiveness and accessibility.

I used the suggestions as a guide while working on the implementation, with the goal of understanding the layout techniques rather than simply copying code.

## Author

- **Frontend Mentor:** [@stephany247](https://www.frontendmentor.io/profile/stephany247)
- **GitHub:** [Github ProfileURL](https://github.com/stephany247)

# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#https://www.frontendmentor.io/challenges/blog-preview-card)
  - [Screenshot](#screenshot)
  - [Links](#oms-blog-preview-card.netlify.app)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [solution URL](oms-blog-preview-card.netlify.app)
- Live Site URL: [live site URL](https://github.com/OMS-Create/oms-blog-preview-card)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Google Fonts (Figtree)

### What I learned

Working through this project helped reinforce fundamental styling techniques for card components, specifically handling typography weights, custom shadows, and precise spacing:

```html
<div class="card">
  <div class="image">...</div>
  <div class="learning"><h5>Learning</h5></div>
  <div class="date">Published 21 Dec 2023</div>
  <header>
    <h2>HTML & CSS foundations</h2>
  </header>
  <p>These languages are the backbone of every website...</p>
</div>
```

```css
.card {
    border: 1px solid hsl(0, 0%, 7%);
    background: hsl(0, 0%, 100%);
    border-radius: 20px;
    padding: 24px;
    width: 336px;
    box-shadow: 8px 8px 0px hsl(0, 0%, 7%);
}
```

### Continued development

In future projects, I want to continue refining responsive design techniques, accessibility standards, and component reusability across different screen sizes.

### Useful resources

- [Google Fonts - Figtree](https://fonts.google.com/specimen/Figtree) - Used for clean and modern typography weights (500 and 800).
- [Frontend Mentor](https://www.frontendmentor.io) - For providing realistic design challenges and style guides.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)

## Sharing your solution

There are multiple places you can share your solution:

1. Share your solution page in the **#finished-projects** channel of our [community](https://www.frontendmentor.io/community). 
2. Share on [X (formerly Twitter)](https://x.com/frontendmentor) and mention **@frontendmentor**, including the repo and live URLs in your post. We'd love to take a look at what you've built and help share it around.
3. Share your solution on [LinkedIn](https://www.linkedin.com/company/frontend-mentor/).
4. Blog about your experience building your project. Writing about your workflow, technical choices, and talking through your code is a brilliant way to reinforce what you've learned. Great platforms to write on are [dev.to](https://dev.to/), [Hashnode](https://hashnode.com/), and [CodeNewbie](https://community.codenewbie.org/).

We provide templates to help you share your solution once you've submitted it on the platform. Please do edit them and include specific questions when you're looking for feedback. 

The more specific you are with your questions the more likely it is that another member of the community will give you feedback.

## Got feedback for us?

We love receiving feedback! We're always looking to improve our challenges and our platform. So if you have anything you'd like to mention, please email hi[at]frontendmentor[dot]io.

This challenge is completely free. Please share it with anyone who will find it useful for practice.

**Have fun building!** 🚀

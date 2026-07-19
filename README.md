# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Modifications and Improvements](#modifications-and-improvements)
- [Author](#author)

## Overview

### Screenshot

![QR Code Component Solution](./preview.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/Nick-ulrich2/QR-Code)
- Live Site URL: [Live Demo](https://qr-code-72v82es37-mvongo-nfoto-hudes-ulrich-s-projects.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Google Fonts](https://fonts.google.com/) - Outfit font family

### What I learned

While working through this challenge, I reinforced several key concepts:

1. **CSS Flexbox** - Effectively centering content both vertically and horizontally using flexbox properties
2. **Responsive Design** - Building responsive layouts that work across mobile (375px) and desktop (1440px) viewports
3. **Color Management** - Using HSL color values for better readability and maintainability
4. **CSS Best Practices** - Proper use of margins, padding, and border-radius for polished UI components

Key CSS patterns used:

```css
body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    display: flex;
    flex-direction: column;
    align-items: center;
}
```

### Continued development

Future improvements could include:

- Testing across more browsers for compatibility
- Adding hover and focus states for better interactivity
- Implementing additional responsive breakpoints for tablets
- Exploring CSS Grid for more complex layouts

### Useful resources

- [MDN Web Docs - Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) - Comprehensive guide to flexbox
- [CSS-Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Visual and practical reference
- [Frontend Mentor - Learning Paths](https://www.frontendmentor.io/learning-paths) - Structured learning resources



## Modifications and Improvements

The following CSS improvements have been implemented to refine the component's appearance and match design specifications more closely:

### CSS Changes Made:

1. **QR Code Container Sizing**
   - Changed `.qr-code` width from `100%` to `95%` for better visual balance within the container
   - Added `.qr-code` height property set to `95%` to maintain proportional dimensions

2. **Text Content Spacing**
   - Adjusted `.text-content` margin from `20px 0` to `15px 0` for tighter, more refined spacing between elements

3. **Paragraph Typography**
   - Added explicit `font-weight: 400` to the `p` selector to ensure consistent font rendering and compliance with the style guide

These changes ensure the component adheres to the design specifications outlined in the style guide while maintaining proper visual hierarchy and spacing.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- GitHub - [@yourusername](https://www.github.com/yourusername)

# Frontend Mentor - QR code component

This is a project made  to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Status: Finished.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### Screenshot

![web site screenshot](./assets/images/page-screenshot.png)

### Links

- Live Site URL: [GitHub pages](https://luizhen527.github.io/qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Atomic commits

### What I learned

I learned how to set css custom properties. How I made it in this project:

```css
:root {
    --white-clr: hsl(0, 0%, 100%);
    --slate-300: hsl(212, 45%, 89%);
    --slate-500: hsl(216, 15%, 48%);
    --slate-900: hsl(218, 44%, 22%);

    --font-size-paragraph: 15px;
}
```

The ```:root``` pseudo-class to make my variables fall in all the others elements, because of the cascade.

---

I also learned how to self-host fonts. This means that I have the font files in the project folder. To do this we need to download the fonts and compress the .ttf files of the fonts we want. I used [this site](https://transfonter.org/) to compress. After compressing, put your files in the font folder and define them on the CSS like this:

```css
@font-face {
    font-family: 'Outfit';
    font-weight: 700;
    src: url('./assets/fonts/outfit/Outfit-Bold.woff2') format('woff2'),
         url('./assets/fonts/outfit/Outfit-Bold.woff') format('woff');
}
```

I self-hosted the fonts on this project for learning. Because I was used to using the google URL.

### Continued development

These are the things I still need to get better at or study more about:

- Study more about fallback fonts;

### Useful resources

[CSS Custom Properties introduction](https://www.example.com) - This video, by Kevin Powell, helped me to undestand how css custom variables, aka css variables, are defined. This guy is amazing.

[Self host fonts tutorial](https://www.youtube.com/watch?v=zK-yy6C2Nck) - This videos teaches how to intall fonts, compress them and put on the CSS code. Great video by Kevin Powell.

[Transfonter](https://transfonter.org/) - Site used to compress fonts to woff and woff2 file extensions.
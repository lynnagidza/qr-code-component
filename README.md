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
- [Author](#author)

## Overview

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [QR code component repo](https://github.com/lynnagidza/qr-code-component)
- Live Site URL: [QR code on Vercel](https://qr-code-component-eta-gilt.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

While not new to development, I hadn't worked with web languages in a while. Who knew centering a div was still so challenging! My journey back to frontend development was mostly smooth, with a few interesting CSS lessons along the way.

## CSS Shorthand Property Insights

I had an "aha moment" when I discovered why my CSS shorthand properties weren't working. Initially, I was incorrectly using commas to separate values:

```css
.content {
  padding: 16px, 16px, 40px, 16px; /* Incorrect syntax with commas */
}
```

After some researching, I realized that CSS shorthand properties use spaces (not commas) to separate values:

```css
.content {
  padding: 16px 16px 40px 16px; /* Correct syntax: top right bottom left */
}
```

Similarly, for border properties:

```css
.qr-code {
  border: 1px solid black; /* Works perfectly without commas */
}
```

It was a simple syntax error, but finding and fixing it was quite satisfying!

## Responsive Design Insights

I initially approached the project with a desktop-first mindset until I discovered the importance of the `viewport` meta tag.

The viewport is basically the user's visible area of a web page and varies with the device the page is being viewed on. This can be implemented in HTML5 as shown below:

```html
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
</head>
```

The viewport tag gives the browser instructions on how to control the page's dimensions and scaling based on the device. You can read more about it [here](https://www.w3schools.com/css/css_rwd_viewport.asp).

### Continued development

I am excited to explore CSS further as I've seen just how powerful it can be. It's amazing how simple code can make big impact in design and UI. My goal is to eventually use frontend libraries and frameworks to create beautiful UIs and enhance user experience.

### Useful resources

- [w3schools](https://www.w3schools.com/css/) - This helped me get my footing back to CSS. It simplifies and explains concepts well.

## Author

- Website - [Lynn Agidza](https://lynnagidza.github.io/)
- Frontend Mentor - [@lynnagidza](https://www.frontendmentor.io/profile/lynnagidza)

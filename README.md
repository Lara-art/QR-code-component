# Frontend Mentor - QR code component solution

This is my solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


## Overview

### Screenshot

![mobile](https://github.com/Lara-art/QR-code-component/assets/62111495/402e7bc3-279a-4bef-b57d-62bac3fdf5ba)<br>
<i>Mobile Design</i>


![Desktop](https://github.com/Lara-art/QR-code-component/assets/62111495/ba689c62-176a-435e-8690-e13278592769)<br>
<i>Desktop Design</i>

### Links

- Solution URL: [Github](https://github.com/Lara-art/QR-code-component)
- Live Site URL: [Deployed](https://lara-art.github.io/QR-code-component/)

## My process

### Built with

- Web font import
- CSS custom properties
- Basic CSS reset
- Base typography settings
- Image styling
- Use of CSS Grid
- Use of Flexbox
- Mobile-first design


### What I learned

I am very proud of this CSS code because I was able to make it responsive for mobile without needing to use a @media query.


```css
h1 {
    font-size: clamp(2.2rem, 1.986rem + 0.571vw, 2.5rem);
}

.container {
    max-width: 1440px;
    margin: auto;
    padding: 2rem;
    display: grid;
    place-content: center;
}
```
Thanks to place-content: center, I have aligned and justified it both vertically and horizontally.

```css
.container {
    display: grid;
    place-content: center;
}
```


## Author

- Github - [Lara](https://github.com/Lara-art)
- Frontend Mentor - [@Lara-art](https://www.frontendmentor.io/profile/Lara-art)

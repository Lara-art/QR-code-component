# Frontend Mentor - QR code component solution

This is my solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). <br>Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


## Overview

### Screenshot
<table>
  <tr>
    <td style="width: 75%;"><img src="https://github.com/Lara-art/QR-code-component/blob/main/QR-Screenshoot/Desktop.PNG" alt="Vista de Escritorio" style="width: 100%;"/></td>
    <td style="width: 25%;"><img src="https://github.com/Lara-art/QR-code-component/blob/main/QR-Screenshoot/mobile.PNG"  alt="Vista Móvil" style="width: 100%;"/></td>
  </tr>
</table>

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

I’m really proud of this CSS code because I made it mobile responsive without using any @media queries.


```css
h1 {
    font-size: clamp(2.2rem, 1.986rem + 0.571vw, 2.5rem);
}

.container {
    max-width: 1440px;
    margin: auto;
    padding: 2rem;
}
```
Using place-content: center, I was able to align and justify it both vertically and horizontally.

```css
.container {
    display: grid;
    place-content: center;
}
```


## Author

- Github - [Lara](https://github.com/Lara-art)
- Frontend Mentor - [@Lara-art](https://www.frontendmentor.io/profile/Lara-art)

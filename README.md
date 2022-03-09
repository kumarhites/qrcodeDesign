# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Screenshot](#screenshot)
- [Links](#links)
- [Built with](#built-with)
### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [qrCodeQr](https://qrcodeqr.netlify.app/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Flexbox


To see how you can add code snippets, see below:

```html
<div class="container">
    <div class="card">
      <img src="./images/image-qr-code.png">
      <div class="text">
        <h2>Improve your front-end skills by building projects</h2>
        <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
      </div>
    </div>
  </div>
```
```css
:root{
    --white: hsl(0, 0%, 100%);
    --light-gray: hsl(212, 45%, 89%);
    --grayish-blue: hsl(220, 15%, 55%);
    --dark-blue: hsl(218, 44%, 22%);
}
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    background-color: var(--light-gray);
    /* this is to center the card */
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    /* this is to center the card */
}
.container{
    max-width: 360px; /* to control the size of the image(not to make the image overflow)*/
    margin: auto auto; /*to push the footer to the bottom*/
    text-align: center;
}
.card{
    background-color: var(--white);
    padding: 15px;
    border-radius: 15px;
    box-shadow: 0 0 10px rgba(0,0,0,0.3);
    margin: 0 1rem;
}
.card img{
    width:100%;
    border-radius: 15px;
}
.text{
    padding: 22px 10px;
}
.text h2{
    color: var(--dark-blue);    
    font-family: "Outfit", sans-serif;
    margin-bottom: 20px;
    
}
.text p{
    color: var(--grayish-blue);
    padding: 0px 10px;
    font-family: "Outfit", sans-serif;
}
```

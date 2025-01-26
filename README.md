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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
Below is a few details about my first frontendmentor.io project.

### Screenshot
![qr code](127.0.0.1_5500_index.html.png)
 

### Links

- Solution URL: http://127.0.0.1:5500/index.html
- Live Site URL: (https://malachifullerton.github.io/frontend_mentor_project_qrcode/)

## My process
Firstly, i edited my html and added some divs around some elements and text and i created a css file and added css code for the html. i used flexbox to put containers where i wanted them to be for proper positioning
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow



### What I learned

1) I re-learnt how to  create a repo on github and clone it on the mchine locally and push it back

2) I also learnt how to make my website live on a github

3) i learnt how to make a files body and html expand the full height of a page. Below is how to do it

```css
html, 
body {
  height: 100%;
}
```

4) i learnt how to use a font directly from google fonts in my css without downloading it to my pc... to do this you have to get the html code for the document and paste it in the html file in the header on top of the css link so it loads before the css does. Next y get the css code and paste in the css file where you want it applied to.

5) i learnt it is best practice to apply the below code to the css file to ensure proper height and width application without making your element bigger than you want it:
```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
``` 

6) i learnt just some basics of responsive design i.e media queries. i learnt in the code there are 4 media keywords which can written after the 
```css
 @media 
 ``` 
 you can input "screen" which is for desktops, phones and tablets and "print" for print media when you want to maybe print the page, "speech" for scrren readers and "all" which covers all the above media keywords.
 
 NB: you can also chooose not to write any keyword which auomatically means all keywords.

 also with the media queries they should ideally be the last thing in your css code.
 
 A full media query looks like this 
 ```css
 @media (max-width: 400px){
  /* code to be written */
 }
 ```  
 with what is in the brackets it can either be max-width or min-width which max-width stands for screens at the given size like say 400px and below and the min-width is vice versa


### Continued development
1) i want to know more of media queries


### Useful resources

- [resource 1](https://www.youtube.com/watch?v=lkDrG7G77Fg) - This helped me with using new fonts in css. I really liked the pattern .
- [ resource 2](https://www.youtube.com/watch?v=P_vkS4UJNDk) - This is an amazing article which helped me  understand the basics of css media queries. I'd recommend it to anyone still learning this concept.


## Author

- Website - [Malachi Fullerton](https://www.your-site.com)
- Frontend Mentor - [@Malachifullerton](https://www.frontendmentor.io/profile/Malachifullerton)
- Twitter - [@malachifullert1](https://x.com/malachifullert1)



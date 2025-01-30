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

 7) I have also learnt about accessibility (this is mainly for disabled people and also benefits abled people) of web pages and gone through a few of the WCAG which stands for web content acessibilty guidlines. There are 4 main principles which are abbreviated POUR: 
 
 Percievable: eg is content should be able to be seen easily... like a text should be on abackgroung that makes it readable.

 Opearable: eg is websites should not only be operable or navigatable by mouse but also keyboard so people who for example cant see the mouse cursor will be able to navigate the website through the keyboard and screen reader.

 Understandable: eg is a website should not bee to complex for a user to understand what is going on... like a when a user inputs a wrong email and password and a feedback of "#Error 2219" is given it will be difficult for  the user to understand what is going on. To make it   more understandable a feedback of "wrong email or password" is more understandable by the user.

 Robust: means your website should work well with today's assistive tools (like screen readers) and still work in the future as technology improves. Basically, build it in a way that won't break when new browsers or accessibility tools come out.

 Under accessibility i also learnt HTML landmarks and ARIA landmarks which basically helps assistive technology like screen Readers to help disabled people navigate pages 
 The most preferred and widly used is HTML land marks but ARIA landmarks can also be used in place of the latter.

 HTML landmarks:
 ```html
 <header>
  <!-- as the name goes it is for the introductory content of a webpage and it can be used multiple times -->
 </header>

<nav>
  <!-- used for navigation section of a website. can be repeated in like in the header, footer or even the side bar  -->
</nav>

 <main>
  <!-- used for the main content of the page. cannot be repeated -->
 </main>

<footer>
  <!-- used for footer content like copyright info, terms of service, etc -->
</footer>

<section> 
  <!-- used for a section of content -->
</section>

<form>
  <!-- used for forms -->
</form>

<table> 
  <!-- used for tables -->
</table>

<figure>
  <!-- used for media like images, charts or diagrams... usually used along side <figcaption> which describes the media in words this is how they looks put together:
    <figure>
      <img src >
      <figcaption>a text describing the above image</figcaption>
    </figure>
    . can be repeated many times -->
</figure>

<figcaption>
<!-- check <figure> -->
</figcaption>

<aside>
  <!-- used for extra information that is related to the main content but not the main focus. Think of it like a sidebar or extra notes on a webpage.  -->
</aside>

<address>
  <!-- used for addresses, phone number, email address, etc -->
</address>

<article>
  <!-- used for blogs, news story, product listing... more of like a self contained piece of content -->
</article>

<mark>
  <!-- used to make emphasis on something -->
</mark>

```

Some ARIA landmarks:
```html


NB: used in place of HTML landmarks

role ="navigation"  this is for <nav>
role="main"   this is for  <main>
role="banner"  this is for  <header>          
role="complementary"  this is for <aside>
role="contentinfo"   this is for <footer>
role="form"  this is for <form>
role="region"  this is for <section>

 ```
 I dont fully understand the ARIA landmarks yet

### Continued development
1) I want to know more of media queries
2) I dont fully understand the ARIA landmarks yet

### Useful resources

- [resource 1](https://www.youtube.com/watch?v=lkDrG7G77Fg) - This helped me with using new fonts in css. I really liked the pattern .
- [ resource 2](https://www.youtube.com/watch?v=P_vkS4UJNDk) - This is an amazing article which helped me  understand the basics of css media queries. I'd recommend it to anyone still learning this concept.


## Author

- Website - [Malachi Fullerton](https://www.your-site.com)
- Frontend Mentor - [@Malachifullerton](https://www.frontendmentor.io/profile/Malachifullerton)
- Twitter - [@malachifullert1](https://x.com/malachifullert1)



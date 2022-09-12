# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow
- SASS
- BEM

### What I learned

This project helped me to be more comfortable in writing SASS files and to continue to use git in my workflow.

This project also made me use a lot more `calc()` function in my CSS files for computed sizes or responsive size.
For example:

```css
.progress {
  height: calc(1rem - 2px);
  width: 81.5%;
  background: linear-gradient(to right, $salmon, $fuschia);
  border-radius: calc(1rem - 2px);
  position: relative;
}
.thumb {
  position: absolute;
  background-color: white;
  border-radius: 50%;
  right: 2px;
  top: 1px;
  z-index: 1;
  height: calc(1rem - 4px);
  width: calc(1rem - 4px);
  cursor: pointer;
}
```

Since I started to use 1rem as the height of the progress bar, I needed to deduct the amount of padding for the children elements.
Instead of using fixed values, I just used `calc()` function to figure out the size of the children elements, since rem is a relative value and pixels are fixed value it is harder to convert from one to another.

### Continued development

I will continue to practice on using automation tools such as Sass and browser sync in developing websites. Next time I'll try using gulp.
I'll also continue on practicing responsive design. Applying them and creating more responsive websites.

### Useful resources

- [How to make a progress bar](https://css-tricks.com/css3-progress-bars/) - Resource I used to learn more about making progress bars

## Author

- Frontend Mentor - [@jayrnoel](https://www.frontendmentor.io/profile/jayrnoel)

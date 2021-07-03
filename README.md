# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

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
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.proud-of-this-css {
  color: papayawhip;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**















Data from previos project








# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshots

![Phone screen size view](images/resultPhone.JPG)
![Desktop screen size view](images/resultDesktop.JPG)


### Links

- Solution URL: [GitHub Project](https://github.com/candelarioavalos/FEMentor01)
- Live Site URL: [GitHub Pages](https://candelarioavalos.github.io/FEMentor01/html/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Google fonts](https://fonts.google.com/)

### What I learned

First of all, I read all the guides and recomendations for this task and tried to follow them.

While I was thinking on how to add the fonts I had to use for this task, I started downloading the fonts, but then I thought that it was going to be loading folders in my computer and GitHub that I didn't need to, so, I decided then just to link the fonts with:

```html
<link href='https://fonts.googleapis.com/css?family=Inter' rel='stylesheet'>
```

I thought that it was a good idea to have one css file for general settings and one more for each different view that I was going to work with, so I wrote one css for general styles, one for mobile version and one more for desktop version, and it worked just great.
Also, I decided to set the break point for views to 1350 pixels, so, phone version for max-width: 1349px and desktop version for min-width: 1350px.

At first, I had some problem to set the appropriate image depending on the screen size view, but then I decided to use a picture element because it allows me to set the corresponding image for each screen size I set.

The rest for html was just think how to name id's and classes for the elements to style them with css.

While coding the general css stiles file, I decided to create and use variable names for colors, that way I could easily choose the corresponding colors for fonts, backgrounds, etc.

For margins and paddings, I had to resize the view of the design images to decide how many pixels I was going to set for each of this elements and how to set them in order to set the apropriate spaces acording to the design images.

The visual effect of the image, I thought that there was a special effect setting that I had to use, but then after playing a while with the transparency, I saw that I could fix that just by setting the apropriate backgroung color for the image, the problem here is still that I don't know the exact color for the image background, nor the settings for opacity, brightness etc. needed to get a better image visual effect. 


### Continued development

I found so interesting the fact that I could give a better visual effect to an image, that was my headache for a while, but after I learned how to work with it, I want to do that again in some of the next projects.

### Useful resources

- [w3schools.com](https://www.w3schools.com/) - This is the page where I have learned the most, they have a lot of easy to learn tutorials for web development and a lot of examples for every topic and language. I will keep studying at w3schools for a while, it is so exciting! Every time I need to see a code example, I search here first!

- [stackoverflow.com](https://stackoverflow.com/) - This is definitely a must while coding, I google everything I have a question abut all the time, and stackoverflow is always one of the options with the possible answer. For example, the image div was getting higher than the image itself, and it didn't look nice, I googled for a tip, and I found in stackoverflow that the best way to avoid that, was to set the display property for the image as block, and that really helped me fixing the problem, I know it is something easy and basic, but really a headache for a beginner!

## Author

- GitHub - [Candelario Avalos Contreras](https://github.com/candelarioavalos)
- Frontend Mentor - [Candelario Avalos Contreras](https://www.frontendmentor.io/profile/candelarioavalos)
- Facebook - [Candelario Avalos Contreras](https://www.facebook.com/candelario.avaloscontreras/)
- LinkedIn - [Candelario Avalos Contreras](https://www.linkedin.com/in/candelario-avalos-4a575b1b9/)


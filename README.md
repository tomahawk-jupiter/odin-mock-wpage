# Mock webpage for Odin project

An assignment done as part of the [Odin Project Course](https://www.theodinproject.com/).

In this project I will make a webpage based on a [picture example](https://cdn.statically.io/gh/TheOdinProject/curriculum/main/foundations/html_css/project/odin-project.png). I have been given some [colors and font styles](https://cdn.statically.io/gh/TheOdinProject/curriculum/main/foundations/html_css/project/colors_and_stuff.png) to help.

## Contents

- [Skills I will practice](#skills-i-will-practice)
- [The Plan](#the-plan)
- [Things I Learnt](#things-i-learnt)

## Skills I will practice

HTML, CSS, Flexbox, Markdown (For these notes), Git and GitHub.

## The Plan

The picture shows a header, four main sections containing multiple elements each and a footer.

I will focus on one section at a time, doing the html then the css. (I added extra html containers while doing the layout).

I will use flexbox to achieve the desired layout then add margin and padding to touch it up.

I will use flex-direction: column; to then stack these sections together. (Actually It will stack by default so this wasn't needed).

I have been given some links to use for finding free pictures to use:
[pexels](https://www.pexels.com/), [pixabay](https://pixabay.com/), [Unsplash](https://unsplash.com/).

## Things I learnt

### CSS variables

Set and Use (they must be defined with scope where they'll be used):

```
:root {
  --main-color: black;
}
.div {
  color: var(--main-color);
}
```

### Select all within a container

The below example is useful for seeing all elements boundaries:

    .class-name * {
      border: solid red 2px;
    }

### Layout Tip:

Put a different color border around each container / element to make it easier to tell them apart when arranging them.

### Border radius:

border-radius creates curved corners. It can take upto 4 values (like with margin), one for each corner.

    border-radius: 20px;

### Placeholder images

[placeholder.com](https://placeholder.com/)

Specify width and height and optionally specify file type at the end, default is .GIF:

https[]()://via.placeholder.com/300x200

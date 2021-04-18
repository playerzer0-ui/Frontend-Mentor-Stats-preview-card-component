# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview
My very first challenge which shows a card with certain info (mobile not supported since I haven't learn it yet)

### The challenge

View the card on screen

### Screenshot

![image](https://user-images.githubusercontent.com/73352315/115143895-a8307b00-a041-11eb-8931-e56ec3a9b912.png) 

### Links

- Solution URL: https://github.com/playerzer0-ui/Frontend-Mentor-Stats-preview-card-component
- Live Site URL: https://playerzer0-ui.github.io/Frontend-Mentor-Stats-preview-card-component/

## My process

lots of thinking (especially on that overlay)

### Built with

-html
-css

### What I learned

/*set image to be rounded on 2 corners and move to the right*/
.image-desktop {
    height: 340px;
    width: 413px;
    border-radius: 0 10px 10px 0;
    position: absolute;
    opacity: 30%;
    z-index: -1;
}

/*the body card itself*/
.container {
    background-color: #1f1238;
    margin: 160px auto;
    width: 840px;
    height: 340px;
    border-radius: 10px;
}

/*the overlay*/
.opacitifier {
    float: right;
    background-color: hsl(277, 100%, 37%);
    border-radius: 0 10px 10px 0;
    height: 340px;
    width: 413px;
    opacity: 99%;
    position: relative;
}

What you see here is responsible for creating that body card, the image set with rounded corners and an overlay disguised as a div (though not perfect, it still looks new to me)

### Continued development

make responsive websites (someday) as well as learn more design features.

### Useful resources

helps me to identify what colors are in the preview challlenge
color picker: https://imagecolorpicker.com/en

## Author

player_zero
amateur coder and new to digital art

pinterest: www.pinterest.com/Nexus_Enchant

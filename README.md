# Preview-Card
This is a Front-end Mentor Challenge
# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [github.com](https://mariamokann.github.io/miniature-funicular/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### Continued development

In Future Projects, I'll like to focus on other aspects of css {Tailwind CSS} and also, improve my use of Bootstrap.

## Author

- Website - Mariam Okanlawon
- Frontend Mentor - [@MariamOkann](https://www.frontendmentor.io/profile/MariamOkann)
- Twitter - [@mariam_okan](https://www.twitter.com/mariam_okan)


## Acknowledgments

I'll like to thank Front-end Mentor for giving me the opportunity to display my knowledge on this challenge.


# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

Bright orange: hsl(31, 77%, 52%)
Dark cyan: hsl(184, 100%, 22%)
Very dark cyan: hsl(179, 100%, 13%)

### Neutral

Transparent white (paragraphs): hsla(0, 0%, 100%, 0.75)
Very light gray (background, headings, buttons): hsl(0, 0%, 95%)

## Typography

### Body Copy

- Font size: 15px

### Font

- Family: [Lexend Deca](https://fonts.google.com/specimen/Lexend+Deca)
- Weights: 400

- Family: [Big Shoulders Display](https://fonts.google.com/specimen/Big+Shoulders+Display)
- Weights: 700

CODE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Preview Card</title>
    <link rel="icon" type="image/x-icon" href="favicon1.ico">
    <style>
        .cards{display: flex;
    margin: 150px 200px;
}
      .sedans{background-color:hsl(31, 77%, 52%);
              color:white;
              padding: 50px;
              border-top-left-radius:10px;
              border-bottom-left-radius: 10px;
              font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
      .suvs{background-color:hsl(184, 100%, 22%);
          color:white;
          padding: 50px;
          font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
     .luxury{background-color:hsl(179, 100%, 13%);
            color:white;
            padding: 50px;
            border-top-right-radius: 10px;
            border-bottom-right-radius: 10px;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;;
}
p{font-family: 'Lexend Deca', sans-serif;
font-size: 14px;
color:hsla(0, 0%, 100%, 0.75);
word-spacing: 4px;
width: 200px;
height: 190px;
line-height: 1.5;
}
button{background-color: white;
    width: 150px;
    height: 50px;
    border-radius: 25px;
    border: 1px solid white;
}
.learn{text-decoration: none;
    font-size: 13px;
}
footer{
 text-align: center;
 color:(179, 100%, 13%);
}
a{
 text-decoration: none;
 color:hsl(184, 100%, 22%);
}
    </style>
</head>
<body>
    <div class="cards">
        <div class="sedans">
            <img src="icon_sedans.svg" style="width: 61px;">
            <h1>SEDANS</h1>
            <p>Choose a sedan for its affordability and its excellent fuel economy. Ideal for cruising in the city or on your next road trip.</p>
            <button><a href="frontendmentor.io" class="learn" style="color: orange;">Learn More</a></button>
        </div>
        <div class="suvs"> 
            <img src="icon_suvs.svg" style="width: 61px;">
            <h1>SUVS</h1>
            <p>
            Take an SUV for its spacious<br> interior, power and<br> versatility. Perfect for your<br> next family vacation and off-road adventures.
            </p>
            <button><a href="frontendmentor.io" class="learn" style="color: teal;">Learn More</a></button>
        </div>
        <div class="luxury">
            <img src="iconluxury.svg" style="width: 61px;">
            <h1>LUXURY</h1>
            <p>
            Cruise in the best car brands<br> without the bloated prices.<br> Enjoy the enhanced comfort <br>of a luxury rental and arrive<br>in style.
            </p>
            <button><a href="frontendmentor.io" class="learn" style="color:rgb(17, 95, 95)">Learn More</a></button>
        </div>
    </div>
    <footer>
        Challenge by <a href="frontendmentor.io">Frontendmentor.io</a> Coded by MariamOkan
    </footer>
</body>
</html>

# css-grid
it's a simple modifiable grid for websites


I have this CSS grid in "two" sections

The first section is .squares where you can modify any of atributes you want, add a background color etc.

the next one is the .img tag, there are multiples for each row, this can call for a css image and place it.

If you just want the grid and don't want to place the images, just remove the img atribute in the div tag. eg:

<div class="square img_2-3">
    ayy an image
</div>

to

div class="square"
ayy i made a square
/div


If you want to modify atributes but keep the old css, just copy and paste the css with a new name eg:

.square {

    float:left;

    position: relative;

    z-index:-999999;

    width: 30%;

    padding-bottom : 30%;

    margin:1.66%;

    background-position:center center;

    background-repeat:no-repeat;

    background-size:contain;

}


to

.square_portfolio {

    float:left;

    position: relative;

    z-index:-999999;

    width: 30%;

    padding-bottom : 30%;

    margin:1.66%;

    background-position:center center;

    background-repeat:no-repeat;

    background-size:contain;

    background-color:#33b5e5;

}



If you want to see the code in action, please visit the portfolio section of my website @ chris-a.rocks/projects.php

Thanks for checking this little project out

-Chris

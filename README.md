<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Level 5</title>
    <link rel="stylesheet" href="style.css">
    <style>
        div{
    border: 5px solid black;
    background-color: aquamarine;
    height: 100px;
    width: 100px;
    border-radius: 50%;
    position: absolute;
    top: 100px;
    left: 100px;
    /* transition-property: all;
    transition-duration: 2s;
    transition-timing-function: ease-in; */
    /* transition: all 5s ease-in-out; */
    animation-name: ColorAnimate;
    animation-duration: 0.25s;
    animation-timing-function: ease-in;
    animation-delay: 0s;
    animation-iteration-count: infinite;
}

@keyframes ColorAnimate {
    from {background-color: aquamarine;}
    to {background-color:darkorange;}
}

/* div:hover {
    background-color: cadetblue;
    transform: rotate(360deg);
    transform: scale(2);
    transform: translate(50px,65px);
    transform: skew(18000deg);
} */

/* div:active{
    background-color: darkgray;
    color: blue;
} */


    </style>
</head>
<body>
    <div>
       
    </div>
</body>
</html>

# Rad-Wallpaper-HTML-CSS
A wallpaper I made with HTML and CSS

## Structure:

```html
<!DOCTYPE html>
<head>
    <title>RAD!</title>
    <link rel="stylesheet" href="Retro.css">
</head>
<html>
<div id="Canvas">

    <div id="A">
        A
    </div>

    <div id="T">
        T
    </div>

    <div id="Sun"></div>

    <div id="Shade"></div>

    <div id="Plain"></div>

</div>
</html>
```

## Styling:

```CSS
html{
    background: -webkit-radial-gradient(circle, blue 50%, black 100%);
    height: 100%;
}

#A{
    margin: none;
    font-size: 200px;
    font-family: Arial, Helvetica, sans-serif;
    text-align: center;
    color: rgba(255, 255, 255, 0.8);
    position: absolute;
    top: 150px;
    left: 20%;
    z-index: 4;
}

#T{
    margin: none;
    font-size: 200px;
    font-family: Arial, Helvetica, sans-serif;
    text-align: center;
    color: rgba(255, 255, 255, 0.8);
    position: absolute;
    top: 150px;
    right: 20%;
    z-index: 4;
}

#Canvas{
    border-style: solid;
    border-color:rgba(0, 0, 0, 0);
    height: 600px;
    width: 1300px;
    margin: auto;
    position: absolute;
    z-index: -1;
    perspective: 500px;
    perspective-origin: bottom;
}

#Sun{
    border-style: none;
    border-radius: 50%;
    width: 25%;
    height: 50%;
    margin: auto;
    background: -webkit-linear-gradient(bottom, rgb(255, 102, 0), yellow);
    position: absolute;
    top: 25%;
    left: 37.5%;
    z-index: 3;

}

#Shade{
    border-style: none;
    border-radius: 50%;
    width: 25%;
    height: 50%;
    margin: auto;
    background: -webkit-linear-gradient(top, blue, rgb(0, 183, 255));
    box-shadow: 0 0 0px 0px rgb(0, 183, 255);
    position: absolute;
    top: 50%;
    left: 37.5%;
    z-index: 2;
    transform: rotateX(50deg);

}

#Plain{
    border-style: none;
    width: 50%;
    height: 500px;
    margin: auto;
    margin-bottom: none;
    background-color: rgb(255, 41, 158);
    box-shadow: 0px 40px 0px -20px rgb(0, 183, 255);
    position: absolute;
    top: 40%;
    left: 25%;
    bottom: 0%;
    z-index: 1;
    transform: rotateX(50deg);
}
```

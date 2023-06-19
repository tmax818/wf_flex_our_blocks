# wf_flex_our_blocks

## solution branch

>Try to duplicate the image below by adjusting the CSS code provided. Use `margin` and `padding` to adjust the spaces between divisions and use `display: flex;` to be able to put each block in its proper place.

![](position-blocks.png)

starter HTML:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Position Practice</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
    <div class="container">
        <div class="top-nav"></div>
        <div class="row">
            <div class="side-nav"></div>
            <div class="main">
                <div class="row">
                    <div class="sub-content"></div>
                    <div class="sub-content"></div>
                    <div class="sub-content"></div>
                </div>
                <div id="advertisement"></div>
            </div>
        </div>
    </div>
</body>
</html>
```
Starter CSS:

```css
.container{
    width: 950px;
    background-color: silver;
    margin: 0px auto;
}
.top-nav {
    height: 150px;
    background-color: green;
}
.side-nav {
    height: 300px;
    width: 200px;
    background-color: blue;
}
.main {
    height: 400px;
    width: 700px;
    background-color: red;
}
.sub-content {
    height: 200px;
    width: 210px;
    background-color: yellow;
}
#advertisement {
    height: 120px;
    width: 660px;
    background-color: purple;
}
.row {
    /* TODO - what should go here? */
}


```
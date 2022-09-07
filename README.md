# Pro Code Production Documentation

|                           Topics                           |                     Subcategories                    |
|------------------------------------------------------------|------------------------------------------------------|
|  [Style Rules](#html-style-web-page-rules)                 |  [Site Colors](#the-website-colors)                  |
|  [HTML Template](#html-template)                           |  [Style Rules](#use-the-following-rules-for-styling) |
|  [Resources](#resources)                                   |  [Banner Element](#banner)                           |
|                                                            |  [Navbar Element](#navigation)                       |
|                                                            |  [Card Element](#cards)                              |
|                                                            |  [Individual Card Elements](#individual-card-elements)|

## HTML Style Web Page Rules
### The Website Colors

Black: "black" Red: "red" Sky Blue: "#2eafff" Limegreen: "#00eb00" White: "white"

### Use The Following Rules For Styling 

> For Red Colored Text Use
```
<span style="color: red;">Text To Color</span>
```

> For Sky Blue Colored Text Use
```
<span style="color: #2eafff;">Text To Color</span>
```

> 

> For Hyperlinks
```
<a href="link">Link</a>
```

> For Footers
```
<div class="footer">
  
</div>
```

> For Subtitle Elements
```
<h3 class="Subtitle" style="text-align: center; padding-bottom: 10px; padding-top: 20px;">
  Subtitle Text
</h3>
```

> For Summary Elements
```
<p class="Summary">
  Lorem ipsum dolor sit amet, 
  consectetur adipiscing elit. 
  Fusce sed mollis lectus. 
  Nunc pretium eleifend mauris, 
  accumsan vestibulum libero interdum.
</p>
```

#### Banner
```
<div class="banner">
  <h1 class="Title">Banner Title</h1>
  <img class="banner-img" src="link-to-banner-image">
</div>
```

#### Navigation

> For Navigation Bar At Root Level
```
<nav class="nav">
  <a href="index.html" class="nav-link">
    Home
  </a>
  <a href="members.html" class="nav-link">
    Members
  </a>
  <a href="projects.html" class="nav-link">
    Projects
  </a>
</nav>
```

> For Navigation Bar At Sublevel And Personal Html Page Directory
```
<nav class="nav">
  <a href="../index.html" class="nav-link">
    Home
  </a>
  <a href="../members.html" class="nav-link">
    Members
  </a>
  <a href="../projects.html" class="nav-link">
    Projects
  </a>
</nav>
```

#### Cards
> Member List Cards
```
<div class="card">
  <a href="members/yourhtmlpage.html" style="diplay: block; width: 100%;">
    <img class="card-img" src="link-to-your-image" />
    <div class="card-title">Card Title</div>
    <div class="card-item">
      Card Item
    </div>
  </a>
</div>
```
##### Individual Card Elements
> Card Shell
```
<div class="card">

</div>
```
> Card Image
```
<img class="card-img" src="link-to-your-image"/>
```
> Card Title
```
<div class="card-title">Card Title</div>
```
> Card Item
```
<div class="card-item">Card Item</div>
```

## HTML Template
> When creating your html file copy (Ctrl+C) and paste (Ctrl+V) this template
```
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="icon" href="../images/favicon.ico">
  <link href="../style.css" rel="stylesheet" type="text/css" />
  <title>Pro-Code <Put Your Name Here></title>
</head>

<body>
  <nav class="nav">
    <a href="../index.html" class="nav-link">
      Home
    </a>
    <a href="../members.html" class="nav-link">
      Members
    </a>
    <a href="../projects.html" class="nav-link">
      Projects
    </a>
  </nav>

  <div>
    <h1><Put Your Name Here></h1>
  </div>
</body>

</html>
```
 
## Resources
1. [W3Schools](https://www.w3schools.com)
2. [Free Code Camp](https://www.freecodecamp.org)
3. [MDN](https://developer.mozilla.org)
4. [Stack Overflow](https://stackoverflow.com)

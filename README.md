# Pro Code Production Documentation

|                           Topics                           |                     Subcategories                    |
|------------------------------------------------------------|------------------------------------------------------|
|  [Assigned Pages](#here-are-the-following-assigned-pages)  |  [Site Colors](#the-website-colors)                  |
|  [Style Rules](#html-style-web-page-rules)                 |  [Style Rules](#use-the-following-rules-for-styling) |
|  [Scripts](#scripts)                                       |  [Banner Element](#banner)                           |
|                                                            |  [Navbar Element](#navigation)                       |
|                                                            |  [Card Element](#cards)                              |
|                                                            |  [Individual Card Elements](#individual-card-elements)|

## Here are the following Assigned Pages

| Jordan Wallace | Andrew Zheng | Rafael Munguia | Antoine Penagunda | Oliver Szczepanski |
| -------------- | ------------ | -------------- | ----------------- | ------------------ |
| Index Page     | Andrew.html  | Rafael.html    | Antoine.html      | Oliver.html        |
| Projects Page  |
| Members Page   |
| Who Are We?    |
| What We Do     |
| Jordan.html    |

## HTML Style Web Page Rules
### The Website Colors

Black: "black" Red: "red" Sky Blue: "#2eafff" Limegreen: "#00eb00"

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

## Scripts
|   HTML   |   CSS   |
|----------|---------|
|  index   |  styles |
|  members |
| projects |
|  Jordan  |

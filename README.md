# bulma-css-burger
Toggleable hamburger menu for bulma (CSS only - no JavaScript required).

# How to use
Get the CSS file and link it:
```html
<link rel="stylesheet" href="css/bulma-css-burger.css">
```

Then, to make the navbar, you'll just need to create a checkbox input and a label:

```html


<!-- Navbar. -->
<nav class="navbar" aria-label="main navigation">
  <div class="container">
    
    <!-- Brand. -->
    <div class="navbar-brand">
      <a class="navbar-item" href="#">
      BRAND
      </a>
    </div>
    
    <!--
     #navbarMenu[navbar-toggle]
     This is the navbar menu.
    -->
    <input type="checkbox" id="navbar-burger-toggle" class="navbar-burger-toggle is-hidden">
    <label for="navbar-burger-toggle" class="navbar-burger">
      <span></span>
      <span></span>
      <span></span>
    </label>
    
    <!-- Menu. -->
    <div class="navbar-menu">
      <div class="navbar-start">
        <a class="navbar-item">Menu Item</a>
      </div>
    </div>
  </div>
</nav>
```

# Featherweight CSS Library
This is a lightweight css library to style basic components on a web page.

## Features
Here are the current features of the Featherweight css library.

### Header
To use the header, simply use the `header` html tag. Add a class that defines the color, background image, or whether or not it should parallax.

`header-logo` is a style that you can use to show text prominently as a logo would display.

```html
<header class="bg-header">
  <section ><a href="#" class="header-logo logo-color">Exceedingly Awesome Sauce!</a></section>
</header>
```

### Nav Bar

The Organization expected for a nav bar is as follows.

```html
  <nav class="navbar sticky">

    <ul class="nav-title">
      <li><a href="http://Some Site.com"><h1>TITLE</h1></a></li>
    </ul>
    <section class="nav-section" >
      <ul>
        <li>
          <a href="https://jaytria.com">Link One</a>
        </li>
        <li>
          <a href="https://jaytria.com">Link Two</a>
        </li>
        <li>
          <a href="https://jaytria.com">Link Three</a>
        </li>
      </ul>
    </section>

</nav>
```

The sticky class is optional if you don't want to have sticky functionality.

### Hamburger Menu
You can add a hamburger menu simply by using this template.

```html
<section class="hamburger-menu bg-hamburger-menu">
  <div class="hamburger-menu-icon">&equiv;</div>
  <div class="hamburger-menu-dropdown bg-hamburger-menu-color" >
    <ul>
      <li><a href="http://xkcd.greatness.co.uk">Item one</a></li>
      <li><a href="http://jaytria.com">Item one</a></li>
    </ul>
  </div>
</section>
```
### Messages
There's your regular old message.

```html
<div id="a" class="alert">Hello! Do you have a moment to talk about out lord and savior Poseidon, God of the sea?
  <span class="close-box">x</span>
</div>
```

Here's how to create a message that should elicit a certain amount of hesitation.

```html
<div class="alert warning">Warning: Pay heed to this message or you may find yourself in an unfortunate circumstance.
    <span class="close-box">x</span>
</div>
```

Here's how to create a message that will inspire fear and possibly dread.

```html
<div class="alert error">Error: Scary things are happening right now.
    <span class="close-box">x</span>
</div>
```

### Content Hero Blocks
Show off content more prominently with enhanced styling.

```html
<section class="hero-block">
  <h2>This is some more fantastic content</h2>
  <p>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
  </p>
</section>
```

Add a background to the block by including a class that specifies the background or even add parallax.

```html
<section class="hero-block my-custom-background parallax">
  <h2>This is some more fantastic content</h2>
  <p>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
  </p>
</section>
```

The `parallax` class will add a parallax effect to the background image that is set on the element.

### Table
Just create a regular old table and it will be styled. If you want a hover effect. Make sure that whichever thing it is you want to have that effect has the class 'hover' on it.

```html
<table>
  <tr><th>col one</th><th>col two</th><th>col three</th></tr>
  <tr><td class="hover">one</td><td>two</td><td>three</td></tr>
  <tr><td class="hover">four</td> <td>five</td><td>six</td></tr>
  <tr class="hover"><td>seven</td> <td>eight</td><td>nein</td></tr>
</table>
```

### Popover
```html
<section class="panel-overlay hide">
  <div class="panel-overlay-content">
    This is where your content for the panel overlay goes.

  </div>
</section>
```

### Footer

This is a basic sample for how to buile a footer.
Each block with the class of `col` will center themselves in a row in the footer. Additionally a sub-footer is available for an additional area for content.

```
  <footer>
    <section class="col">
      <span class="footer-title">
        <a href="http://google.com"><h2>Title One</h2></a>
      </span>
      <ul>
        <li>
        <a href="http://google.com">Title One</a>
        </li>
        <li>
            <a href="http://google.com">Link Two</a>
        </li>      
        <li>
            <a href="http://google.com">Link Three</a>
        </li>
      </ul>
    </section>

    <section class="col">
        <span class="footer-title">
          <a href="http://jkjoogle.com"><h2>Title One</h2></a>
        </span>
        <ul>
          <li>
            <a href="http://xazabbad.com">Link One</a>
          </li>
          <li>
              <a href="http://xyzabc.com">Link Two</a>
          </li>      
          <li>
              <a href="http://google.com">Link Three</a>
          </li>
        </ul>
      </section>

      <section class="col">
          <span class="footer-title">
            <h2>Title One</h2>
          </span>
          <ul>
            <li>
              <a href="http://google.com">Link One</a>
            </li>
            <li>
                <a href="http://google.com">Link Two</a>
            </li>      
            <li>
                <a href="http://google.com">Link Three</a>
            </li>
          </ul>
        </section>
  </footer>
```

### Sub Footer

```
  <section class="sub-footer">
        <h2>Title One</h2>
        <ul>
          <li>
            <a href="http://google.com">Link One</a>
          </li>
          <li>
              <a href="http://google.com">Link Two</a>
          </li>      
          <li>
              <a href="http://google.com">Link Three</a>
          </li>
        </ul>
  </section>
```

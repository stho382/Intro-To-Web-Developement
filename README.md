- box model (margin, padding, element)
- element size (px, em, rem, vw, vh)
- layout (grid and flexbox)
	- justify-content, align-items, grid-template-columns (positioning)
- include good reference

# CSS
## Basic concepts

### Box model

### Layout
**Positioning**:

### Size

## How to use CSS
CSS is a langauage that styles the HTML page. In the presentation, we included CSS in `index.html` and `quotes.html` using the `<link>` tag to reference the `styles.css`file (**linked css**). Then we apply styles to our elements using class selectors like so:
```
<nav class="navbar">...</nav>
```

However, there are 2 other common ways to include CSS in the html page. Firstly, using **inline style**:
```html
<p style="text-align: center; font-size: 36px">Big centered text</p>
```
Normally, this is considered **bad practice** in HTML and CSS because it hinders readability. Secondly, we can use the `<style>` tag (**embedded css**), e.g.
```html
<html>
  <head>
    <style>
      .big_center_text {
        text-align: center;
	    font-size: 36px;
	  }
    </style>
  <head>
  <body>
    <p class="big_centered_text">Big centered text</p>
  </body>
</html>
```
The above 2 examples produce the same result, that is, to center the paragraph, and change its `font-size` to `36px`. This is better than inline styles, but writing CSS in a `.css` file offers the best readability. See more ways to include CSS in HTML [here](https://ryanstutorials.net/css-tutorial/css-including.php).

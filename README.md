# CSS Palettes
The goal of this repository is to establish a collection of standardized css color templates.

## Usage Example
```css
/* Add refernce to stylesheet in your css file. */
@import url("http://cdn.css.com/facebook.css");

/* use in your css definitions */
.nav {
  background-color: var(--facebook);
}
```

## Template Example
```css
/* Facebook, facebook.com */
:root {
  --facebook: #3B5898;
  --facebook-font: #FFF;
  
  --facebook-snd: #E9EBEE;
  --facebook-snd-font: #000;
  --facebook-snd-font-snd: #90949C;
  
  --facebook-btn: #4267B2;
  --facebook-btn-font: #FFF;
  
  --facebook-a: #365899;
}
```

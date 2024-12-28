##### The exercise in the index.html shows how to achieve various styling at different screen breakpoints using min-width and max-width properties.

# Media Query
- Used for adding breakpoints to define responsive layouts.
- Instead of using the selector, we use @media
## Synatax
```
@media (max-width: 600px){
    Style to apply to specified screen size.
}
```
- The CSS rule inside the @media query overrides the default styling.
- We can combine two screen sizes while defining media query.
```
@media (min-width: 600px)and (max-width: 900px){
    styles to apply to screens between 600px and 900px
}
```
- It is key to understand the breakpont max-width and min-width. 
- For **max-width**, the styles apply for screen sizes equal or below the specified screen size.
- For **min-width**, the styles apply to screen size equal or greater than the specified screen size.
- The combination of min-width and max-width allow us to define screen limits we want to apply style to.

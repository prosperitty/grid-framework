# Simple Grid Framework

### Overview

This is a 12-column grid framework that is being applied to a cloned version of The Odin Project website.

### Main focus
- Learn Sass
- Responsive Design

## How it works

### Grid Container
To initialize a 12 column grid container, you may use a predefined class named "container". Like so:

```html 
<div class="container">
    <div>example</div>
</div>
```

### Setting columns
This framework allows you to utilize columns to create a responsive layout.
After initializing a grid container, you may start adding content to this container.
Predefined classes, "column-[1-12]", can be utilized to create column layouts of your desire.

A one column grid may be created like so:

```html 
<div class="container">
    <div class="column-12">content</div>
</div> 
```

A two column grid may be created like so:

```html 
<div class="container">
    <div class="column-6">content</div>
    <div class="column-6">content</div>
</div> 
```

### Grid Breakpoints
Breakpoints may be applied to break columns at certain screen sizes.
There are three breakpoints, which are, "lg", "md", and "sm".
These breakpoints may be added to the "column" class to break certain columns.

- Sizes
    - lg = min-width 1200px
    - md = min-width 992px, max-width 1199.99px
    - sm = max-width 991.99px

Example:
At the large breakpoint, the container will have 4 columns
At the medium breakpoint, the container will have 2 columns
At the small breakpoint, the container will have 1 column

```html 
<div class="container">
    <div class="column-lg-3 column-md-6 column-sm-12">1/4</div>
    <div class="column-lg-3 column-md-6 column-sm-12">2/4</div>
    <div class="column-lg-3 column-md-6 column-sm-12">3/4</div>
    <div class="column-lg-3 column-md-6 column-sm-12">4/4</div>
</div> 
```

## References

[The Odin Project](https://www.theodinproject.com/courses/html-and-css/lessons/design-your-own-grid-based-framework)

[Live Demo](https://alex-lvl.github.io/grid-framework/)


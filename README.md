# 12 Columns Grid (via CSS Custom Properties)

I introduce Bootstrap's 12 Columns Grid realized via Vanilla CSS (CSS Variables / CSS Custom Properties).

> You might not need a CSS Preprocessors

## Example
```css
// your css file
@import 'css-vars-grid.css';
```

```html
// your html
// …
<div class="row">
  <div class="col-5">Hello</div>
  <div class"col-7">World</div>
</div>
```

[Familiar syntax](https://getbootstrap.com/docs/4.0/layout/grid/) for class names (`col-`, `push-`, `pull-`, `offset-`) and breakpoints from Bootstrap 4 (`sm: 576px`, `md: 762px`, `lg: 992px` and `xl: 1200px`).

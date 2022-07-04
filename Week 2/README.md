# Week 2

- [Keynote](https://docs.google.com/presentation/d/1SKM9rU0F8iKHCu1u9bhCFoVhlxMzynxhe0CFkrRvS1I/edit#slide=id.g1315a388697_0_16)

## Basic

- [index.html](Basic/index.html)

## Javascript

- declare
  - const > let > var
- operator
  - `==`
    - 比較值
      - 1 = '01'
        - true
  - `===`
    - 比較值及比較型態

## CSS

- [CSS Selector](https://www.w3schools.com/cssref/css_selectors.asp)
  - type
  - class
  - id
  - attribute
  - combinators
  - pseudo
- CSS Style
  - box-sizing
  - border
  - padding
  - margin
  - position

### SCSS

- Preprocessor
  - `Sass`, `Less`
- variables

```scss
$primaryColor: blue;
.title {
  color: $primaryColor;
}
.text {
  color: $primaryColor;
}
```

- nesting

```scss
.box {
  border: 1px solid #fff;
  .button {
    color: red;
    &.disabled {
      opacity: 0.5;
    }
  }
}
```

- mixin
  - 有點像 function

```scss
@mixin square($size, $radius: 0) {
  width: $size;
  height: $size;
  @if $radius != 0 {
    border-radius: $radius;
  }
}
.box {
  @include square(100px, $radius: 4px);
}
```

- extends

```scss
%message-style {
  font-size: 14px;
  color: #000;
}
.message {
  @extend %message-style;
}
```

```css
.success {
  @extend %message-style;
  border-color: green;
}
.error {
  @extend %message-style;
  border-color: red;
}
```

- function

```scss
@function shadow($colors) {
  $result: ();
  @each $color in $colors {
    $i: index($colors, $color);
    $result: append($result, $i * 2px $i * 2px $color, comma);
  }
  @return $result;
}
.box {
  $colors: red, blue, green, yellow;
  box-shadow: shadow($colors);
}
```

## React

- [React Sample Code](./react-sample-code/)

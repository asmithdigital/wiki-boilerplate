[Pseudo-elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)

[Pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/pseudo-classes)

[KSS Commenting](http://warpspire.com/kss/syntax/)

# CSS Properties Grouped by type:

```CSS
.selector {

  /* @extend / @mixin - no content */
  @extend %property;
  @mixin clearfix();

  /* Positioning */
  position: absolute;
  z-index: 10;
  top: 0;
  right: 0;

  /* Display & Box Model */
  display: inline-block;
  overflow: hidden;
  box-sizing: border-box;
  width: 100px;
  height: 100px;
  margin: 10px;
  padding: 10px;
  border: 10px solid #333;

  /* Color */
  background: #000;
  color: #fff
  
  /* Text */
  font-family: sans-serif;
  font-size: 16px;
  line-height: 1.4;
  text-align: right;

  /* Other */
  cursor: pointer;

  /* @extend / @mixin - with content *
  @mixin breakpoint ($variable) {
    property: value;
  }

  /* Pseudo-elements */
  &::before { }

  /* Scss nested selector */
  &__item { } 

}
```

**References:**

* [CSS tricks Poll](https://css-tricks.com/poll-results-how-do-you-order-your-css-properties/)

* [github.com/necolas/idiomatic-css](https://github.com/necolas/idiomatic-css#4-format)
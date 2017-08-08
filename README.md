# Scalable

### Install

```sh
npm install scalable --save-dev
```

### Usage

```sh
var scalable = new Scalable(element, options);
```

### Options
+ `align`: `left | center | right` Horizontal alignment of an element. `default: left`
+ `verticalAlign`: `top | center | bottom` Vertical alignment of an element. `default: top`
+ `containerHeight`: `fixed | auto` Behaviorur of container height property  `default: fixed`
  + `fixed` - The element fits inside the container.
  + `auto` - Enlargement of the element increases the height of the container.
+ `minWidth`: Minimum width of an element.
+ `maxWidth`: Maximum width of an element.
+ `minScale`: Minimum scale of an element.
+ `maxScale`: Maximum width of an element.


### Example

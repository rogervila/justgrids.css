![JustGrids.css](http://rogervila.github.io/justgrids.css/tests/demo.png)

# JustGrids.css

JustGrids is very simple, **lightweight and responsive css grid system**. these are some of its advantages:

  - No dependencies
  - No javascript
  - Compatible with all browsers*

## Demo

[Visit de demo](http://rogervila.github.io/justgrids.css/) to test JustGrids.css

## Browser support

JustGrids.css is **supported by all CSS2 compatible browsers**.

**Responsive does not work in IE 8**, because it does not support mediaqueries.

[Microsoft dropped support for IE8, IE9 and IE10](https://www.microsoft.com/en-us/WindowsForBusiness/End-of-IE-support), so it is not planned to make it work in this browser.

Anyway, **the grid system DOES work in old browsers**.

## Example

JustGrids.css uses rows and columns. 

```html
<div class="grid row">
    <div class="grid column size-6-12 offset-6-12">
        <p>I'm taking the right half of the screen</p>
    </div>
</div>
```
You can determinte the size for different device widths:

```html
<div class="grid row">
    <div class="grid column size-6-12 offset-6-12 md-size-12-12 md-offset-0-12">
        <p>I take the right half of the screen on big screens<p>
        <p>On medium screens, I take the whole screen</p>
    </div>
</div>
```

## Responsive

JustGrids uses 3 different sizes: Normal, medium and small:

| Size                                     | Pixels          |
|------------------------------------------|-----------------|
| **Normal size** (size-n-n, offset-n-n)       | **> 768**           |
| **Medium siz**e (md-size-n-n, md-offset-n-n) | **> 568 && <= 768** |
| **Small size** (sm-size-n-n, sm-offset-n-n)  | **<= 568**          |

## TODO

* Easy expandable 
* Pretty demo page

## License
MIT, created by [Roger Vilà](https://www.linkedin.com/in/rogervilacamon)

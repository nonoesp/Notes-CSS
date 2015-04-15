Notes-CSS
=========

Useful notes on CSS.

## Child selector

`.wrapper *` Selector for every child of .wrapper

`.wrapper > *` Selector for every descendant of .wrapper (first level children)

## Center Element Horizontally

HTML
```html
<div class="wrap">
	Some content.
</div>
```

CSS
```css
.wrap {
	max-width: 640px;
	margin: 0 auto;
}
```

## Fake Underline with Border

```css
.u-borderBottom {
	box-shadow: inset 0 -2px 0 0 rgba(255, 255, 255, 1), inset 0 -3px 0 0 rgba(125, 125, 125, 0.25);	
}
```

## TODO (SCSS)


 
```css
.u-waterBlueGradient {
	background-image:-webkit-linear-gradient(45deg, rgba(35,165,184,0.83), rgba(10,80,129,0.83));
	background-image:-moz-linear-gradient(45deg, rgba(35,165,184,0.83), rgba(10,80,129,0.83));
	background-image:-o-linear-gradient(45deg, rgba(35,165,184,0.83), rgba(10,80,129,0.83));
	background-image:linear-gradient(45deg, rgba(35,165,184,0.83),rgba(10,80,129,0.83));
}

.u-blueGradient {
	background-image:-webkit-linear-gradient(45deg, rgba(36,41,50,0.83), rgba(49,56,88,0.83));
}

.u-blackGradient {
	background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(0,0,0,0)), color-stop(59%,rgba(0,0,0,0)), color-stop(100%,rgba(0,0,0,0.65))), url('/img/architect.jpg') no-repeat;
}
```

## Remove iOS Input Shadows

```scss
@include appearance(none);
```

## License

Notes-CSS is licensed under the MIT license. (http://opensource.org/licenses/MIT)

## Me

I tweet at [@nonoesp](http://www.twitter.com/nonoesp) and blog at [nono.ma/says](http://nono.ma/says). I would love to hear about it if you find these notes are useful. Thanks!

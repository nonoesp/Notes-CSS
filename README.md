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

## License

Notes-CSS is licensed under the MIT license. (http://opensource.org/licenses/MIT)

## Me

I tweet at [@nonoesp](http://www.twitter.com/nonoesp) and blog at [nono.ma/says](http://nono.ma/says). I would love to hear about it if you find these notes are useful. Thanks!

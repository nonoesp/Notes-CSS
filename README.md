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
	max-width: 640px
	margin: 0 auto;
}
```
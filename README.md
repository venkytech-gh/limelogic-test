# limelogic-test
testing the website


## How to use the wave background

Add the following HTML inside your page:

```html
<div class="wave-bg">
  <!-- paste SVG code here -->
</div>
```

Then add this CSS:

```css
.wave-bg {
  position: absolute;
  inset: 0;
  z-index: 0;
}

.wave-bg svg {
  width: 100%;
  height: 100%;
  display: block;
}
```

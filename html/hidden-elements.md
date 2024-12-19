# Hidden elements

## Hide an element

```html
<div hidden>Hidden content</div>
```

## Hide only from assistive tecnology

```html
<div aria-hidden="true">Hidden content</div>
```

## Hide only visually

```css
.visually-hidden:not(:focus):not(:active) {
  clip: rect(0 0 0 0);
  clip-path: inset(50%);
  height: 1px;
  overflow: hidden;
  position: absolute;
  white-space: nowrap;
  width: 1px;
}
```

```html
<div class="visually-hidden">Hidden content</div>
```

---

[Inclusively Hidden](https://www.scottohara.me/blog/2017/04/14/inclusively-hidden.html)

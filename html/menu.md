# Menu

## Simple menu

```html
<div aria-label="Accessibility options" role="menu">
  <button role="menuitem" type="button">Color contrast</button>
  <button role="menuitem" type="button">Easy language</button>
  <button role="menuitem" type="button">Font size</button>
</div>
```

## List

The role `menuitem` must be direct descendant of `menu`. That's why we use the
`presentation` role for the middle items.

```html
<ul aria-label="Accessibility options" role="menu">
  <li role="presentation">
    <button role="menuitem" type="button">Color contrast</button>
  </li>
  <li role="presentation">
    <button role="menuitem" type="button">Easy language</button>
  </li>
  <li role="presentation">
    <button role="menuitem" type="button">Font size</button>
  </li>
</ul>
```

---

- [Menu and navigation: The difference](https://stevefrenzel.dev/posts/menu-and-navigation-the-difference/)

# Icon link/button

## Icon only link

```html
<a
  href="https://twitter.com/misteroom"
  title="Follow me on Twitter"
  aria-label="Follow me on Twitter"
>
  <svg
    aria-hidden="true"
    focusable="false"
    xmlns="http://www.w3.org/2000/svg"
    viewbox="0 0 16 16"
  >
    …
  </svg>
</a>
```

## Icon only button

```html
<button type="button" aria-label="Follow me on Twitter">
  <svg
    aria-hidden="true"
    focusable="false"
    xmlns="http://www.w3.org/2000/svg"
    viewbox="0 0 16 16"
  >
    …
  </svg>
</button>
```

## Alternative solution

```html
<button type="button">
  <span class="sr-only">Follow me on Twitter</span>
  <svg
    aria-hidden="true"
    focusable="false"
    xmlns="http://www.w3.org/2000/svg"
    viewbox="0 0 16 16"
  >
    …
  </svg>
</button>
```

`.sr-only` is a CSS class to make the element visible only for screen readers.

---

- [Accesible icon links](https://hugogiraudel.com/2020/12/10/accessible-icon-links/)
- [Buttons and the Baader–Meinhof phenomenon](https://www.matuzo.at/blog/2022/button-baader/)
- [Misleading Icons: Icon-Only-Buttons and Their Impact on Screen Readers](https://htmhell.dev/adventcalendar/2024/27/)

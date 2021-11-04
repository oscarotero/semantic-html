# Buttons

## Native button

```html
<button type="button">Click me</button>
```

## Button to send a form

```html
<button type="submit">Send data</button>
```

## Link used as button

Used only to triggering in-page functionality, rather than navigating to another
document or section within the current page.

```html
<a href="/fallback-url.html" role="button">Link</a>
```

## ON/OFF buttons

```html
<!-- This button is NOT active -->
<button aria-label="Favorite" aria-pressed="false">❤</button>

<!-- This button IS active -->
<button aria-label="Favorite" aria-pressed="true">❤</button>
```

---

[Button state and accessibility](https://gomakethings.com/button-state-and-accessibility/)

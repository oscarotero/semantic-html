# Menu

## Simple visible menu

The link to `#main` is the current page, so it works as a skip link.

```html
<nav aria-label="Main menu">
    <ul>
        <li><a href="/">Home</a></li>
        <li><a href="#main">About us</a></li>
        <li><a href="/services">Services</a></li>
        <li><a href="/projects">Projects</a></li>
        <li><a href="/contact">Contact</a></li>
    </ul>
</nav>
```

## Menu with button to show/hide

Note: this approach requires javascript to show/hide the list on click the button

```html
<nav aria-label="Main menu">
    <button aria-expanded="false">
        <svg>...</svg>
        Menu
    </button>

    <ul id="menu-list" hidden>
        <li><a href="/">Home</a></li>
        <li><a href="#main">About us</a></li>
        <li><a href="/services">Services</a></li>
        <li><a href="/projects">Projects</a></li>
        <li><a href="/contact">Contact</a></li>
    </ul>
</nav>
```

---

* [Patrones diseño inclusivos - Víctor Rodríguez](https://youtu.be/B2vbQ57Tf-c)

# Breadcrumb

## Breadcrumb navigation
```html
<nav aria-labelledby="breadcrumb">
    <h1 id="breadcrumb">You are here:</h1>
    <ul id="breadcrump-list">
        <li><a href="/">Main</a> →</li>
        <li><a href="/products/">Products</a> →</li>
        <li><a href="/products/dishwashers/">Dishwashers</a> →</li>
        <li><a>Second hand</a></li>
    </ul>
</nav>
```

## Alternative version

This version uses a `<p>` instead of `<ul>` for the links (from WHATWG).
Useful if you have more than one path:

```html
<nav aria-labelledby="breadcrumb">
    <h1 id="breadcrumb">You are here:</h1>
    <p>
        <a href="/">Main</a> ▸
        <a href="/products/">Products</a> ▸
        <a href="/products/dishwashers/">Dishwashers</a> ▸
        <a>Second hand</a>
    </p>
    <p>
        <a href="/">Main</a> ▸
        <a href="/second-hand/">Second hand</a> ▸
        <a>Dishwashers</a>
    </p>
</nav>
```

---

* [Common idioms without dedicated elements](https://www.w3.org/TR/html5/common-idioms-without-dedicated-elements.html#bread-crumb-navigation)
* [Patrones diseño inclusivos - Víctor Rodríguez](https://youtu.be/B2vbQ57Tf-c)
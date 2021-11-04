# Pagination

## Simple pagination with next/prev pages

```html
<nav aria-label="You are in page 2">
    <a href="page1" rel="prev">Previous page (1)</a>
    <a href="page3" rel="next">Next page (3)</a>
</nav>
```

## Pagination with a map of pages

```html
<nav aria-label="You are in page 2">
    <ul>
        <li><a href="page1" aria-label="Page 1" rel="prev">1</a></li>
        <li><a href="page2" aria-label="Page 2" aria-current="page">2</a></li>
        <li><a href="page3" aria-label="Page 3" rel="next">3</a></li>
        <li><a href="page4" aria-label="Page 4">4</a></li>
        <li><a href="page5" aria-label="Page 5">5</a></li>
    </ul>
</nav>
```

---

- [A11y pagination](https://a11y-style-guide.com/style-guide/section-navigation.html)

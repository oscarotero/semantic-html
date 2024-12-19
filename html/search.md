# Search

## Search form

```html
<form role="search">
    <input type="search" aria-label="search text" size="20" enterkeyhint="search">
    <button type="submit">Search<button>
</form>
```

## Alternative version using the new `<search>` element:

```html
<search>
  <form>
    <input
      type="search"
      aria-label="search text"
      size="20"
      enterkeyhint="search"
    >
    <button type="submit">Search</button>
  </form>
</search>
```

---

- [Search Landmark](http://w3c.github.io/aria-practices/examples/landmarks/search.html)
- [enterkeyhint](https://html.spec.whatwg.org/multipage/interaction.html#input-modalities:-the-enterkeyhint-attribute)
- [`<search>` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/search)

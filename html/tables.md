# Tables

## With a A11y friendly title

```html
<table>
  <caption>
    <h2>Top 10 best-selling albums of all time</h2>
  </caption>

  <!-- Table markup -->
</table>
```

Alternative version using a `figure` and `figcaption`:

```html
<figure>
  <figcaption id="caption">Top 10 best-selling albums of all time</figcaption>
  <table aria-labelledby="caption">
    <!-- Table markup -->
  </table>
</figure>
```

If we want to make the table scrollable, we can use a `div` to wrap the `table`.
The `tabindex` is needed for keyboard navigation:

```html
<figure>
  <figcaption id="caption">
    <h2>Top 10 best-selling albums of all time</h2>
  </figcaption>

  <div
    class="table-wrapper"
    role="group"
    aria-labelledby="caption"
    tabindex="0"
  >
    <table><!-- Table markup --></table>
  </div>
</figure>
```

---

- [Accessible front-end patterns for responsive tables](https://www.smashingmagazine.com/2022/12/accessible-front-end-patterns-responsive-tables-part1/)
- [Pure CSS scrolling shadows](https://lea.verou.me/2012/04/background-attachment-local/)

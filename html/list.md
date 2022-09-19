# List

## List of ordered elements

```html
<ol>
  <li>One</li>
  <li>Two</li>
  <li>Three</li>
</ol>
```

## List of unordered elements

```html
<ul>
  <li>One</li>
  <li>Two</li>
  <li>Three</li>
</ul>
```

## Unstyled list of elements

If the list is styled with `list-style: none`, the `role="list"` attribute must be added due the Safari behavior.

```html
<style>
  .no-style {
    list-style: none;
  }
</style>

<ul class="no-style" role="list">
  <li>One</li>
  <li>Two</li>
  <li>Three</li>
</ul>
```

## List of key-value pairs

```html
<dl>
  <dt>Name</dt>
  <dd>Óscar</dd>
  
  <dt>Surname</dt>
  <dd>Otero</dd>
</dl>
```

Alternative version for styling purposes:

```html
<dl>
  <div>
    <dt>Name</dt>
    <dd>Óscar</dd>
  </div>
  
  <div>
    <dt>Surname</dt>
    <dd>Otero</dd>
  </div>
</dl>
```

---

["Fixing" Lists](https://www.scottohara.me/blog/2019/01/12/lists-and-safari.html)

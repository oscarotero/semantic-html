# Navbar

## Using a `<header>`

We can use the `<header>` element as long as it is NOT a descendant of `<aside>`, `<article>`, `<main>`, `<nav>`, or `<section>`.

```html
<body>
  <header>
    <a href="#main" class="skiptocontent">Skip To main content</a>
    <img src="images/logo.png" alt="Website Logo" />
    <h1>Name of the site</h1>
    <nav aria-label="Main menu">…</nav>
  </header>
  …
<body>
```

## Using `role="banner"`

If it's not possible to use a `<header>` element because it's a descendant of `<aside>`, `<article>`, `<main>`, `<nav>`, or `<section>`, we can use ARIA roles.

The *banner* role is for defining a global site header, which usually includes a logo, company name, search feature, and possibly the global navigation or a slogan.

```html
<body>
  <main>
    <div role="banner">
      <a href="#main" class="skiptocontent">Skip To main content</a>
      <img src="images/logo.png" alt="Website Logo" />
      <h1>Name of the site</h1>
      <nav aria-label="Main menu">…</nav>
    </div>
    …
  </main>
<body>
```

---

- [Best intention barriers (ARIA edition)](https://marcus.io/blog/best-intention-barriers-aria)
- [ARIA: banner role](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/banner_role)

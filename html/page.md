# Page

Minimum html needed for any html page:

```html
<!DOCTYPE html>

<html lang="es">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Page description | Site name</title>
    </head>
    <body>
        <a href="#main">Go to the main content</a>

        <main id="main">
            <h1>Page title</h1>

            Main content here
        </main>
    </body>
</html>
```

---

## `lang` attribute

* Help the browser to choose a font that support that language
* Screen readers use this value to select the right voice syntetizer
* Improve content indexing
* Useful for users using Google Translate

## `viewport` config

* Make the web responsive, so it can ve viewed in a smartphone allowing zoom.

## `title` element

* Must contain the name of the document in an accessible way, using the pattern `page description | site name`.

## Skip link

* A hidden link, only visible on focus, that allows to jump directly into the main region.

## `main` element

* Only one `main` element in the page.
* Determines the main content of the page.
* Screen readers can jump directly into this region.
* A useful tip for printing:
  ```css
  @media print {
      body > *:not(main) {
          display: none;
      }
  }
  ```

## `h1` element

* Screen readers can jump directly into this element.

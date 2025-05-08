# Form fields

## Fields within text

```html
<label>The airport is <input type="text" name="miles" size="3" value="8"> miles
  away.</label>
```

## Field with help text

```html
<label for="username">Username</label>
<input
  type="text"
  name="username"
  id="username"
  aria-invalid="false"
  aria-describedBy="help"
>
<span id="help">Enter your user name</span>
```

## Field with error message

```html
<label for="username">Username</label>
<input
  type="text"
  name="username"
  id="username"
  aria-invalid="true"
  aria-describedBy="error"
>
<strong id="error">The username is incorrect</strong>
```

## Field with `pattern`

Use the `title` attribute to customize the error message.

```html
<label for="name">Name</label>
<input
  type="text"
  name="name"
  id="name"
  pattern="Bob [A-Za-z].+"
  title="The name must start with 'Bob '"
>
```

## Multi-part fields

```html
<div role="group" aria-labelledby="label">
  <span id="label">Social Security</span>
  <span>
    <input type="number" name="ss-1" size="3" title="First 3 digits" required>
    <input type="number" name="ss-2" size="2" title="Next 2 digits" required>
    <input type="number" name="ss-3" size="4" title="Last 4 digits" required>
  </span>
</div>
```

> Note: You can use `<fieldset>` instead `<div role="group">` but has layout
> issues

## A group of radio buttons

```html
<div role="radiogroup" aria-labelledby="label">
  <span id="label">Credit Card Type:</span>
  <span>
    <label><input type="radio" name="cct" value="visa"> Visa</label>
    <label><input type="radio" name="cct" value="mastercard"> Master
      Card</label>
    <label><input type="radio" name="cct" value="other"> Other</label>
  </span>
</div>
```

---

- [Marking up forms and reporting violations of forms](http://mars.dequecloud.com/demo/form-markup.htm)
- [Semantic markup for fieldset alternative](https://stackoverflow.com/questions/48413847/semantic-markup-for-fieldset-alternative)
- [Semantic input error message inside label](https://stackoverflow.com/questions/46656151/semantic-input-error-message-inside-label)
- [ARIA21: Using Aria-Invalid to Indicate An Error Field](https://www.w3.org/TR/2016/NOTE-WCAG20-TECHS-20161007/ARIA21#ARIA21-description)
- [Lesser Known Uses Of Better Known Attributes](https://www.smashingmagazine.com/2025/01/lesser-known-uses-better-known-attributes/)

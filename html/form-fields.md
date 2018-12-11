# Form fields

## Fields within text
```html
<label>The airport is  <input type="text" name="miles" size="3" value="8">  miles away.</label>
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
> Note: You can use `<fieldset>` instead `<div role="group">` but has layout issues

## A group of radio buttons
```html
<div role="radiogroup" aria-labelledby="label">
    <span id="label">Credit Card Type:</span>
    <span>
        <label><input type="radio" name="cct" value="visa"> Visa</label>
        <label><input type="radio" name="cct" value="mastercard"> Master Card</label>
        <label><input type="radio" name="cct" value="other"> Other</label>
    </span>
</div>
```
---

* [Marking up forms and reporting violations of forms](http://mars.dequecloud.com/demo/form-markup.htm)

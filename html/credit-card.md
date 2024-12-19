# Credit card form

```html
<label for="card-holder">Card holder</label>
<input
  type="text"
  name="card-holder"
  id="card-holder"
  autocomplete="cc-name"
  required
>

<label for="card-number">Card number</label>
<input
  type="text"
  inputmode="numeric"
  name="card-number"
  id="card-number"
  autocomplete="cc-number"
  required
>

<label for="card-expiration-month">Card expiration month</label>
<input
  type="text"
  inputmode="numeric"
  maxlength="2"
  placeholder="MM"
  name="card-expiration-month"
  id="card-expiration-month"
  autocomplete="cc-exp-month"
  required
>

<label for="card-expiration-year">Card expiration year</label>
<input
  type="text"
  inputmode="numeric"
  maxlength="4"
  placeholder="YYYY"
  id="card-expiration-year"
  name="card-expiration-year"
  autocomplete="cc-exp-year"
  required
>

<label for="card-cvv">CVV</label>
<input
  type="text"
  inputmode="numeric"
  maxlength="3"
  placeholder="000"
  name="card-cvv"
  id="card-cvv"
  autocomplete="cc-csc"
  required
>
```

## Alternative for expiration date

```html
<label for="card-expiration">Card expiration date</label>
<input
  type="text"
  inputmode="numeric"
  maxlength="7"
  placeholder="MM/YYYY"
  name="card-expiration"
  id="card-expiration"
  autocomplete="cc-exp"
  required
>
```

---

- [HTML attribute: autocomplete](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/autocomplete)
- [The hidden depths of the input element](https://www.htmhell.dev/adventcalendar/2023/8/)

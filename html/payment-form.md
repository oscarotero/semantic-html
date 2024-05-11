# Payment form

Using attributes to help users to enter the data:

```html
<form method="post">
    <label for="number">Card number</label>
    <input id="number" name="number" autocomplete="cc-number" inputmode="numeric" required>

    <label for="name">Name on card</label>
    <input id="name" name="name" autocomplete="cc-name" required>

    <label for="exp">Expiry date</label>
    <input id="exp" name="exp" autocomplete="cc-exp" required>

    <label for="csc">Security code</label>
    <input id="csc" name="csc" autocomplete="cc-csc" inputmode="numeric" required>

    <button>Complete payment</button>
</form>
```

---

- [Payment form best practices codelab](https://web.dev/articles/codelab-payment-form-best-practices)

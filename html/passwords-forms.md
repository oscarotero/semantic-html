# Forms with passwords

## Log in

Use `autocomplete="current-password"`

```html
<form>
    <label for="user-password">Password:</label>
    <input type="password" id="user-password" autocomplete="current-password" required>
</form>
```

## Sign-up or change the password

Use `autocomplete="new-password"`

```html
<form>
    <label for="user-password">New password:</label>
    <input type="password" id="user-password" autocomplete="new-password" required>
</form>
```
---

* [MDN: Allowing autocomplete](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/password#Allowing_autocomplete)

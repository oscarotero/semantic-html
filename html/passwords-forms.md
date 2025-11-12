# Forms with passwords

## Log in

Use `autocomplete="current-password"`

```html
<form>
  <label for="user-password">Password:</label>
  <input
    type="password"
    id="user-password"
    autocomplete="current-password"
    required
  >
</form>
```

## Sign-up or change the password

Use `autocomplete="new-password"`

```html
<form>
  <label for="user-password">New password:</label>
  <input
    type="password"
    id="user-password"
    autocomplete="new-password"
    required
  >
</form>
```

## One-Time Passcode

Example with numeric passcode but can be adapted to alphanumeric values.

```html
<form>
  <label for="user-password">
    Enter the 6-digit numeric code sent to +1 (555) 555-5555
  </label>
  <input
    type="text"
    id="user-password"
    inputmode="numeric"
    autocomplete="one-time-code"
    maxlength="6"
    pattern="\d{6}"
    required
  >
</form>
```

---

- [MDN: Allowing autocomplete](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/password#Allowing_autocomplete)
- [Simple One-Time Passcode Inputs](https://cloudfour.com/thinks/simple-one-time-passcode-inputs/)

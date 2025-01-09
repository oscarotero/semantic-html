# Accordion

## Simple accordion

```html
<details>
  This is a simple details content
</details>
```

## Accordion with custom summary

```html
<details>
  <summary>View all details</summary>
  This is a details content with custom summary
</details>
```

## Pre-opened accordion

```html
<details open>
  This is a simple details content
</details>
```

## Group of accordions mutually exclusive

```html
<details name="refrigerator">
  <summary>Refrigerator 1</summary>
  Lunches, condiments, yogurt et al.
</details>

<details name="refrigerator">
  <summary>Refrigerator 2</summary>
  More Lunches, leftovers from client meeting, stray cans of off-brand soda et
  al.
</details>

<details name="refrigerator">
  <summary>Refrigerator 3</summary>
  Cookie dough someone bought from somebody’s child’s fundraiser, expired milk,
  unidentifiable meat et al.
</details>
```

---

- [Quick Reminder that Details/Summary is the Easiest Way Ever to Make an Accordion](https://css-tricks.com/quick-reminder-that-details-summary-is-the-easiest-way-ever-to-make-an-accordion/)
- [MDN: &lt;details&gt;](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details)
- [MDN: &lt;summary&gt;](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/summary)
- [Can I Use #details](https://caniuse.com/#feat=details)
- [Lesser Known Uses Of Better Known Attributes](https://www.smashingmagazine.com/2025/01/lesser-known-uses-better-known-attributes/)

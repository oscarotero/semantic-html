# Abbreviation and acronyms

Provide an expansion of the abbreviation/acronym, neuronym even, in plain text
on first use, use an <abbr> to mark up the abbreviation, which provides a hint
to user agents on how to announce/display the content

```html
<p>
  <abbr>FWIW</abbr> (For what it's worth) I often get the following confused:
  <abbr>WTF</abbr> and <abbr>FTW</abbr>.
</p>

<p>
  By providing a plain text expansion besides the acronyms, myself and probably
  others, are less confused by the jargon. Thus improving usability and <abbr
  >a11y</abbr> (accessibility).
</p>
```

## Linking to definitions

```html
<p>
  The <a href="#def-wai">WAI</a> demonstrates the <a href="#def-w3c">W3C</a>
  commitment to accessibility
</p>

<h3>Definitions:</h3>
<dl>
  <dt id="def-wai">WAI</dt>
  <dd>Web Accessibility Initiative</dd>
  <dt id="def-wai">W3C</dt>
  <dd>World Wide Web Consortium</dd>
</dl>
```

---

- [Short note: The abbreviation appreciation society](https://developer.paciellogroup.com/blog/2019/03/short-note-the-abbreviation-appreciation-society/)
- [Abbreviations done right: The `<abbr>` element and why not use it](https://htmhell.dev/adventcalendar/2025/25/)

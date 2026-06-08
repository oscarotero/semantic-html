# Tabs

## Accessible tabs

```html
<div role="region">
  <div role="tablist">
    <button role="tab" id="tab1" aria-selected="true">
      Section 1
    </button>
    <button role="tab" id="tab2">
      Section 2
    </button>
    <button role="tab" id="tab3">
      Section 3
    </button>
  </div>

  <section role="tabpanel" id="section1" aria-labelledby="tab1">
    Content section 1
  </section>

  <section role="tabpanel" id="section2" aria-labelledby="tab2">
    Content section 2
  </section>

  <section role="tabpanel" id="section3" aria-labelledby="tab3">
    Content section 3
  </section>
</div>
```

## Using anchors

The same code but using anchors for progressive enhancement:

```html
<div role="region">
  <ul role="tablist">
    <li role="presentation">
      <a role="tab" id="tab1" href="#section1" aria-selected="true">
        Section 1
      </a>
    </li>
    <li role="presentation">
      <a role="tab" id="tab2" href="#section2">
        Section 2
      </a>
    </li>
    <li role="presentation">
      <a role="tab" id="tab3" href="#section3">
        Section 3
      </a>
    </li>
  </ul>

  <section role="tabpanel" id="section1" aria-labelledby="tab1">
    Content section 1
  </section>

  <section role="tabpanel" id="section2" aria-labelledby="tab2">
    Content section 2
  </section>

  <section role="tabpanel" id="section3" aria-labelledby="tab3">
    Content section 3
  </section>
</div>
```

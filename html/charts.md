# Charts

## Simple charts using `alt`

```html
<img
  src="chart.svg"
  alt="Chart showing the people's favorite StarWars characters. 22% chose Han Solo, 18% chose Darth Vader"
>
```

## Simple charts using SVG

```html
<svg
  role="img"
  aria-labelledby="title description"
  xmlns="http://www.w3.org/2000/svg"
>
  <title id="title">Favourite characters from Star Wars</title>
  <desc id="description">
    Chart showing people's favourite characters from the original Star Wars
    trilogy
  </desc>

  <!-- SVG code -->
</svg>
```

## Complex charts using SVG

Use `table`, `columnheader`, `row`, `rowheader` and `cell` roles to convert the
graphics elements into a table for screen readers:

```html
<svg xmlns="http://www.w3.org/2000/svg">
  <title>Favourite characters from Star Wars</title>
  <desc>
    Chart showing people's favourite characters from the original Star Wars
    trilogy
  </desc>

  <g role="table">
    <g role="row">
      <text role="columnheader" x="..." y="...">
        Name
      </text>
      <text role="columnheader" x="..." y="...">
        Percentage of votes
      </text>
    </g>

    <g role="row">
      <g role="rowheader">
        <path role="img" d="...">
          <title>Han Solo</title>
        </path>
      </g>

      <g role="cell">
        <path role="img" d="...">
          <title>22%</title>
        </path>
      </g>
    </g>
    <g role="row">
      <g role="rowheader">
        <path role="img" d="...">
          <title>Darth Vader</title>
        </path>
      </g>

      <g role="cell">
        <path role="img" d="...">
          <title>18%</title>
        </path>
      </g>
    </g>
  </g>
</svg>
```

## Complex charts with SVG + tables

Another approach is to show the table content and the SVG chart separately:

```html
<svg role="presentation" xmlns="http://www.w3.org/2000/svg">
  <!-- SVG contents -->
</svg>

<table>
  <caption>
    Favourite characters from the original Star Wars trilogy
  </caption>
  <tr>
    <th>Character</th>
    <th>Percentage of votes</th>
  </tr>
  <tr>
    <td>Han Solo</td>
    <td>22%</td>
  </tr>
  <tr>
    <td>Darth Vader</td>
    <td>18%</td>
  </tr>
</table>
```

---

- [Do graphs and charts need to be accessible?](https://www.tempertemper.net/blog/do-graphs-and-charts-need-to-be-accessible)
- [Accessible SVG line graphs](https://tink.uk/accessible-svg-line-graphs/)

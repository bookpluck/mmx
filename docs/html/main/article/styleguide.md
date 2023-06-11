# Styleguides - An HTML Specification

## Guidance

- __Keep it semantic.__ 
  - `<aside>`
    - `<b>` tags represent positive rules (e.g. "Prefer") 
    - `<u>` tags represent negative rules (e.g. "Avoid...")
- __Keep it flat.__
  - `<h2>` is for category
  - `<h3>` is for specific advise using imperative voice
  - if you find yourself needing `<h4>`, seperate into a new styleguide

## Example

```html
<article class="styleguide">
  <menu id="toc">
    <li>
      <a href="#title">How to Write</a>
    </li>
  </menu>

  <h1 id="title">Story Meta-data</h1>
  <h2>Titles</h2> 
  <h3>Prefer Them Short & Sweet</h3>
  <aside>
    <b>
      <!-- example of good -->
    </b>
    <u>
      <!-- example of bad -->
    </u>        
  </aside>
  <p>
    <!-- explanation -->
  </p>
  <h3>Avoid Giving Too Much Away</h3>
  <aside>
    <strong>note</strong>
    <p>
      <!-- further explanation / short side discussion -->
    </p>
  </aside>
  <p>
    <!-- explanation -->
  </p>
</article>
```


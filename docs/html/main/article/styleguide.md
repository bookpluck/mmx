# Styleguides - An HTML Specification

## Guidance

- __Keep it flat.__ Aim for three indentation levels deep as a local maximum
- __Keep it semantic.__ In asides, `<b>` tags represent positive rules
  (e.g. "Prefer") and `<u>` tags represent negative rules (e.g. "Avoid...").


## Example

```html
<article class="styleguide">
  <menu id="toc">
    <li>
      <a href="#title">How to Write</a>
    </li>
  </menu>

  <h1 id="title">How to Write</h1>
  <h2 id="Metadata">Metadata</h2> 
  <h3>Titles</h3>
  <h4>Prefer Them Short & Sweet</h4>
  <aside>
    <b>strong</b>
    <p>
      <!-- example of good -->
    </p>
    <u>weak</u>
    <p>
      <!-- example of bad -->
    </p>        
  </aside>
  <p>
    <!-- explanation -->
  </p>
  <h4>Avoid Giving Too Much Away</h4>
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


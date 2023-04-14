# Styleguides - An HTML Specification

## Guidance

- __Keep it flat.__ Don't go down the rabit hole of using `<h4>` through `<h5>` tags.
- __Keep it semantic.__ In sections and asides, `<b>` tags represent positive rules
  (e.g. "Prefer") and `<u>` tags represent negative rules (e.g. "Avoid...").


## Example

```html
<main>
  <article class="styleguide">
    <menu id="toc">
      <li>
        <a href="#title">How to Write</a>
      </li>
    </menu>
    
    <h1 id="title">How to Write</h1> 

    <h2 id="Metadata">Metadata</h2> 
    
    <h3>Titles</h3>
    <section>
      <b>Prefer Them Short & Sweet</b>
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
      <u>Avoid Giving Too Much Away</u>
      <aside>
        <strong>note</strong>
        <p>
          <!-- further explanation / short side discussion -->
        </p>
      </aside>
      <p>
        <!-- explanation -->
      </p>
    </section>
  </article>
</main>
```


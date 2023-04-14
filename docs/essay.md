# Essay Specification

## Example

```html
<main>
  <article class="essay">
    <header>
      <small>Category</small>
      <hgroup>
        <h1>Essay Title</h1>
        <p>Essay Subtitle</p>
      </hgroup>
      <address>by Author Name</address>
      <figure>
        <!-- img and figcation tags for a essay header image ->
      </figure>    
    </header>
    <p>
     
    </p>
    <blockquote>
      <p>
        
      </p>
      <cite>&mdash;Title</cite> by Author Name
    </blockquote>
    <figure>
      <img src="path/to/image.jpg" alt="alt text" />
      <figcaption>
        Image copyright 
      </figcaption>
    </figure>
  </article>
</main>
```

### Tags

- __`cite`__ tags are used for the titles of books, stories, articles, et al.
  The `i` and `em` tags should not be used for this. 
- __`aside`__ tags are used for pull quotes.
  - __`small`__ tags can modify pull quotes to use a smaller font. Best used
    for longer quotes.
  - __`strong`__ tags imply that the text within them is important, which is
    why it is used for asides that are important to the nearby text.     

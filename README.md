## Starting a New Static Site

### 1. Add MMX

From the project root, run:
`git submodule add https://github.com/bookpluck/mmx.git`

### 2. Create partials

- Add `mmx-config` directory to your project root.
- Add `partials` directory in `mmx-config`.
- Add `_head.html.erb` and `_header.html.erb` and `_footer.html.erb` files in `partials` directory. 
   - note: `<head>` and `<header>` tags are provided by the mmx template
   - see: [Recommended head content](#recommended-head)
   - see: [Provided HTML](#provided-html)
   
### 3. Create an `erb` directory and add pages

- see: [Provided HTML](#provided-html)

### 4. Build the site

Run `mmx/bin/build`


### 5. Import styles

- create `css/main.css`
  - import css from MMX: `@import url('../mmx/css/main.css');`
- in `_head.html.erb`
  - add `<link rel="stylesheet" type="text/css" href="../../css/main.css">`
- `mmx/bin/build`

___

## Provided HTML

ERB pages can assume this HTML is provided:

```html
<!DOCTYPE html>
<html lang='en'>
  <head>
    <!-- head code that you will provide via partial -->    
  </head>
  <body>
    <header>
      <!-- header code that you will provide via partial -->    
    </header>
    <!-- page code will be rendered here -->    
  </body>
</html>
```
 
## Recommended `head`

```html
<meta charset="utf-8">
<title><%= meta_tags.title %></title>
<meta name="description" content="<%= meta_tags.description %>">
<meta name="author" content="">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

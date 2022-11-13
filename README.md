# Starting a New Static Site

0. __Create partials__
   - Add `mmx-config` directory to your project root.
   - Add `partials` directory in `mmx-config`.
   - Add `_head.html.erb` and `_header.html.erb` files in `partials` directory. 
      - note: `<head>` and `<header>` tags are provided by the mmx template
      - see: [Provided HTML](#provided-html)
0. __Create an `erb` directory and add pages.
   - see: [Provided HTML](#provided-html)
0. __Run `mmx/bin/build`__

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
      <!-- head code that you will provide via partial -->    
    </header>
      <!-- page code will be rendered here -->    
  </body>
</html>
```
 

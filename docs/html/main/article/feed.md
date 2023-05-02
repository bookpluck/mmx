# Feed YAML Specification

```yml
---
page_defaults: &page_defaults
  author_email: jack@marginchronicles.com

# list your public pages from most recent to least.
# this list will be used to:
# - build a sitemap.txt
# - build a feed.html
pages:
  - <<: *page_defaults
    path: essays/best-first-word  
    byline: Jack Windeyer
    tag: Essay
    hed: The Perfect First Word for Your Next Story 
    dek:
    standfirst:
    grafs: 
      - lede paragraph
      - nut paragraph
      - third paragraph
      
    # used on feed page for the spash article
    # should have larger width than height
    img_lg: img/essay-banners/difate-revolt-in-2100.jpg
    
    # used on feed page for non-splash articles
    # should be square
    image_sm: img/essay-banners/difate-revolt-in-2100-sm.jpg
```

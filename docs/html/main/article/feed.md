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
    author_name: Jack Windeyer
    page_type: Essay
    path: essays/best-first-word
    title: The Perfect First Word for Your Next Story
    description: >
      Magazines are swamped with submissions and some only have
      time to read a paragraph or two before deciding to reject
      or continue on. How do you hook a reader in the first sentence?
    image_banner: img/essay-banners/difate-revolt-in-2100.jpg
    # used on feed page for the most recent essay
    image_banner_md: img/essay-banners/difate-revolt-in-2100-md.jpg
    # used on feed page for all subsequent essays
    image_banner_sm: img/essay-banners/difate-revolt-in-2100-sm.jpg
```

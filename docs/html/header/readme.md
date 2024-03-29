# Header

Each host app is responsible for the layout and styling of its own header; this page exists as an example approach
that fits in the overal MMX design asthetic which takes its inspiration from the layout of print newspapers. As such,
this guide will reconstruct an exemplar of the print-newspaper header:

<img width="1586" alt="eunice-news" src="https://user-images.githubusercontent.com/114622842/232142460-29fb9735-6b55-4f75-a698-9f3072f8e338.png">

```html
<header>
  <aside>
    Eunice Newspaper Appears Under New Name, With New Dress
  </aside>
  <section>
    <div>
      A Modern Newspaper for a Growing Community
    </div>
    <hgroup>
      <h1>
        The Eunice News
      </h1>
      <p>
        (A Consolidation of The New Era and Clarion News)
      </p>
    </hgroup>
    <div>
      16 Pages This Issue
    </div>
  </section>
  <aside>
    <div>
      Member Lousiana Press Association
    </div>
    <div>
      Eunice, Louisiana, Thursday, November 29, 1951
    </div>
    <div>
      Member National Editorial Association
    </div>    
  </aside>
</header>
```

The rest of this guide digs into each of the child elements of the `header` element.

## Asides for Skyboxes

```
<aside>
  Eunice Newspaper Appears Under New Name, With New Dress
</aside>
```

## Main Section

### Divs for Ears

### H-Groups as Nameplates

```html
<hgroup>
  <h1>
    The Eunice News
  </h1>
  <p>
    (A Consolidation of The New Era and Clarion News)
  </p>
</hgroup>
```
The _Nameplate_ of a newspaper is the section that includes the name of the periodical. It may also include an image, 
slogan or brief detail about the paper.

### Aside for Banner

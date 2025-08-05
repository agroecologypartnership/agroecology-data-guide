# Agroecology Partnership: Data Management Guidelines

This repository contains a book written with Quarto and published via GitHub Pages. 



## How to edit this book

See the full documentation at https://quarto.org/docs/books/

### Write new pages or edit existing ones

Pages of the book are written in separated `.qmd` files. These are markdown files optimized for quarto (e.g. allowing to run code). However, this book uses only markdown syntax and does not run code.

Pages are indexed via `_quarto.yml`. This file also takes care of the css and other design styles of the final website.



### Edit references

References are written in `.bib` format and saved in the `references.bib` file. They are referenced within the text using their key as `[@key]`. Example: `[@wickham2014tidy]` is the key that references:

```
@article{wickham2014tidy,
  author       = {Wickham, Hadley},
  title        = {Tidy data},
  journal      = {Journal of Statistical Software},
  volume       = {59},
  number       = {10},
  pages        = {1--23},
  year         = {2014},
  doi          = {10.18637/jss.v059.i10},
  url          = {https://doi.org/10.18637/jss.v059.i10}
}
```



### Preview changes in the book locally

Before deploying a new version of the book online, it is advisable to first preview locally and see how it looks like. To do this:

1. Go to the terminal
2. Type and enter: `quarto preview`
3. Open the website at the localhost specified in the terminal.

You can also render the website locally without opening in a browser. Run `quarto render` to do this. 



### Deploy a new version online

To deploy a new version of the book online, run:

 ```
 quarto publish
 ```



## Acknowledges

This guidelines are written by the Data Management team at the ICT Core department of [LifeWatch ERIC](https://www.lifewatch.eu/) as part of the LifeWatch contribution to the WP5 of the [Agroecology Partnership](https://www.agroecologypartnership.eu/), funded by Horizon Europe.
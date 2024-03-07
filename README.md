# Hints for my Website

This is supposed to be a very lightweight thing. 
Static site generation at its minimum, basically hand written html with generated bibliography.


# Requirements and build

This site was built using

- [neat.css](https://neat.joeldare.com) to have very basic layout
- [bibtexparser](bibtexparser.readthedocs.org) to generate html from a bibtex file.

To install bibtexparser, use pip

```pip install bibtexparser```



# Template for bibtex

we have three relevant 'publicationtype' values: accepted, bestpaper, bestposter

```
@article{ln,
publicationtype = {accepted},
  pdf = {},
  poster = {},
  slides = {},
  video = {},
  code = {},
  reviews = {},
  venuetype = {},
  venueurl = {},
  author       = {},
  title        = {},
  year = {},
  journal = {},
  volume = {}, 
  comment = {},
}
```

```
@inproceedings{ln,
publicationtype = {accepted},
  pdf = {},
  poster = {},
  slides = {},
  video = {},
  code = {},
  reviews = {},
  venuetype = {},
  venueurl = {},
  author       = {},
  title        = {},
  year = {},
  booktitle = {}, 
  comment = {},
}
```
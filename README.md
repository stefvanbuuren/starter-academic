# academic

This repository contains the source of my academic website. The site uses 
`blogdown` in combination with the `starter-academic` theme.

Updating:

- `contents/publication/xxx` to change or add publications
- `config/_default/config.toml` and friends for configuration

Add a publication:

- `static/publications/` for adding pdf's
- `static/files/citations/` for adding .bib files. 
- run `academic import --bibtex static/files/citations/2020-08-12_new.bib` to create a new directory `contents/publication/[xxx]/` with `.bib` and `.md` files
- change author "S. van Buuren" to `admin`
- add line `url_pdf: 'publications/thepdf.pdf'`
- add file `featured.png` with illustration to `contents/publication/[xxx]/` folder

Use `blogdown:::serve_site()` to update the website after a source file is saved. 

The terminal command `./deploy.sh` will rebuild the website 
and upload the contents to `stefvanbuuren/stefvanbuuren.github.io`, 
from where it is published at https://stefvanbuuren.name. 


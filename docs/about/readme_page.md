---
title: Development Readme
summary: Setup and instructions for development.
authors:
    - Jacques du Plessis
---
# KArchives Development Readme
Using mkdocs to make some wiki magic.  This project is a collection pages that describe Aklatoria, named the **Kobold Archives**.

## Installation

- Download and install python3
- Run pip installs:
```
pip install mkdocs
pip install mkdocs-material
pip install pymdown-extensions
pip install markdown-blockdiag
pip install markdown-include
```

> See installation instructions for MkDocs at [https://www.mkdocs.org/#installation](https://www.mkdocs.org/#installation)<br>
> See cool examples at [https://alinex.gitlab.io/env/mkdocs](https://alinex.gitlab.io/env/mkdocs)

## Startup
* Open project directory in terminal
* Run `mkdocs serve` to start the live-reloading docs server
* Open browser at [http://127.0.0.1:8000](http://127.0.0.1:8000)

## Making pages
* Pages are stored in nested folders inside the `docs` folder
* Page resources are saved as markdown (.md) files

### Page Design Guide
* Use nested pages where possible
* Don't worry too mush about linking right away, pages may be moved (the search option can help you find any page easily).
* Link assets from the assets folders (images etc.)

## Useful Links and Resources
* [MkDocs Documentation](https://www.mkdocs.org/)
* [MkDocs Awesome Pages - Plugin](https://github.com/lukasgeiter/mkdocs-awesome-pages-plugin)
* [Markdown Documentation](https://daringfireball.net/projects/markdown/)
* [Table Generator](https://www.tablesgenerator.com/markdown_tables)

## Plugins Documentation 
* [includes](https://pypi.org/project/markdown-include/)
* [extensions](https://pypi.org/project/pymdown-extensions/)


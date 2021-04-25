---
title: Development Readme
summary: Setup and instructions for development.
authors:
    - Jacques du Plessis
---
# KArchives Development Readme

## Installation

- Download and install [python3](https://www.python.org/)

**Mac / Linux:**
```
python -m venv env
. ./env/bin/activate
pip install -r requirements.txt
```

**Windows (Bash shell):**
```
python -m env karchives_venv
. ./env/Scripts/activate
pip install -r requirements.txt
```

**Manual installation:**
- See installation instructions for MkDocs at [https://www.mkdocs.org/#installation](https://www.mkdocs.org/#installation)

## Startup
* With the Virtual environment active
* Run `mkdocs serve` to start the live-reloading docs server
* Open browser at [http://127.0.0.1:8000](http://127.0.0.1:8000)

## Publish to Github pages.
- Pull latest changes from master
- Push latest changes to master
- Run `mkdocs gh-deploy`

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
`pip install markdown-include`
* [extensions](https://pypi.org/project/pymdown-extensions/)
`pip install pymdown-extensions`
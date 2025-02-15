# STAR Informatics Website Generator

This repository hosts templates, scripts and contents for the generation of the business web site for STAR (**S**ervices & **T**ools for **A**dvanced **R**esearch) Informatics division of [Delphinai Corporation](https://delphinai.ca).

The repository uses the [`mkdocs`](https://www.mkdocs.org/) tooling to generate and manage the web site.

## Getting Started

The site uses Python (suggest 3.9 or better) and `mkdocs`. Assuming that you have python and pip installed on your machine, create a suitable virtual environment, then install the requirements (including mkdocs) as follows:

```shell
pip install -r requirements.txt
```

The repository already has core `mkdocs` configuration and layout, within which additional content may be added. 

The following `mkdocs` commands are useful for the work:

* `mkdocs serve` - Start the live-reloading docs server on your computer.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

### Project layout

The Translator `mkdocs` documentation is hierarchically structured as follows:

    mkdocs.yml         # The configuration file.
    docs/
        index.md       # the website landing page.
        license.md

with some utility resources:

        img/          # shared images
        includes/     # shared site abbreviation file, etc
        stylesheets/  # CSS styles for the site

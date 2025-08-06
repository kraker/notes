# notes

[kraker.github.io/notes](https://kraker.github.io/notes)

This is a [MkDocs](https://www.mkdocs.org/) site that hosts my
[second brain](https://github.com/kraker/second-brain) as a GitHub Pages site.
It uses the [mkdocs-terminal](https://github.com/ntno/mkdocs-terminal) theme.

## Quick start

This project uses
[git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules). Clone the
site including submodules, then change directories into the project root.

```bash
git clone --recurse-submodules https://github.com/kraker/notes.git
cd notes
```

Python virtual environments are recommended. Create a venv and source it.

```bash
python3 -m venv .env
source .env/bin/activate
```

Install Python development environment dependencies.

```bash
python3 -m pip install -r requirements-dev.txt
```

Serve the site locally.

```bash
mkdocs serve
```

Update submodules.

```bash
git submodule update --remote
```

Deploy to GitHub Pages.

```bash
mkdocs gh-deploy
```

## License

MIT

## Author

Written by Alex Kraker (@kraker)

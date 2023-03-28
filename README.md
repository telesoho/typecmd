This is a sample how to use poetry & typer to make your own cli tools.

## System requirements

[install poetry](https://python-poetry.org/docs/#installation)

## install

clone source

```sh
git clone https://github.com/telesoho/typecmd.git
```

```sh
cd typecmd
poetry install
poetry build
```

Active shell

```sh
poetry shell
```

use pipx to install the cli commands.

```sh
pipx install dist/typecmd-0.1.0.tar.gz
```

Now you can use `typecmd`.

```sh
typecmd --help
```

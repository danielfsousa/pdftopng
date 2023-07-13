# pdftopng

A PDF to PNG conversion library (based on `pdftoppm` from `poppler`)

## Fork

Fixes https://github.com/vinayak-mehta/pdftopng/issues/11

How to build: https://github.com/vinayak-mehta/pdftopng/issues/11#issuecomment-1528971792

## Installation

```
$ pip install pdftopng
```

## Usage

```
from pdftopng import pdftopng

pdftopng.convert(pdf_path="foo.pdf", png_path="foo.png")
```

```
$ pdftopng /path/to/pdf /path/to/png
```

## Testing

First, set up the development environment using:

```
$ pip install -e ".[dev]"
```

And then:

```
$ pytest --verbose --cov-report term --cov-report xml --cov=pdftopng tests/test_*.py
```

## Versioning

`pdftopng` uses [Semantic Versioning](https://semver.org/). For the available versions, see the tags on this repository.

## License

This project is licensed under GPLv2, see the [LICENSE](https://raw.githubusercontent.com/vinayak-mehta/pdftopng/master/LICENSE) file for details.

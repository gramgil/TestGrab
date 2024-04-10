# Sienna Grabber

This is a fork of https://github.com/major/yotagrabber with very specific
parameters like a MODEL, a ZIPCODE and DISTANCE.

## Installation

Install [poetry](https://python-poetry.org/docs/).

Install dependencies:

```bash
poetry install --only main
```

Install Playwright browsers:

```bash
poetry run playwright install firefox
```

Run script:

```bash
MODEL=sienna ZIPCODE=55436 DISTANCE=300 poetry run update_vehicles
```

## Flat Viewer

https://flatgithub.com/gramgil/TestGrab?filename=output%2Fsienna.csv&sha=4b37bb8a1479cf475e0e46c8b48302a4f73a4a48

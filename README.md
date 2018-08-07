# Computational Pathology Group website

[![Build Status](https://travis-ci.org/DIAGNijmegen/website-pathology.svg?branch=master)](https://travis-ci.org/DIAGNijmegen/website-pathology)

Pilot website for Computational Pathology Group.

[Online demo](https://diagnijmegen.github.io/website-pathology/)

**Components**

This project consists of three subprojects:

1. A Pelican static site.
2. A sass-powered Radboudumc theme built on top of bootstrap.
3. A above-the-fold css extraction tool.

## Static site by Pelican

### Installation

Install the requirements from `requirements.txt`:

```
pip install -r requirements.txt
```

### Usage

Run in main directory:

```
pelican content --autoreload  --output output --settings pelicanconf.py
```

This runs a local build of the site with auto-reload enabled.

### Server

A server can be ran using the built in Pelican-python server:

```
# Run in output directory
python -m pelican.server
```

Or, if available, using browser-sync:

```
# Run in repository root
browser-sync start --server output --files output
```

## Radboudumc theme

The theme requires Nodejs and npm to be built.

### Installation

```
npm --prefix pathology-theme install
```

### Usage

For testing purposes:

```
npm --prefix pathology-theme run deploy-watch
```

For a new build:

```
npm --prefix pathology-theme run deploy
```

## Above the fold

The above-the-fold script requires Nodejs and npm to be built. This script is only required for production sites as it optimizes the css delivery. It is not required for local development or testing.

### Installation

```
npm --prefix above-the-fold install
```

### Usage

```
npm --prefix above-the-fold run critical
```

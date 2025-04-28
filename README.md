# IT-Wallet Technical Specifications

[![GitHub release](https://img.shields.io/github/release/italia/eid-it-wallet-docs.svg?style=plastic)](https://github.com/italia/eid-it-wallet-docs/releases)
[![Get invited](https://slack.developers.italia.it/badge.svg)](https://slack.developers.italia.it/)
[![Docs Italia](https://docs.italia.it/media/static/projects/badges/passing.svg)](https://docs.italia.it/italia/eid-it-wallet-docs/it/master/index.html)
[![Documentation](https://img.shields.io/badge/Documentation-Docs%20Italia-blue.svg)](https://docs.italia.it/italia/eid-it-wallet-docs/)

---

## Table of Contents

- [Description](#intro)
- [Documentation](#documentation)
- [Versioning](#versioning)
- [Contributing](#how-to-contribute)
- [Authors](#authors)
- [License](#license)

## Intro

This repository hosts the sphinx project tree of IT-Wallet Technical Specifications.

> This repository may contain contents to be considered experimental until the publication of the first stable release, v1.0.

## Preview

Preview of the latest editor's copy build, corresponding to the branch `versione-corrente` can be navigated using the following link:

 - [Editor's Copy](https://italia.github.io/eid-wallet-it-docs/versione-corrente/en/)

### Preview of a branch

Preview of other branches can be navigated by adding the branch name in the webpath, as follows:

 - https://italia.github.io/eid-wallet-it-docs/$branch-name/en

### Preview of released versions

Released versions can be navigated by adding the tag in the webpath leaded by a _v_, as follows:

 - [https://italia.github.io/eid-wallet-it-docs/v1.0.0/en/](https://italia.github.io/eid-wallet-it-docs/v1.0.0/en/)
 - [https://italia.github.io/eid-wallet-it-docs/v0.9.3/en/](https://italia.github.io/eid-wallet-it-docs/v0.9.3/en/)
 - [https://italia.github.io/eid-wallet-it-docs/v0.9.2/en/](https://italia.github.io/eid-wallet-it-docs/v0.9.2/en/)
 - [https://italia.github.io/eid-wallet-it-docs/v0.9.1/en/](https://italia.github.io/eid-wallet-it-docs/v0.9.1/en/)
 - [https://italia.github.io/eid-wallet-it-docs/v0.9.0/en/](https://italia.github.io/eid-wallet-it-docs/v0.9.0/en/)
 - [https://italia.github.io/eid-wallet-it-docs/v0.8.2/en/](https://italia.github.io/eid-wallet-it-docs/v0.8.2/en/)
 - [https://italia.github.io/eid-wallet-it-docs/v0.8.1/en/](https://italia.github.io/eid-wallet-it-docs/v0.8.1/en/)
 - [https://italia.github.io/eid-wallet-it-docs/v0.8.0/en/](https://italia.github.io/eid-wallet-it-docs/v0.8.0/en/)
 - [https://italia.github.io/eid-wallet-it-docs/v0.7.1/en/](https://italia.github.io/eid-wallet-it-docs/v0.7.1/en/)
 - [https://italia.github.io/eid-wallet-it-docs/v0.7.0/en/](https://italia.github.io/eid-wallet-it-docs/v0.7.0/en/)
 - [https://italia.github.io/eid-wallet-it-docs/v0.6.0/en/](https://italia.github.io/eid-wallet-it-docs/v0.6.0/en/)
 - [https://italia.github.io/eid-wallet-it-docs/v0.5.0/en/](https://italia.github.io/eid-wallet-it-docs/v0.5.0/en/)
 - [https://italia.github.io/eid-wallet-it-docs/v0.4.1/en/](https://italia.github.io/eid-wallet-it-docs/v0.4.1/en/)

## Build

HTML
````
pip install -r requirements-dev.txt

sphinx-build -b html -d html/en/doctrees docs/en/ html/en
````

ODT
````
sudo apt install pandoc
sphinx-build -b singlehtml docs/en/  html/
cd html
pandoc -o eid-it-wallet-docs.odt index.html
````

## Versioning

This project adheres to the [*Semantic
Versioning*](https://semver.org/) model.

Furthermore, this project uses the git *branches* and *tags* in the following way:
* the branch `versione-corrente` contains the last stable version of the standard;
* The [release page](https://github.com/italia/eid-wallet-it-docs/releases) of
  GitHub contains all the released versions of the specifications. For the sake of coherence, the *releases* are made according to the tag names.

Each time a release is created or edited, a preview is built based on the tag the release refers to. See [the preview section](preview-of-released-versions) for more.

## How to contribute

Don't hesitate to submit [Pull Requests or raise Issues](CONTRIBUTING.md) if you encounter any problems.


## License

The project is covered by a [CC-0](LICENSE) license.

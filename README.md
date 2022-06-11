# Application for Crystallography.io

[![Build Status][github-actions-status]][github-actions-url]
[![Github Tag][github-tag-image]][github-tag-url]
[![Github Tag][github-license-image]][github-license-url]

## Install Application

- Linux (require [snapcraft](https://snapcraft.io/) installed)

```bash
snap install --edge structure-search
```

- Windows
Download and install latest version from [here](https://github.com/chemistry/app.crystallography.io/releases)

- Mac OS
Download and install latest version from [here](https://github.com/chemistry/app.crystallography.io/releases)

## Starting Development

Start the app in the `dev` environment:

```bash
npm start
```

## Packaging for Production

To package apps for the local platform:

```bash
npm run package
```

## How to release application

- Release: ``git tag v0.0.25 &&  git push --tags``
- Clean: ``git tag -d v0.0.25 && git push --delete origin v0.0.25``

## Author

[Volodymyr Vreshch](https://vreshch.com)

## License

  This project is licensed under the MIT license, Copyright (c) 2020 Volodymyr Vreshch.
  For more information see [LICENSE.md](https://github.com/chemistry/app.crystallography.io/blob/master/LICENSE.md).


[github-actions-status]: https://github.com/chemistry/app.crystallography.io/workflows/Test/badge.svg
[github-actions-url]: https://github.com/chemistry/app.crystallography.io/actions
[github-tag-image]: https://img.shields.io/github/v/tag/chemistry/crystallography.io.svg?label=version
[github-tag-url]: https://github.com/chemistry/app.crystallography.io/releases/latest
[github-license-image]: https://img.shields.io/github/license/chemistry/crystallography.io
[github-license-url]: https://github.com/chemistry/app.crystallography.io/blob/master/LICENSE











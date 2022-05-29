# Application for Crystallography.io

[![Build Status][github-actions-status]][github-actions-url]
[![Github Tag][github-tag-image]][github-tag-url]

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

* Release: ``git tag v0.0.25 &&  git push --tags``
* Clean: ``git tag -d v0.0.25 && git push --delete origin v0.0.25``

## Author

[Volodymyr Vreshch](https://vreshch.com)

## License

  This project is licensed under the MIT license, Copyright (c) 2020 Volodymyr Vreshch.
  For more information see [LICENSE.md](https://github.com/chemistry/app.crystallography.io/blob/master/LICENSE.md).

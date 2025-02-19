# gh-prx

opinionated branch-pr-push workflow

[![license][license-img]][license-url]
[![release][release-img]][release-url]

## Installation

``` shell
gh extension install ahmadnassri/gh-prx
```

### Upgrading

``` shell
gh extension upgrade prx
```

## Usage

> [!WARNING]
> stage your changes first!

``` shell
gh prx $branch $message
```

> 1.  stash any current changes
> 2.  create new branch with the name \$branch
> 3.  stage all changed files
> 4.  commit with the \$message
> 5.  make pull request
> 6.  open pull request in the browser

> [!TIP]
> `message` is optional, standard commit message editor will trigger if not provided

---

> Author: [Ahmad Nassri](https://www.ahmadnassri.com/)

[license-url]: LICENSE
[license-img]: https://badgen.net/github/license/ahmadnassri/gh-prx
[release-url]: https://github.com/ahmadnassri/gh-prx/releases
[release-img]: https://badgen.net/github/release/ahmadnassri/gh-prx

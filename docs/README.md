## Installation

```shell
gh extension install ahmadnassri/gh-prx
```

### Upgrading

```shell
gh extension upgrade prx
```

## Usage

> [!WARNING]
> stage your changes first!


```shell
gh prx $branch $message
```
> 1. stash any current changes
> 1. create new branch with the name $branch
> 1. stage all changed files
> 1. commit with the $message
> 1. make pull request
> 1. open pull request in the browser

> [!TIP]
> `message` is optional, standard commit message editor will trigger if not provided

# Go hooks for pre-commit

[Go](https://golang.org) tools package for [pre-commit](http://pre-commit.com).

## Using go tools with pre-commit

```yaml
-   repo: git://github.com/doublify/pre-commit-go
    sha: ''
    hooks:
    -   id: fmt
    -   id: vet
```

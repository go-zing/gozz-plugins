<p align="center">
  <a href="https://github.com/go-zing/gozz" target="_blank">
    <img src="https://raw.githubusercontent.com/go-zing/gozz-doc/main/docs/.vuepress/public/logo.png" alt="logo">
  </a>
</p>

## Introduction

### Documentation

[English](https://go-zing.github.io/gozz) | [简体中文](https://go-zing.github.io/gozz/zh)

### Why they independent

In [Golang plugin](https://pkg.go.dev/plugin),
module with same name loaded should be compiled in same version.

So we have great reason to reduce core dependencies of `gozz` in `go.mod` then
provide greater independence.
Also, We separate some official plugins as extension from main repo,
and users are free to choose to install it themselves.

The project would provide [plugins](./plugins) and [orm-schema-drivers](ormdrivers).

## Install

```shell
gozz install https://github.com/go-zing/gozz-plugins -f [path to plugins]
```

## Showcase

- [Gozz-Core](https://github.com/go-zing/gozz-core)
- [Gozz-Doc](https://github.com/go-zing/gozz-doc)

## License

[Apache-2.0](https://github.com/go-zing/gozz/blob/main/LICENSE)
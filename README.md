# Problem statement
runs npm install

# Example usage

> note: in examples, VERSION represents a version of the npm.install pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/npm.install#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/npm.install#VERSION
```

## compose

```yaml
op:
  pkg: { ref: github.com/opspec-pkgs/npm.install#VERSION }
  inputs: 
    srcDir:
    registry:
```

# Support

join us on [![Slack](https://opspec-slackin.herokuapp.com/badge.svg)](https://opspec-slackin.herokuapp.com/)
or [open an issue](https://github.com/opspec-pkgs/npm.install/issues)

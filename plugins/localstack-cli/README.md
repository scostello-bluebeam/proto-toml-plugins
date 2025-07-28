# localstack-cli plugin

[localstack-cli](https://github.com/localstack/localstack-cli) plugin for [proto](https://github.com/moonrepo/proto).

## Installation

This is a community plugin and is thus not built-in to proto. To use it, first either add it to your global or project-based `.prototools` by running:

### Global install

```shell
proto plugin add localstack-cli "source:https://raw.githubusercontent.com/scostello-bluebeam/proto-toml-plugins/main/localstack-cli/plugin.toml" --global
proto install localstack-cli
```

### Per-project install

```shell
proto plugin add localstack-cli "source:https://raw.githubusercontent.com/scostello-bluebeam/proto-toml-plugins/main/localstack-cli/plugin.toml"
proto pin localstack-cli latest --resolve
```

# terramate plugin

[terramate](https://github.com/terramate-io/terramate) plugin for [proto](https://github.com/moonrepo/proto).

## Installation

This is a community plugin and is thus not built-in to proto. To use it, first either add it to your global or project-based `.prototools` by running:

### Global install

```shell
proto plugin add terramate "source:https://raw.githubusercontent.com/scostello-bluebeam/proto-toml-plugins/main/terramate/plugin.toml" --global
proto install terramate
```

### Per-project install

```shell
proto plugin add terramate "source:https://raw.githubusercontent.com/scostello-bluebeam/proto-toml-plugins/main/terramate/plugin.toml"
proto pin terramate latest --resolve
```

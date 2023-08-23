# TDD Boilerplate Core

[![License: MIT][license_badge]][license_link]

A TDD Boilerplate core project for flutter app created with [Mason CLI][mason_cli]

## Getting Started 🚀

Make sure to setup mason before proceed or get started here [Mason CLI][mason_cli]

## Install brick

Run ``mason init` or manually create mason.yaml file to setup mason in current workspace, then add each tdd_boilerplate brick to mason via.

```sh
# Core
$ mason add tdd_boilerplate_core --path bricks/tdd_boilerplate_core

# Model
$ mason add tdd_boilerplate_model --path bricks/tdd_boilerplate_model

# Usecase
$ mason add tdd_boilerplate_usecases --path bricks/tdd_boilerplate_usecases

# Repository
$ mason add tdd_boilerplate_repository --path bricks/tdd_boilerplate_repository
```

or install globally via

```sh
# Core
$ mason add -g tdd_boilerplate_core --path bricks/tdd_boilerplate_core

# Model
$ mason add -g tdd_boilerplate_model --path bricks/tdd_boilerplate_model

# Usecase
$ mason add -g tdd_boilerplate_usecases --path bricks/tdd_boilerplate_usecases

# Repository
$ mason add -g tdd_boilerplate_repository --path bricks/tdd_boilerplate_repository
```

## Verify brick

Verify that the brick has been successfully added by running mason ls:

```sh

$ mason ls

# OR

$ mason ls -g

```

## Generate code via:

```sh
# Core
$ mason make tdd_boilerplate_core

# Model
$ mason make tdd_boilerplate_model

# Usecase
$ mason make tdd_boilerplate_usecases

# Repository
$ mason make tdd_boilerplate_usecases
```

## Generate mason bundle via:

```sh
# Core
$ mason bundle "./bricks/tdd_boilerplate_core" --type dart --output-dir "lib/template/tdd_boilerplate_core"

# Model
$ mason bundle "./bricks/tdd_boilerplate_model" --type dart --output-dir "lib/template/tdd_boilerplate_model"

# Usecase
$ mason bundle "./bricks/tdd_boilerplate_usecases" --type dart --output-dir "lib/template/tdd_boilerplate_usecases"

# Repository
$ mason bundle "./bricks/tdd_boilerplate_usecases" --type dart --output-dir "lib/template/tdd_boilerplate_usecases"
```

[tdd_boilerplate_cli]: https://github.com/Mujhtech/tdd_boilerplate_cli
[mason_cli]: https://docs.brickhub.dev/installing
[license_badge]: https://img.shields.io/badge/license-MIT-blue.svg
[license_link]: https://opensource.org/licenses/MIT

# bash-qa

_**WARNING: This is prototype software not currently intended for public use.**_

## Usage

```bash
npm i --save-dev @liquid-labs/bash-qa
# create Makefile.bash-qa and updates/creates Makefile
$(npm bin)/bash-qa-init
make test
```

## Overview

Creates a Docker container and automatically mounts and runs `bats`<!-- TODO: link --> tests.

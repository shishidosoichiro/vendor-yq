# Node version manger

simple.

## Commands

- `./bin/install [version]`: install specific version.
- `./bin/home [version]`: return home directory path of specific version.
- `./bin/bin [version]`: return bin directory paths of specific version.
- `./bin/installed`: list installed versions.
- `./bin/versions`: list versions that can be installed.
- `eval $(./bin/env [version])`: set up the environment of specific version.


## Requirements

- `curl`: required for `./bin/install` and  `./bin/versions`
- `tar`: required for `./bin/install`
- `xz`: required for `./bin/install`


```sh
apt-get update
apt-get install -y curl xz-utils
```

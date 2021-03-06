[![CircleCI](https://circleci.com/gh/devatherock/drone-yaml-validator.svg?style=svg)](https://circleci.com/gh/devatherock/drone-yaml-validator)
[![Version](https://img.shields.io/docker/v/devatherock/vela-yaml-validator?sort=semver)](https://hub.docker.com/r/devatherock/vela-yaml-validator/)
[![Coverage Status](https://coveralls.io/repos/github/devatherock/drone-yaml-validator/badge.svg?branch=master)](https://coveralls.io/github/devatherock/drone-yaml-validator?branch=master)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/eee25e47d4104a20894d2a0f8f35d2fd)](https://www.codacy.com/gh/devatherock/drone-yaml-validator/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=devatherock/drone-yaml-validator&amp;utm_campaign=Badge_Grade)
[![Docker Pulls - Drone](https://img.shields.io/docker/pulls/devatherock/drone-yaml-validator.svg)](https://hub.docker.com/r/devatherock/drone-yaml-validator/)
[![Docker Image Size](https://img.shields.io/docker/image-size/devatherock/vela-yaml-validator.svg?sort=date)](https://hub.docker.com/r/devatherock/vela-yaml-validator/)
[![Docker Image Layers](https://img.shields.io/microbadger/layers/devatherock/vela-yaml-validator.svg)](https://microbadger.com/images/devatherock/vela-yaml-validator)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
# yaml-validator
CI plugin to validate yaml files

## Usage
### Docker

```shell script
docker run --rm \
  -e PLUGIN_DEBUG=true \
  -v path/to/yamls:/work \
  -w=/work \
  devatherock/drone-yaml-validator:latest
```

### CI
Please refer [docs](DOCS.md)

## Tests
To test the latest plugin images, run the below command
```shell
make functional-test
```

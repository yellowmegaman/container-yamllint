# container-yamllint <p><a href="https://github.com/yellowmegaman/container-yamllint/actions"><img src="https://github.com/yellowmegaman/container-yamllint/workflows/container/badge.svg" alt="Build Status"></a><a href="https://hub.docker.com/r/yellowmegaman/container-yamllint"></p><p><img src="https://img.shields.io/docker/pulls/yellowmegaman/container-yamllint?style=flat-square" alt="Docker pulls"></a></p>

Alpine yamllint image

##### Example
```
docker run --rm -ti -v $PWD:/test yellowmegaman/container-yamllint:latest /test/file.yml
docker run --rm -ti -v $PWD:/test quay.io/yellowmegaman/container-yamllint:latest /test/file.yml
```

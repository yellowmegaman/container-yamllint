# container-yamllint [![Build Status](https://cloud.drone.io/api/badges/yellowmegaman/container-yamllint/status.svg)](https://cloud.drone.io/yellowmegaman/container-yamllint)

Alpine yamllint image

##### Example
```
docker run --rm -ti -v $PWD:/test yellowmegaman/container-yamllint:latest /test/file.yml
docker run --rm -ti -v $PWD:/test quay.io/yellowmegaman/container-yamllint:latest /test/file.yml
```

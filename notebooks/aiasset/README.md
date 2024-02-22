# README
1. Docker installation is required for this module.
2. Run below command after done with the docker installation.

```bash
  docker run --user root -it --privileged --cap-add=ALL -d -v /dev:/dev -v /lib/modules:/lib/modules openvino/ubuntu22_runtime bash

  docker compose up --cap-add=ALL -d
```

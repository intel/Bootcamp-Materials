```bash
  docker run --user root -it --privileged --cap-add=ALL -d -v /dev:/dev -v /lib/modules:/lib/modules openvino/ubuntu22_runtime bash

  docker compose up --cap-add=ALL -d
```
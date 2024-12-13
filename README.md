# zephyr-modules

## Installation

Fetch binary blobs for radio on ESP32

```
west blobs fetch hal_espressif
```


Configure path for build-tool. Alternative to exporting zephyr config, but this makes a mess in home dir (~/.cmake)

```export CMAKE_PREFIX_PATH=./sdk/zephyr/share/zephyr-package/cmake```

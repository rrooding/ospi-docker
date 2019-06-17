# Docker OpenSprinkler Pi (OSPi)

This Docker image allows you to run the [OpenSprinkler firmware](https://opensprinkler.com/product/opensprinkler-pi/) as a container on your Raspberry Pi.

## Usage

```bash
docker run \
  --privileged \
  --network=host \
  --restart always \
  -d \
  rrooding/ospi:latest
```
---
description: Latest software for Ronin nodes and bridge operator.
---

# Latest versions

This page describes how to get the latest version of the node's software.

## Ronin node

Every Ronin node release is published on
[GitHub](https://github.com/axieinfinity/ronin/releases).

### Mainnet

To find the Docker image for each mainnet release, visit the following:

* [Docker Hub](https://hub.docker.com/r/axieinfinity/ronin-mainnet/tags)
* [GitHub Container Registry](https://github.com/axieinfinity/ronin/pkgs/container/ronin)

To download the latest image for your node, follow these steps:

1. In the `.env` file, set `NODE_IMAGE` to the following:

    ```
    ghcr.io/axieinfinity/ronin:v2.5.2-9bf4895
    ```

2. Save the changes.
3. Run `docker-compose up -d`.

### Saigon testnet

To find the Docker image for each testnet release, visit
[Docker Hub](https://hub.docker.com/r/axieinfinity/ronin-testnet/tags).

To download the latest image for your node, follow these steps:

1. In the `.env` file, set `NODE_IMAGE` to the following:

    ```
    axieinfinity/ronin-testnet:v2.5.0-4abacb213
    ```

2. Save the changes.
3. Run `docker-compose up -d`.

## Bridge operator

Every bridge release is published on
[GitHub](https://github.com/axieinfinity/bridge-v2/releases). To find the Docker
image for each release, visit
[Docker Hub](https://hub.docker.com/r/axieinfinity/bridge/tags).

To download the latest image, follow these steps:

1. In the `.env` file, set `BRIDGE_IMAGE` to the following:

    ```
    ghcr.io/axieinfinity/bridge:v0.2.4-70568ab
    ```

2. Save the changes.
3. Run `docker-compose up -d`.

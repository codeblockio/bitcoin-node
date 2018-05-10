# Running a Bitcoin full node

This is the configuration for the Bitcoin full node running on CodeBlock infrastructure.

It is running the Bitcoin Core client (v0.16.0)

# Docker Image

The container image was built from [here](https://github.com/ruimarinho/docker-bitcoin-core).

It is highly recommended to build your image from scratch while properly verifying the signatures
for each binary that you are including in the image.

# Resource Requirements

Specify the appropriate resources requirements as specified [here](https://bitcoin.org/en/bitcoin-core/features/requirements)

# Future

- Add [lnd](https://github.com/lightningnetwork/lnd) container (Lightning network)

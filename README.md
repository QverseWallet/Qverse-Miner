# Qverse Miner

High-performance GPU miner for Qubitcoin (QBTC) network.

## Requirements

- NVIDIA GPU (RTX 20/30/40 series)
- CUDA drivers installed
- Linux x86_64

## Download

Download the latest release from [Releases](https://github.com/QverseWallet/Qverse-Miner/releases)

## Quick Start

```bash
# Extract
tar -xzvf Qverse-Miner-Linux-0.1.tar.gz

# Run
chmod +x qverse_miner start_mining.sh
./start_mining.sh
```

## Options

| Option | Description |
|--------|-------------|
| `--algo` | Mining algorithm (qhash) |
| `--url` | Pool address |
| `--user` | Wallet address.WorkerName |
| `--pass` | Pool password (x) |

## Supported GPUs

| Series | Models |
|--------|--------|
| RTX 40 | 4090, 4080, 4070, 4060 |
| RTX 30 | 3090, 3080, 3070, 3060 |
| RTX 20 | 2080, 2070, 2060 |

## Pool

In version 0.1, the only available pool is the official Qverse pool:

```
stratum+tcp://stratum.qverse.pro:25565
```

## Dev Fee

**0% dev fee** - This is a beta version, no fees are charged.

## Support

For issues and questions, open an issue on GitHub.


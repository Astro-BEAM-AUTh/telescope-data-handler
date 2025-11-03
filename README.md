<!-- omit in toc -->
# Telescope Data Handler

![Python](https://img.shields.io/badge/python-3.13-blue.svg)
[![CI](https://github.com/Astro-BEAM-AUTh/telescope-data-handler/workflows/CI/badge.svg)](https://github.com/Astro-BEAM-AUTh/telescope-data-handler/actions)
[![Code style: ruff](https://img.shields.io/badge/code%20style-ruff-000000.svg)](https://github.com/astral-sh/ruff)

<!-- omit in toc -->
## Table of Contents
- [Overview](#overview)
- [How to Run](#how-to-run)
- [Development](#development)
- [Contributing](#contributing)

## Overview
This project is responsible for handling the data flow from the telescope's SDR system to the cloud infrastructure.
It manages the following tasks:
- Receiving radio signal data from the SDR.
- Processing and buffering the data locally.
- Communicating with the Message Broker (Kafka?) to send and receive commands and telemetry.
- Uploading processed data to the cloud storage or database for further analysis.

## How to Run
To run the data handler, execute the following command:

```bash
uv run data-handler
```

## Development
To install the development dependencies, run:

```bash
uv sync --dev
```

## Contributing

Contributions are welcome!
If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

Please read our [Contributing Guidelines](https://github.com/Astro-BEAM-AUTh/telescope-data-handler?tab=contributing-ov-file) for more details.
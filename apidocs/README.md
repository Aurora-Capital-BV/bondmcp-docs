# BondMCP CLI Quickstart

This guide explains how to install the BondMCP command line interface and authenticate against the public API.

## Installation

You can install the CLI from PyPI:

```bash
pip install bondmcp-cli
```

Alternatively, clone this repository and install it in editable mode:

```bash
pip install -e .
```

## Configuration

Before running any commands, set the environment variable `BONDMCP_PUBLIC_API_KEY` with your API key. You may also override the API base URL by setting `BONDMCP_PUBLIC_API_BASE_URL`.

API keys are provided to registered users. Visit [api.bondmcp.com](https://api.bondmcp.com) to create an account and obtain your key.

## Usage Example

Once installed and configured, you can ask for the latest health insights:

```bash
bondmcp-cli ask "What are the latest health insights?"
```

## OpenAPI Specification

The complete OpenAPI specification for the BondMCP service is available at <https://api.bondmcp.com/openapi.json>.

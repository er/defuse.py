# Quickstart

## Install

```bash
pip install defuse-py
```

## Usage

```python
import asyncio
from defuse import IntentsClient

async def main():
    async with IntentsClient() as client:
        tokens = await client.get_tokens()
        print(tokens)

asyncio.run(main())
```

See the [API reference](api/client.md) for the full surface.

# discordeasy

**discordeasy** is a Python package designed to make Discord bot development easier, faster, and more efficient. It provides built-in commands, utilities for creating application command trees, and tools to simplify and speed up bot execution.

## Features

- 🚀 Simple and fast bot setup
- 🧩 Built-in commands and utilities
- 🌳 Easy application command tree creation
- ⚡ Optimised for performance and simplicity

## Installation

```sh
pip install discordeasy
```

## Quick Start

```python
import discordeasy

bot = discordeasy.Bot(command_prefix="!")

@bot.command()
async def hello(ctx):
    await ctx.send("Hello, world!")

bot.run("YOUR_BOT_TOKEN")
```

## Documentation

For more details, see the [Wiki](https://github.com/Virtosync/discordeasy/wiki) or the [examples](examples/) directory.

## Requirements

- Python 3.8+
- discord.py 2.0.0 or newer

## Contributing

Contributions are not welcome until further notice.

## License

MIT License. See [LICENSE](LICENSE) for details.

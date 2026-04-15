# Claude Creative Tools

A Claude Code plugin marketplace hosting creative plugins for AI image generation and video direction.

## What is this?

This is a **Claude Code plugin marketplace** - a repository that hosts multiple plugins as a unified catalog. Users can:
- Add the entire marketplace once with `/plugin marketplace add`
- Install individual plugins they need with `/plugin install`
- Each plugin can be installed independently without others

## Available Plugins

| Plugin | Category | Description |
|--------|----------|-------------|
| **openrouter-images-skill** | Creative | AI image generation via OpenRouter. Text-to-image, image editing, batch processing. |
| **ai-director** | Creative | Master framework for AI image generation, video direction, and storytelling. |
| **thumbnail-creator** | Creative | YouTube thumbnail creative director with 33+ techniques. |

## Installation

### Add the Marketplace (One-time)

```bash
/plugin marketplace add ddm21/claude-creative-tools
```

### Install Individual Plugins

Install the plugins you need:

```bash
# Single plugin
/plugin install openrouter-images-skill@claude-creative-tools

# Multiple plugins
/plugin install openrouter-images-skill@claude-creative-tools
/plugin install ai-director@claude-creative-tools
/plugin install thumbnail-creator@claude-creative-tools
```

### View Available Plugins

```bash
/plugin list
```

## Using Plugins

Once installed, each plugin's skills become available as slash commands:

```bash
/openrouter-images  # AI image generation
/ai-director        # AI image generation, video direction, and storytelling
/thumbnail-creator  # YouTube thumbnail creation
```

## License

MIT
# MeiGen Docs

Documentation for [MeiGen](https://www.meigen.ai) — AI-powered image generation platform.

**Live site:** [docs.meigen.ai](https://docs.meigen.ai)

Built with [Mintlify](https://mintlify.com).

## Local Development

```bash
# Install CLI
npm i -g mint

# Start dev server
mint dev
```

## Structure

```
├── index.mdx                    # Home page
├── quickstart.mdx               # Quick start guide
├── features/
│   ├── gallery.mdx              # Gallery features
│   ├── generate.mdx             # Image generation
│   ├── prompt-enhance.mdx       # Prompt enhancement
│   └── models.mdx               # Model comparison
├── api-reference/
│   ├── introduction.mdx         # API overview
│   └── endpoint/
│       ├── generate.mdx         # POST /api/generate/v2
│       ├── models.mdx           # GET /api/models
│       ├── images.mdx           # GET /api/images/:id
│       └── tokens.mdx           # Token management
└── mcp/
    ├── overview.mdx             # MCP plugin intro
    └── setup.mdx                # Installation guide
```

# MeiGen Docs

Documentation for [MeiGen](https://www.meigen.ai) — AI image & video generation platform.

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
├── docs.json                    # Mintlify site config + navigation (en / zh)
└── en/ & zh/                    # Bilingual mirrors — keep both in sync
    ├── quickstart.mdx           # Quick start guide
    ├── account.mdx              # Account & data deletion
    ├── features/
    │   ├── gallery.mdx          # Gallery features
    │   ├── generate.mdx         # Image & video generation
    │   └── models.mdx           # Model comparison
    ├── mcp/
    │   ├── overview.mdx         # MCP plugin intro
    │   ├── setup.mdx            # Installation guide
    │   └── comfyui.mdx          # ComfyUI integration
    └── api-reference/
        ├── introduction.mdx     # API overview
        └── endpoint/
            ├── generate.mdx     # POST /api/generate/v2
            ├── models.mdx       # GET /api/models
            ├── images.mdx       # GET /api/images/:id
            └── tokens.mdx       # Token management
```

Every page exists in both `en/` and `zh/`. When editing content, update both mirrors in the same change.

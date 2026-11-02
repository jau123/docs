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
    │   └── comfyui.mdx          # 3.0 migration (legacy URL)
    └── api-reference/
        ├── introduction.mdx     # API overview
        └── endpoint/
            ├── generate.mdx     # POST /api/generate/v2
            ├── models.mdx       # GET /api/models
            ├── images.mdx       # GET /api/images/:id
            └── tokens.mdx       # Token management
```

Every page exists in both `en/` and `zh/`. When editing content, update both mirrors in the same change.

## Public documentation

Document what readers can do, what they need to supply, what they will be charged, and how to recover from an error. For API and MCP guides, show the public MeiGen endpoint, parameters and returned fields. Use illustrative media URLs and tell readers which returned URL to use. Keep service routing, storage layouts, internal parameters and processing logic out of published text, examples, comments and links. Apply the same check to both languages. Keep setup steps, model pricing and migration notes on their respective pages. Link to them when another guide needs that information.

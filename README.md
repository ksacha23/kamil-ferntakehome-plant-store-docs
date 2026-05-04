# Plant Store Documentation

Welcome to the Plant Store documentation site, built with [Fern](https://buildwithfern.com).

## Getting Started

### Prerequisites

Install the Fern CLI:

```bash
npm install -g fern-api
```

### Validate the docs

To check the configuration is valid before publishing:

```bash
fern check
```

### Publish the docs

To publish the site live:

```bash
fern generate --docs
```

Your documentation will be available at `kamil-sacha-demo.docs.buildwithfern.com`.

## Project Structure

```
fern/
├── docs.yml                  # Main configuration (nav, colors, fonts, logo)
├── fern.config.json          # Organization name and Fern version
├── openapi/
│   ├── api.yml               # OpenAPI spec for the Plant Store API
│   └── ai_examples_override.yml  # Custom code samples and examples
└── docs/
    ├── assets/               # Images, fonts, CSS
    └── pages/
        └── landingpage.mdx   # Home page content
```

## Editing Content

- **Landing page**: edit `fern/docs/pages/landingpage.mdx`
- **API spec**: edit `fern/openapi/api.yml`
- **Styling & navigation**: edit `fern/docs.yml`
- **Custom CSS**: edit `fern/docs/assets/main.css`

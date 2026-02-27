# Thottathil Shopify Theme

A custom Shopify theme built from scratch.

## Folder Structure

```
thottathil-build-shopify-theme/
├── assets/          # CSS, JS, images, fonts
├── config/          # Theme settings (settings_schema.json, settings_data.json)
├── layout/          # Theme layouts (theme.liquid)
├── locales/         # Translation files
├── sections/        # Shopify sections
├── snippets/        # Reusable Liquid snippets
└── templates/       # Page templates
    └── customers/   # Customer-specific templates
```

## Development

Install [Shopify CLI](https://shopify.dev/docs/themes/tools/cli) to develop and preview locally:

```bash
npm install -g @shopify/cli @shopify/theme
shopify theme dev --store your-store.myshopify.com
```

## Deployment

```bash
shopify theme push --store your-store.myshopify.com
```

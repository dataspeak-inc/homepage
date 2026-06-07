# DataSpeak static site

This directory is generated from the WordPress theme templates in `wp_data/wp-content/themes/dataspeak-theme`.

## Pages

- `/`
- `/products/lightning-ai/`
- `/products/agent-madang/`
- `/products/sql-genius/`
- `/products/rapid-rag/`
- `/contact-us/`

## Local preview

```sh
python3 -m http.server 9000 --directory static-site
```

Then open http://localhost:9000.

## Rebuild

```sh
node tools/build-static-site.mjs
```

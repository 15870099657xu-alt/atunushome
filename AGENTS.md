# Shopify Theme Rules

This repository is a Shopify Online Store 2.0 theme.

## Required workflow

- Inspect existing code before editing.
- Work only on the current feature branch.
- Do not push or publish themes.
- Run `shopify theme check` after code changes.
- Keep changes limited to the requested task.

## Shopify constraints

- Preserve existing section setting IDs.
- Preserve existing block type names.
- Do not modify `config/settings_data.json` unless explicitly requested.
- Do not rewrite unrelated `templates/*.json` files.
- Keep section schema valid JSON.
- Use translation keys for customer-facing text.
- Do not hardcode store domains, product IDs, collection IDs, variant IDs, or image URLs.
- Preserve Shopify Theme Editor compatibility.
- Prefer sections, blocks, snippets, metafields, and theme settings.
- Reuse existing CSS classes and design tokens.
- Do not introduce third-party libraries without approval.

## Validation

Before finishing:

1. Run `shopify theme check`.
2. Review `git diff`.
3. Report all changed files.
4. Mention any migration or compatibility risk.
5. Do not create a commit unless explicitly requested.
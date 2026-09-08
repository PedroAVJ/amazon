# Repository guidance

- This repository is the canonical source for the `amazon` plugin.
- Keep the Codex and Claude manifests synchronized when both are present. The Claude plugin is intentionally absent for Codex-only plugins.
- Marketplace catalogs reference this repository; do not duplicate runtime behavior back into a marketplace repository.
- Keep credentials, payment details, addresses, and secret values out of Git. Private product constraints and purchase history must stay outside Git; `preferences/README.md` documents optional local configuration, which never authorizes cart or checkout actions.
- Preserve stable command names, service labels, and credential identifiers across releases.
- Bump the plugin version for released behavior changes and run `npm test` before publishing.

# AGENTS.md

This repository is a documentation portal template for [Revdoku](https://revdoku.com): SDK / library docs. Install, quickstart, language tabs and changelog.
Revdoku publishes it as a docs site (Mintlify-compatible) with search, an Ask box, an MCP server for AI agents and `llms.txt`.

## How it goes live

- Push to GitHub. Revdoku syncs the repository (Settings → GitHub in the dashboard) and publishes the site again.
- Revdoku only reads the repository. Change the files here, on GitHub.
- This file is for you, the agent. Revdoku keeps it in the project but never publishes it. The same holds for `CLAUDE.md`, `GEMINI.md`, dotfiles, `.env` files and lockfiles.

## Files

- `docs.json` holds the site name, colors and the navigation. A page that `navigation` does not list stays out of the sidebar. List pages by path without the extension.
- Pages are `.mdx` or `.md` files. Start each with front matter: `title` and `description`.
- `quickstart.mdx` shows install and a first call, with one tab per language (`Tabs` or `CodeGroup`).
- `changelog.mdx` has one entry per release, newest first. Add reference pages for the public API of the library.

## Rules

1. Replace the sample name "Acme" and the sample text with the real product. Keep the structure.
2. Keep `docs.json` in step with the pages you add, rename or delete. Check every link.
3. This repository publishes: never put secrets, tokens or private data in it.
4. Page format and components (`Callout`, `Card`, `CardGroup`, `Steps`, `Tabs`, `CodeGroup`, `Accordion`): https://docs.revdoku.com/docs-sites.md
5. About Revdoku: https://revdoku.com. Docs: https://docs.revdoku.com.

<p align="center">
  <a href="https://github.com/linkoutapp/brand" aria-label="Linkout brand assets">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/linkoutapp/brand/main/scraper-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/linkoutapp/brand/main/scraper-transparent.svg">
      <img src="https://raw.githubusercontent.com/linkoutapp/brand/main/scraper-transparent.svg" alt="Linkout" width="128">
    </picture>
  </a>
</p>

# Linkout

LinkedIn tools that run through your own visible Chrome session.

The Node.js package includes profile and activity reads, plus opt-in actions. The MCP interface exposes read-only tools. You sign in to LinkedIn yourself; the runtime uses that local browser session.

[Website](https://www.linkout.space/) · [Setup and API guides](https://github.com/linkoutapp/docs)

## Repositories

| Repository | Purpose |
| --- | --- |
| [linkout-scraper](https://github.com/linkoutapp/linkout-scraper) | Node.js package and read-only MCP server |
| [docs](https://github.com/linkoutapp/docs) | Setup, API, and operating guides |
| [docker-image](https://github.com/linkoutapp/docker-image) | Container packaging and its current platform limitations |
| [li_at](https://github.com/linkoutapp/li_at) | Chrome extension for viewing your LinkedIn session cookie |
| [brand](https://github.com/linkoutapp/brand) | Logos and SVG artwork |
| [.github](https://github.com/linkoutapp/.github) | This organization profile |

## Before using Linkout

Read the scraper's setup and security notes. Keep passwords, cookies, and browser profiles private. LinkedIn can restrict automated activity; local execution and daily limits do not remove that risk.

Maintained by [Sai-Adarsh](https://github.com/Sai-Adarsh).

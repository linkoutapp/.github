<p align="center">
  <a href="https://github.com/linkoutapp/brand" aria-label="Linkout brand">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/linkoutapp/brand/main/scraper-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/linkoutapp/brand/main/scraper-transparent.svg">
      <img alt="Linkout" src="https://raw.githubusercontent.com/linkoutapp/brand/main/scraper-transparent.svg" width="160">
    </picture>
  </a>
</p>

# Linkout

Local LinkedIn tooling for signed-in desktop Chrome.

## Repositories

- `linkout-scraper` — Node.js package and read-only MCP server for LinkedIn profile, connection, message, post, reaction, and comment reads.
- `docker-image` — Docker package wrapper for the Linkout read-only MCP server.
- `brand` — Linkout artwork and public brand assets.

## Runtime position

Linkout keeps authentication on the user device. It does not submit LinkedIn credentials, copy `.env` files, set cookies, run headless LinkedIn automation, use proxies, or ship Sales Nav scraping.

## Maintainer

Maintained by [Sai-Adarsh](https://github.com/Sai-Adarsh).

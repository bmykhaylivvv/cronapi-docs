# CronAPI documentation project

## About this project

- Documentation site for [CronAPI](https://cronapi.dev) built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "cron" (lowercase) for recurring scheduled webhooks
- Use "job" for one-time delayed webhooks
- Use "run" for a single webhook execution record
- Use "API key" (not "token" or "secret") when referring to authentication credentials
- Use "webhook" when referring to the HTTP request CronAPI sends to the user's URL
- Use "fire" or "trigger" when describing webhook execution

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Always include cURL, Node.js, and Python examples in `<CodeGroup>` blocks for API endpoints
- Use realistic but clearly fake data in examples (UUIDs, example.com URLs)

## Content boundaries

- Document only the public REST API and dashboard features
- Do not document internal infrastructure, Supabase schema details, or deployment configuration
- Do not document features that are not yet implemented (e.g., retry logic, rate limiting)

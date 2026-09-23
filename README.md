# Anton Standrik

I'm a Lead Software Engineer at Yandex. I work on YDB's web interfaces and developer tooling, mostly in TypeScript, and I'm one of the code owners of [ydb-embedded-ui](https://github.com/ydb-platform/ydb-embedded-ui), the web UI built into YDB.

In open source, I build tools for vector search, local database operations, CI, and coding agents. I spend a lot of time on the boring parts too: tests, reproducible setups, failure modes, and permission boundaries.

## Selected work

* **[ydb-qdrant](https://github.com/astandrik/ydb-qdrant):** a Qdrant-compatible vector search service and TypeScript library backed by YDB.
* **[local-ydb-toolkit](https://github.com/astandrik/local-ydb-toolkit):** a Codex skill and MCP server for operating Docker-based local YDB deployments.
* **[my_instructions](https://github.com/astandrik/my_instructions):** project-neutral instructions for coding agents, with an eval harness that tests whether they actually change agent behavior.
* **[gravity-ai-ui](https://github.com/astandrik/gravity-ai-ui):** a UI generator that validates model output and renders it using trusted Gravity UI components.
* **[setup-local-ydb](https://github.com/astandrik/setup-local-ydb):** a GitHub Action for provisioning disposable local YDB tenants in CI.
* **[codex-pets](https://github.com/astandrik/codex-pets):** a YDB-backed gallery and MCP service for Codex-compatible animated pets.

## Open source contributions

Most of my open-source work is in [YDB Embedded UI](https://github.com/search?q=repo%3Aydb-platform%2Fydb-embedded-ui+author%3Aastandrik+is%3Apr+is%3Amerged&type=pullrequests): 300+ merged PRs covering diagnostics pages, the query editor, the AI assistant integration, component APIs, and Playwright e2e infrastructure. I also send occasional C++ fixes to [YDB core](https://github.com/search?q=repo%3Aydb-platform%2Fydb+author%3Aastandrik+is%3Apr+is%3Amerged&type=pullrequests) (KQP query statistics, HTTP/TLS startup).

Elsewhere: [Gravity UI](https://github.com/search?q=org%3Agravity-ui+author%3Aastandrik+is%3Apr&type=pullrequests), [codebase-memory-mcp](https://github.com/search?q=repo%3ADeusData%2Fcodebase-memory-mcp+author%3Aastandrik+is%3Apr&type=pullrequests), and the [codebase-memory-mcp skill](https://github.com/github/awesome-copilot/tree/main/skills/codebase-memory-mcp) in GitHub's awesome-copilot, which I added and maintain.

## Writing

I wrote [how semantic search works in Codex Pets](https://habr.com/ru/articles/1067576/). It covers embeddings, hybrid ranking, YDB storage, and fallback paths.

## Contact

[LinkedIn](https://www.linkedin.com/in/astandrik/) · [Telegram](https://t.me/astandrik) · [Email](mailto:astandrik@gmail.com) · [ORCID](https://orcid.org/0009-0004-3091-4951)

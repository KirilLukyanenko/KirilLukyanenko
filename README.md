### Kiril Lukyanenko: senior .NET backend engineer

I build backend services with AI coding agents, and make their work checkable: a written spec, tests the agent never sees, gates in CI, and a log of every run with its cost.

**[comp-ledger](https://github.com/KirilLukyanenko/comp-ledger)**: a multi-tenant compensation data service (.NET 10, PostgreSQL 17), with effective dating, "as known at" queries, snapshots, a streaming export and an MCP server. It was written entirely by Claude Code agents from specs. 9 logged runs, 1,347 holdout scenarios.

**[foreman](https://github.com/KirilLukyanenko/foreman)**: takes a task and an unfamiliar repository, and drives AI agents to a verified change: recon in a Docker sandbox, a checked spec, hidden acceptance tests, implementation, an independent review and a report. Measured on 9 real fixed issues in Python, TypeScript and C#: 9/9 verified by its gate, 7 of 8 gradeable ones resolved; a red team of planted prompt injections, safe 4/4.

C# · .NET · ASP.NET Core · PostgreSQL · Docker · GitHub Actions · Claude Code · MCP

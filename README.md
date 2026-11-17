# Stanislav Křikava

Fullstack developer in Prague. I work mostly in C# and .NET, and I build tools that run locally as one small native binary.

## Hubris

<a href="https://github.com/Shadowinger/Hubris"><img src="https://raw.githubusercontent.com/Shadowinger/Hubris/main/docs/hubris-dashboard.png" alt="Hubris desktop app: 11 of 368 tools in the model's context, one blocked call, the sign-in state of each server and the live call log" width="820"></a>

[Hubris](https://github.com/Shadowinger/Hubris) is an open-source gateway between an AI agent and its tools. It is one local server in front of every MCP server you use: it keeps tool definitions out of the model's context until they are needed, and it checks every tool call before it runs.

- **Less context.** With 368 tools from 7 servers connected, the model carried 2,428 tokens of tool definitions instead of 180,691.
- **Policy on every call.** Destructive commands stop and wait for approval, and secrets in tool output are masked before the model sees them.
- **One native binary.** C# on .NET 10 with Native AOT, 9.3 MB, no runtime to install. 239 unit tests and 93 end-to-end checks, CI on macOS, Linux and Windows.

[Repository](https://github.com/Shadowinger/Hubris) · [Latest release](https://github.com/Shadowinger/Hubris/releases/latest) · MIT licence

## Other projects

| Project | What it is | Built with |
|---|---|---|
| [SafeKeep](https://github.com/Shadowinger/SafeKeep) | Password manager with AES-256-GCM encryption and a GTK4 interface | C, GTK4, OpenSSL |
| [Medirecord Statistics](https://github.com/Shadowinger/Medirecord-Statistics) | Patient statistics app: an Angular frontend and an ASP.NET Core API on SQL Server | TypeScript, C#, SQL Server |
| [Dashboard](https://github.com/Shadowinger/Dashboard) | Admin dashboard with a REST API for managing users | Angular, Node.js, Express |

## What I work with

C# and .NET (ASP.NET Core, EF Core, Avalonia, Native AOT) · TypeScript and Angular · C · SQL Server · Docker · GitHub Actions

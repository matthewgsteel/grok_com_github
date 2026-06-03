# grok_com_github

GitHub MCP tool definitions and schemas for Grok agents.

**GitHub:** https://github.com/matthewgsteel/grok_com_github

## Contents
- 	ools/ — 43 JSON tool definition files (schemas) for GitHub operations:
  - Issues, pull requests, branches, releases, commits, search, repositories, collaborators, teams, etc.
  - Examples: create_pull_request.json, search_issues.json, merge_pull_request.json, ...

## Purpose
These definitions power the grok_com_github MCP server integration, allowing Grok (and agents built on it) to perform GitHub actions via function calls.

## Local location (Proton Drive synced)
C:\Users\MGS\Proton Drive\Code\mcp\grok_com_github

## Notes
- This repo contains the **tool manifests** exposed to the agent platform.
- The actual runtime implementation of the MCP server may be provided by the Grok environment or a separate connector.
- When updating tool surfaces (adding/removing capabilities), update the JSONs here and sync.

## Getting started with the MCP
This is connected in Grok Build / agent sessions as the "grok_com_github" server.

## Related
- Your dedicated Code workspace: the parent Code/ folder in Proton Drive contains this and other projects.
- See Code/README.md for the full recommended structure (mcp/, skills/, agents/, etc.).

Pushed from local Proton Drive workspace.

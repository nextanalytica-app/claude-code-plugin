# nextanalytica for Claude Code

A plugin that lets Claude Code add [nextanalytica](https://nextanalytica.app) web analytics to the sites and apps it builds. Its one skill points Claude at nextanalytica's MCP server, which tells it every step: create the project, add the tag, check that data arrives and attach the domain once the app is deployed. You only sign in once.

```sh
claude plugin marketplace add nextanalytica-app/claude-code-plugin
claude plugin install nextanalytica@nextanalytica
```

Docs: [Set up with your agent](https://nextanalytica.app/docs/model-context-protocol/agent-setup).

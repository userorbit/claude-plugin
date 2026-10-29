# Userorbit for Claude

Connect Claude to your Userorbit workspace to work with customer feedback, product roadmaps, help center content, changelogs, onboarding, and support.

## What it does

- **Feedback and roadmap**: summarize feature requests by customer problem and show where they sit on your roadmap.
- **Release review**: turn completed feature requests into a release-note draft, and suggest product tour, checklist, and help center updates for release notes you provide.
- **Support to help**: group recurring support questions and draft a help article grounded in the conversations and your existing documentation.
- **Product activity**: chart daily, weekly, and monthly active users, explore event catalogs, and inspect a person's activity history.

Drafts are reviewed in chat before anything is saved. Saving drafts and updating records happen only when you ask, within your workspace permissions. Publishing, scheduling, and sending are done in Userorbit.

## Install

In Claude Code:

```
/plugin marketplace add userorbit/claude-plugin
/plugin install userorbit@userorbit
```

On first use, Claude opens a browser window to sign in to Userorbit and choose a workspace. The plugin connects to the hosted Userorbit MCP server at `https://api.userorbit.com/mcp` with OAuth. No API keys are stored in the plugin.

## Requirements

A Userorbit account and workspace. Available tools follow your permissions and the access you grant during sign-in.

## Support

- Website: https://userorbit.com
- Support: https://userorbit.com/contact
- Privacy: https://userorbit.com/privacy
- Terms: https://userorbit.com/terms

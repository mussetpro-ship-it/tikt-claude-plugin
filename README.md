# TIKT for Claude

The TIKT plugin connects Claude to your [TIKT](https://trytikt.com) workspace: the leads TIKT finds among the people who engage with the
LinkedIn profiles you follow, scored against your ICP.

It adds the TIKT connector (`https://api.trytikt.com/mcp`) and three ready-made methods:

- **Triage leads** (`triage-leads`): Sort the workspace's leads: count them, read them by score and ICP criteria, propose what to keep, discard or list.
- **Send leads to my tools** (`send-leads-to-my-tools`): Get the right leads into the user's CRM or sequencer: a few by their tool's connector, many through TIKT's workflows.
- **Find profiles to track** (`find-profiles-to-track`): Find LinkedIn profiles the user's buyers follow, show them, and track the ones the user picks.

## Install

**Claude (claude.ai) and Cowork**: open **Customize › Plugins**, click **Add › Add marketplace**, enter `mussetpro-ship-it/tikt-claude-plugin`, then install
**TIKT**. Open the plugin's **Connectors** tab and connect TIKT.

**Claude Code**:

```
/plugin marketplace add mussetpro-ship-it/tikt-claude-plugin
/plugin install tikt@tikt
```

Then run `/mcp` and sign in to TIKT.

## Connect

When you connect, a TIKT window opens: sign in, choose **Full access** or **Read only**, and click **Allow**. Your assistant then works
in your workspace only. Disconnect it anytime in TIKT, in **Settings › API & MCP**.

The plugin holds no key and no data: it only points Claude to TIKT. Help: https://docs.trytikt.com/help/connect-your-ai-assistant

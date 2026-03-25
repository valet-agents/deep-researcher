# Deep Researcher

Every day at 8am, researches top AI sources, summarizes the 5 most important stories from the previous day, and posts a briefing to #ai-news in Slack.

## Prerequisites
- A [Parallel](https://parallel.ai) account and API key
- A Slack workspace with a bot token (`xoxb-...`) and a `#ai-news` channel (bot must be invited to the channel)

<table>
  <tr>
    <td><strong>CHANNELS</strong></td>
    <td><code>cron</code> — 8am daily</td>
  </tr>
  <tr>
    <td><strong>CONNECTORS</strong></td>
    <td><code>slack-mcp</code> <code>parallel-search-mcp</code></td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <br />
      <a href="https://dashboard.valet.dev/setup/configure?from=github.com/valet-agents/deep-researcher">
        <img src="https://raw.githubusercontent.com/valet-agents/deep-researcher/main/.github/deploy-button.svg" alt="Deploy Agent →" height="40" />
      </a>
      <br /><br />
    </td>
  </tr>
</table>

# bugAgent Status

System status and uptime monitoring for [bugAgent](https://bugagent.com), powered by [Upptime](https://github.com/upptime/upptime).

Live at: **[status.bugagent.com](https://status.bugagent.com)**

## Monitored Services

| Service            | URL                                 |
| ------------------ | ----------------------------------- |
| bugAgent Website   | https://bugagent.com                |
| bugAgent Dashboard | https://app.bugagent.com            |
| bugAgent API       | https://app.bugagent.com/api/health |
| Supabase Database  | Supabase REST API                   |
| Supabase Auth      | Supabase Auth health                |
| MCP Server         | https://mcp.bugagent.com            |

## How it works

- GitHub Actions pings each endpoint every 5 minutes
- Uptime data stored as JSON in this repo
- Static status page auto-deployed to GitHub Pages
- Response time graphs updated every 6 hours
- Custom domain: status.bugagent.com

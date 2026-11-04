# Prompt 6 — the dashboard that shows what matters (Claude Dashboards)

**Plan:** Dashboards is in **beta** and only available on paid plans (Pro, Max, Ultra, Team, Enterprise).
On Enterprise, it’s turned off until the account owner enables it.
**Data:** Connect a data source (BigQuery, Snowflake, Databricks, Redshift, ClickHouse) or an app like
Salesforce through connectors. Without that, you can start with an attached spreadsheet.

## First: choose the numbers (before opening the dashboard)
A good dashboard answers one question: “Am I getting there?”
- **Outcome number** (what you want in the end): monthly revenue, active customers, appointments completed.
- **Drivers** (what you can influence today): proposals sent, first appointments, patient follow-ups.

```
Help me choose the numbers for my dashboard.
My goal for [period] is: [e.g., 120 appointments per month].
1. Confirm which is the outcome number.
2. Suggest 2 to 4 drivers of that outcome that I can measure every week.
3. For each one, say where the data comes from (which system or spreadsheet) and how often to update it.
Don’t build the dashboard yet.
```

## Then: build the dashboard
```
Build a dashboard with: [outcome number] against the target at the top; below that, [drivers]
week by week; one chart per number, with no embellishments. Use [connector / attached spreadsheet].
For each chart, say in one sentence what changed since last week.
```

**Before sharing:** click each number and check the query behind it; check the date of the
last update on each chart. Anthropic hasn’t published query accuracy rates, so always verify.
For in-depth analysis, send the dashboard to your BI tool.
# renovate-config

Shared [Renovate](https://docs.renovatebot.com/) configuration for the yoprotocol org.

## Usage

Add this to `renovate.json` in any repo:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>yoprotocol/renovate-config"]
}
```

## What it does

- **Schedule**: Runs Monday mornings only (before 7am Sofia time)
- **Patches**: Grouped into 1 PR per week
- **Minors**: Grouped into 1 PR per week
- **Majors**: Require approval via the Dependency Dashboard issue
- **Concurrent PRs**: Max 5 open at any time
- **No auto-merge**: All PRs require manual review

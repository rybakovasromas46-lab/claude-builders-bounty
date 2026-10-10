# Weekly GitHub Dev Summary

1. Import `workflow.json` into n8n (Code nodes must allow HTTP requests).
2. In **Configuration**, set the GitHub `owner/repo`, EN/FR language, Slack webhook URL, optional GitHub token, and Anthropic API key. Do not commit credentials.
3. Set n8n timezone and verify the weekly Friday 17:00 trigger.
4. Execute manually, check commits/issues/merged PRs, Claude response and Slack delivery. Capture a genuine successful execution screenshot.
5. Activate the workflow after successful verification.

Requires working n8n, GitHub API access, Claude API billing and Slack webhook. Model ID may need updating as Anthropic availability changes. Never include real tokens in screenshots or commits. Pagination capped at 20 pages per endpoint.

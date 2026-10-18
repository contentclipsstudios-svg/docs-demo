# API reference (sample)

## `POST /v1/jobs`

Create a docs build job.

| Param | Type | Required | Description |
|---|---|---|---|
| `repo` | string | ✓ | Git repository URL |
| `framework` | enum | — | `docusaurus` \| `mkdocs` (default: auto) |
| `deploy` | bool | — | Deploy after build (default: `true`) |

```json
{ "repo": "https://github.com/acme/app", "framework": "mkdocs" }
```

**201** returns `job_id` — builds complete in under 24h, typically under 6h.

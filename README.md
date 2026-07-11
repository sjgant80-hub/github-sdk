# @ai-native-solutions/github-sdk

Sovereign wrapper for **GitHub** · DevOps

**100 endpoints** wrapped from OpenAPI spec.

## Install
```bash
npm install @ai-native-solutions/github-sdk
```

## Use
```js
import Github from '@ai-native-solutions/github-sdk';
const client = new Github({ apiKey: process.env.GITHUB_KEY });
```

## Endpoints (100)
- `GET /` · GitHub API Root
- `GET /advisories` · List global security advisories
- `GET /advisories/{ghsa_id}` · Get a global security advisory
- `GET /agents/repos/{owner}/{repo}/tasks` · List tasks for repository
- `POST /agents/repos/{owner}/{repo}/tasks` · Start a task
- `GET /agents/repos/{owner}/{repo}/tasks/{task_id}` · Get a task by repo
- `GET /agents/tasks` · List tasks
- `GET /agents/tasks/{task_id}` · Get a task by ID
- `GET /app` · Get the authenticated app
- `POST /app-manifests/{code}/conversions` · Create a GitHub App from a manifest
- `GET /app/hook/config` · Get a webhook configuration for an app
- `PATCH /app/hook/config` · Update a webhook configuration for an app
- `GET /app/hook/deliveries` · List deliveries for an app webhook
- `GET /app/hook/deliveries/{delivery_id}` · Get a delivery for an app webhook
- `POST /app/hook/deliveries/{delivery_id}/attempts` · Redeliver a delivery for an app webhook
- `GET /app/installation-requests` · List installation requests for the authenticated app
- `GET /app/installations` · List installations for the authenticated app
- `GET /app/installations/{installation_id}` · Get an installation for the authenticated app
- `DELETE /app/installations/{installation_id}` · Delete an installation for the authenticated app
- `POST /app/installations/{installation_id}/access_tokens` · Create an installation access token for an app
_...and 80 more_

## License
MIT · Copyright 2026 AI-Native Solutions

## Upstream
- Docs: https://docs.github.com/en/rest
- Homepage: https://github.com

# Nexora.AI — Backend

Backend for a multi-tenant AI chatbot SaaS platform.

## Services
| Service | Folder | Local port |
|---|---|---|
| core-service | services/core | 8001 |
| chat-service | services/chat | 8002 |
| voice-service | services/voice | 8003 |
| form-service | services/forms | 8004 |
| ingestion-worker | services/ingestion_worker | – |
| platform-common (shared code) | packages/platform_common | – |

## How we work
- `main` is protected: every change goes through a pull request with 1 approval.
- Branch names: `feat/<TaskID>-short-name` (example: `feat/B10-login-roles`)
- Commit messages: `feat:`, `fix:`, `chore:`, `test:`, `docs:`
- One GitHub issue per task. Never commit secrets or `.env` files.


## Project board
All tasks are tracked as GitHub issues (one per task ID) on the **Nexora.AI Backend** board in the repo's **Projects** tab.
# sync-config

Kunpeng+BoostKit community mirror sync configuration — powered by [community-mirror](https://github.com/huanglei0308/community-mirror).

This repository runs an automated daily workflow that mirrors repos from:
- **gitcode/kunpengcompute** → **github/kunpengcompute**
- **gitcode/BoostKit** → **github/kunpengcompute**

<!-- SYNC_STATUS_START -->
<!-- SYNC_STATUS_END -->

## Setup

This sync-config follows the [community-mirror setup guide](https://github.com/huanglei0308/community-mirror/blob/main/docs/setup-guide.md).

### Required Secrets

| Secret | Description |
|--------|-------------|
| `SYNC_KUNPENG_GITCODE_TOKEN` | GitCode API token for reading source repos |
| `SYNC_KUNPENG_TOKEN` | GitHub token for creating/managing destination repos |
| `SYNC_KUNPENG_PRIVATE_KEY` | SSH private key for pushing to GitHub |

## Contact

huanglei 30082796

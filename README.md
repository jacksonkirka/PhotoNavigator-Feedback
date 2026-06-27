# PhotoNavigator Feedback

Public bug reports, feature requests, and general feedback from [PhotoNavigator](https://github.com/jacksonkirka/PhotoNavigator-Releases) beta users.

## How submissions arrive

1. User fills out **Help â†’ Send Feedback...** in the Windows app.
2. The entry is saved to the local PostgreSQL catalog on their PC (`pn_user_feedback`).
3. The app submits to this repository via the GitHub Issues API (publisher build token).

Anyone can **read** open issues here. Only maintainers need access to the private source repo.

## Labels

| Label | Meaning |
|-------|---------|
| `user-feedback` | Submitted from the in-app dialog |
| `bug` | Bug report |
| `enhancement` | Feature request |
| `question` | General feedback |

## Maintainers

- Triage with `tools/pull_user_feedback.ps1` in the PhotoNavigator source tree.
- Implement fixes in the private `PhotoNavigator` repo; close issues here when shipped.
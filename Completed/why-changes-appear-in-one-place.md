# Why you only see changes in one place

| Location | What it is | Does direct edit update it? |
|----------|------------|-----------------------------|
| Project repo (`app-insights-unlocked`) | The actual project | Yes – your direct changes appear here |
| Data-analytics → Completed | A separate parent/portfolio repo (or folder) | No – it is not linked automatically |

## Explanation

Changing files inside the project repository (`app-insights-unlocked`) only updates that repository.

The folder **Data-analytics → Completed** is a different place on GitHub. It does not receive those changes unless you copy or update them there yourself.

## How to keep them in sync

1. Make changes in the real project repo.
2. Copy / update the project (or add a link) inside `Data-analytics/Completed/`.
3. Commit and push the portfolio repo.

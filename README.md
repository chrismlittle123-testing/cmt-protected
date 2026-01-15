# cmt-protected

Test repository for check-my-toolkit branch protection checks.

This repo has branch protection **ENABLED** on main.

## Configuration

```toml
[process.repo]
enabled = true
require_branch_protection = true
require_codeowners = true

[process.repo.branch_protection]
branch = "main"
required_reviews = 1
dismiss_stale_reviews = true
```

## Branch Protection Settings

- Require pull request reviews: 1
- Dismiss stale reviews: Yes
- Require status checks: No

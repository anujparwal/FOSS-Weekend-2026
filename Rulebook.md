# Contributor Rulebook

Welcome to the contribution guidelines! This document outlines the rules and processes for contributing to the project effectively.

## Event Timeline

- Start: **10th April 2026, 00:00**
- End: **12th April 2026, 23:59**

## PR Point System

Your contributions will be evaluated and assigned points based on the following system:

### Base Points (Internal and General Repos):
| Difficulty | Description | Points |
| :-- | :-- | :-- |
| Basic | Basics (Bash practice, Git drills, docs) | 5 pts |
| Very Easy | General repo fixes, very simple UI tweaks | 15 pts |
| Easy | Simple to implement UI tweaks and minor bug fixes | 30 pts |
| Medium | Feature implementation, logic fixes | 45 pts |
| Hard | Complex refactoring, core logic | 60 pts |
| Very Hard | Performance optimization, major features | 70 pts |
| Exceptionally Hard | Reimplementation or rewriting certain modules of large scale projects | 80+ pts |

It is not advisable to spend time on Exceptionally Hard unless you know what you are doing.

### Special Bonuses (One-Time Only)
- Contribution to a Special Repo: +20 pts
- External Repo (50+ stars): +40 pts
- External Repo (250+ stars): +60 pts
- External Repo (1K+ stars): +100 pts

**Note:** External repo bonuses apply only to Easy-Medium difficulty issues or higher. Very Easy PRs in high-star repos will not qualify for these bonuses.

### Issue Creation
- Create an issue: 5 to 15 points based on quality.
- Penalty: Points will be deducted for useless or spam issues.

### Quality Bonus (Up to 10 pts):
You can earn extra points based on the quality of your PR.

## Repository Types
Repositories are categorized as follows:

### 1. Multiple PRs Allowed on a Single Issue
- Multiple contributors can submit PRs for the same issue.
- PRs will be closed after review, and points will be given accordingly.
- **No assignment is required** in these repositories.
- There is no need to assign yourself in multiple-PR repositories.
- Tagged as `Muliple-PR` in readme.md

### 2. Single PR Per Issue
- Only one PR is allowed per issue.
- The PR will be merged after review, and points will be assigned.
- The bot will be active here, and **assignment is required** to work on an issue.
- Tagged as `Unique-PR` in readme.md

## Issue Assignment System
- To assign yourself an issue, comment `/assign`.
- To unassign yourself, comment `/unassign`.
- A contributor can assign themselves a maximum of **two issues at a time**.
- You can only assign additional issues if your previous assigned issues are closed.
- If two people have already raised PRs before the assignment time, the third person should wait until the maintainer reviews the previous PRs before assigning the issue to themselves.
- Time limits for issue completion based on difficulty (old assignment system mapped for all issues):
  - **Basic Issue**: 1.5 hours
  - **Very Easy Issue**: 1.5 hours
  - **Easy Issue**: 1.5 hours
  - **Medium Issue**: 3 hours
  - **Hard Issue**: 5 hours
  - **Very Hard Issue**: 5 hours
  - **Exceptionally Hard Issue**: 8 hours
  - **No label**: Considered **Medium Issue** (3 hours)
  - **There is no time limit for issues in multiple-pr repositories**
- If you need more time due to substantial work done, you can request the maintainer to increase the time.
- **Note**: Extensions are given only when necessary and only when you have shown what you have done (Using Draft PR functionality), so assign issue only if you can work on it.

## Leaderboard System
- The leaderboard tracks contributions via labels.
- The leaderboard is updated every 30 mins, so don't dm maintainers that i haven't got points.

## Review Process
- All contributions are reviewed and managed by FOSS Wing members.
- Difficulty and final points may be adjusted if the actual solution is significantly easier or harder than initially estimated.

## Getting Started
1. Review the curated list of repositories.
2. Identify an issue or create a new one.
3. Use the `/assign` command where assignment is required.
4. Submit your Pull Request within the relevant time limit.

## Contributor Responsibilities(Quality Bonus points)
- **Follow Contribution Guidelines**: Ensure that your code follows best practices and project rules.
- **Write Clear Commit Messages**: Keep commit messages meaningful and concise.
- **Use Proper Branching**: Work on a separate branch before making a PR.
- **Respect Deadlines**: Complete issues within the given timeframe.
- **Engage with Maintainers**: If a PR needs improvement, make necessary changes promptly.
- **Label PRs Properly**: Ensure that PRs have the correct labels so they are processed efficiently.

## Setup Guidelines
- Ensure that you follow the setup guide provided in the **README.md** or **CONTRIBUTING.md**.
- If environment variables are required, check for a `.env.example` file to configure them correctly.

For further assistance, contact **the maintainers** or **FOSS-Wing@Axios**.

Happy Contributing!


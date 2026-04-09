# Maintainer Guide

## Event Timeline

- Start: **10th April 2026, 00:00**
- End: **12th April 2026, 23:59**

## Leaderboard System
- The leaderboard is maintained by tags.
- Once a PR is accepted, the maintainer **must** add a label in the format: `accepted-'points here'` (e.g., `accepted-30`).
- The label must be in **lowercase** so that the leaderboard bot can pick it up correctly.

## PR Point System

As a maintainer, you are responsible for evaluating and assigning points to Pull Requests (PRs) based on the following system:

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

It is not advisable to spend time on Exceptionally Hard unless clearly justified by implementation complexity.

### Special Bonuses (One-Time Only)
- Contribution to a Special Repo: +20 pts
- External Repo (50+ stars): +40 pts
- External Repo (250+ stars): +60 pts
- External Repo (1K+ stars): +100 pts

**Note:** External repo bonuses apply only to Easy-Medium difficulty issues or higher. Very Easy PRs in high-star repos do not qualify.

### Issue Creation
- Create an issue: 5 to 15 points based on quality.
- Penalty: Points are deducted for useless or spam issues.

### Quality Bonus (Up to 10 pts):


## Repositories
Repositories will be divided into two categories:
1. **Multiple PRs Allowed on a Single Issue**:
   - Multiple contributors can submit PRs for the same issue.
   - PRs will be closed after review, and points will be given accordingly.
   - **No assignment is required** in this type of repository.

2. **Single PR Per Issue**:
   - Only one PR is allowed per issue.
   - The PR will be merged after review, and points will be assigned.
   - The bot will be active here, and **assignment is required** for contributors to work on an issue.

## Issue Assignment System
- Contributors can assign themselves an issue by commenting `/assign`.
- To unassign an issue, contributors can comment `/unassign`.
- A contributor can assign themselves a maximum of **three issues at a time**.
- If two people have already raised PRs before assignment time, the third person should wait for review before assigning.
- The time limit for completing an issue (old assignment system mapped for all issue difficulties):
   - **Basic Issue**: 1.5 hours
   - **Very Easy Issue**: 1.5 hours
   - **Easy Issue**: 1.5 hours
   - **Medium Issue**: 3 hours
   - **Hard Issue**: 5 hours
   - **Very Hard Issue**: 5 hours
   - **Exceptionally Hard Issue**: 5 hours
   - **No label**: Considered **Medium Issue** (3 hours)
   - **Multiple-PR repositories**: No assignment required and no time limit
- If the maintainer finds that a contributor has done good work and needs more time, they can extend the deadline by commenting `/extend-'time in hrs here'` (e.g., `/extend-2`).
- **Note**: Extend time only when necessary.

## Maintainer Responsibilities:
1. **Review PRs Promptly**: Ensure PRs are reviewed in a timely manner.
2. **Provide Constructive Feedback**: If a PR needs improvement, leave clear and actionable feedback.
3. **Assign Points Fairly**: Use the point system above to evaluate contributions objectively.
4. **Enforce Contribution Guidelines**: Make sure contributors follow coding standards and project rules.
5. **Merge PRs Appropriately**: Ensure PRs are tested and meet quality standards before merging.
6. **Add the Acceptance Label**: Always tag accepted PRs with `accepted-'points here'` to update the leaderboard correctly.

## Additional Notes:
- If a PR does not meet minimum quality requirements, maintainers may request changes before assigning points.
- For edge cases, maintainers can discuss and decide on point allocation based on the overall effort involved.
- If a contributor disputes the points assigned, maintainers should review and justify their decision.

Maintainers play a crucial role in keeping the project organized and ensuring high-quality contributions. Thank you for your efforts in maintaining the repository!

## Setup Guidelines
- Ensure the repository has a proper **README** with a setup guide.
- If environment variables are needed, include a `.env.example` file to guide contributors on necessary configurations.

For further assistance, contact **FOSS-Wing@Axios**.

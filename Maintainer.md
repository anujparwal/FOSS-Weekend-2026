# Maintainer Guide

## Event Timeline

- Start: **10th April 2026, 00:00**
- End: **12th April 2026, 23:59**

## Leaderboard System
- The leaderboard is maintained by tags.
- Once a PR is accepted, the maintainer **must** add a label in the format: `accepted-'points here'` (e.g., `accepted-30`).
- The label must be in **lowercase** so that the leaderboard bot can pick it up correctly.

## PR Point System

### **1. Basic (5 pts)**

> ![NOTE]
> Reserved for Git and Bash Repo

**Scope:** Learning-level or trivial changes

**Effort:** 5–20 minutes

**Requirements:**

* No real logic implementation
* No understanding of project architecture needed
* Minimal or no testing required

**Examples:**

* Fixing typos in docs
* Running predefined scripts (e.g., Bash practice)
* Formatting files (README, comments)

---

### **2. Very Easy (15 pts)**

**Scope:** Extremely small code changes

**Effort:** 15–45 minutes

**Requirements:**

* Change limited to 1–2 files
* No new logic, only minor edits
* No dependency or architecture understanding required

**Examples:**

* Fixing UI text or alignment
* Updating config values
* Minor styling fixes (CSS, Tailwind tweaks)

---

### **3. Easy (30 pts)**

**Scope:** Small feature or bug fix

**Effort:** 1–2 hours

**Requirements:**

* Basic understanding of the codebase
* Small logic addition or modification
* Limited to a single module/component

**Examples:**

* Adding a simple button with functionality
* Fixing a minor bug in logic
* Handling a simple API response

---

### **4. Medium (45 pts)**

**Scope:** Standard feature development

**Effort:** 2–5 hours

**Requirements:**

* Requires understanding of module-level architecture
* Involves multiple files/components
* May include state handling, API integration, or validation

**Examples:**

* Implementing a complete feature (CRUD, filters, etc.)
* Fixing non-trivial bugs affecting functionality
* Writing reusable components

---

### **5. Hard (60 pts)**

**Scope:** Complex logic or refactoring

**Effort:** 5–10 hours

**Requirements:**

* Deep understanding of the codebase
* Cross-module changes
* Must consider edge cases and performance

**Examples:**

* Refactoring existing modules without breaking behavior
* Implementing non-trivial algorithms
* Fixing complex bugs with unclear root cause

---

### **6. Very Hard (70 pts)**

**Scope:** Advanced system-level work

**Effort:** 10–20 hours

**Requirements:**

* Strong architectural understanding
* Performance considerations required
* May involve concurrency, optimization, or system design

**Examples:**

* Optimizing slow queries or rendering
* Designing scalable features
* Handling large data processing efficiently

---

### **7. Exceptionally Hard (80+ pts)**

**Scope:** Major system changes or redesign

**Effort:** 20+ hours

**Requirements:**

* Full understanding of the project architecture
* High risk of breaking existing functionality
* Requires planning, design, and testing

**Examples:**

* Rewriting core modules
* Migrating to a new architecture or framework
* Implementing large-scale features affecting multiple systems

---

It is not advisable to spend time on Exceptionally Hard unless clearly justified by implementation complexity.

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

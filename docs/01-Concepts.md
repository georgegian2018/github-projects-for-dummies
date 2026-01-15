# Core Concepts: Organization, Repository, Project

This section fixes the #1 beginner confusion: these are different things.

## 1) Organization (org)
An **Organization** is like a workspace that can own:
- repositories
- projects
- people / teams

Organizations are the only real way to “group repositories”.

✅ Example:
- `progenesis-research` (organization)

## 2) Repository (repo)
A **Repository** is where your content lives:
- code
- LaTeX papers
- figures
- datasets
- documentation

A repo belongs to either:
- your personal account, OR
- an organization

✅ Example:
- `progenesis-research/mdpi-paper-mmwave-v2x`

## 3) Project (GitHub Projects)
A **Project** is a planning tool (like Trello/Jira-lite):
- board view (Todo → In Progress → Done)
- table view (spreadsheet)
- roadmap view (timeline)

A project does NOT contain repositories.

> 💡 **Key sentence:**  
> **Projects organize work. Repositories store content.**


## Correct hierarchy (memorize this)

```text
Personal GitHub Account
└── Organization
├── Repositories
│ ├── repo-1
│ ├── repo-2
│ └── repo-3
└── Projects
├── Project A
└── Project B
```

This hierarchy means:

- Your **personal account** is just how you log in.
- An **organization** is a container that groups related work.
- **Repositories** store files, code, papers, figures, and data.
- **Projects** track work using tasks and issues.

Repositories and Projects live **side by side** inside an organization.
Projects do **not** contain repositories.

### Important rule

- ✅ Use **Organizations** to group repositories.
- ❌ Do **not** expect Projects to act like folders for repositories.

> 📌 **Think of it this way:**  
> Repositories hold *things*.  
> Projects track *work*.



---
⬅️ **Previous:** [Home](00-Home.md)  ➡️ **Next:** [How Projects Link to Repositories](02-Projects-Linking.md)

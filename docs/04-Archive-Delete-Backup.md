# Archive vs Delete vs Backup (Safe Closing)

Beginners often say “close the repo/project/org”, but GitHub uses different actions.

## What “close” really means in GitHub
| Thing | “Close” exists? | What you can do |
|------|------------------|----------------|
| Issue | ✅ Yes | Close |
| Project | ❌ No | Archive or Delete |
| Repository | ❌ No | Archive or Delete |
| Organization | ❌ No | Delete only |

## Safe option: Archive (recommended)
Archiving is a “soft close”:
- keeps everything
- makes it read-only
- can be restored later

### Archive a repository
Repo → **Settings** → scroll to **Danger Zone** → **Archive this repository**

### Archive a project
Project → **Settings** → **Archive project**

## Dangerous option: Delete (irreversible)
Deleting removes it permanently.
Only do it if:
- it’s a test
- it’s empty
- you are 100% sure you never need it again

### Delete a repository
Repo → **Settings** → **Danger Zone** → **Delete this repository**

### Delete a project
Project → **Settings** → **Delete project**

### Delete an organization
Org → **Settings** → **Danger Zone** → **Delete organization**
This deletes EVERYTHING inside it (repos + projects).

## Backups (do this before deleting)
### Quick backup
Repo → **Code** → **Download ZIP**

### Proper backup (best)
Use git:
```bash
git clone https://github.com/ORG/REPO.git
```

---

⬅️ **Previous:** [Archive-Delete-Backup](04-Archive-Delete-Backup.md)  
➡️ **Next:** [Table of Contents](TOC.md)
--
---

⬅️ **Previous:** [Org vs Personal Projects](03-Org-vs-Personal-Projects.md)  
🏁 **End of tutorial** · [Back to Table of Contents](TOC.md)


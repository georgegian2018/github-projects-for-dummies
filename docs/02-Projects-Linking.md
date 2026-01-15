# How Projects Link to Repositories (The Real Mechanism)

This is the “aha moment”.

## The rule
> Projects do NOT link to repositories directly.

Instead, GitHub links them through **Issues** (or Pull Requests).

## The real chain

Project → Issue → Repository

Meaning:
- An **Issue** belongs to a **Repository**
- A **Project** contains a card that can reference that issue
- That card is what makes it *feel linked*

## Step-by-step: link a repo to a project
### Step 1 — Create an Issue in the repository
1. Open your repo
2. Click **Issues**
3. Click **New issue**
4. Give it a title (example):
   - `MDPI paper – mmWave V2X antennas`
5. Click **Submit**

### Step 2 — Add that Issue to the Project
Method A (from the Issue page):
1. Open the issue
2. On the right sidebar find **Projects**
3. Select your project (e.g., `Research Roadmap`)

Method B (from the Project board):
1. Open the project
2. Click **+ Add item**
3. Choose **Add issue**
4. Select the issue from your repository

## Result
Now your project shows a card that includes:
- the issue title
- the repo name

That is the “link”.

✅ Next: avoid the biggest trap (Org vs Personal projects)  
`docs/03-Org-vs-Personal-Projects.md`


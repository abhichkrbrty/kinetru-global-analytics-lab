---

## 📄 File 2: `onboarding/01_git_workflow.md`

```md
# Git Workflow

## Branching Rule
Never push directly to `main`.

Create branches like:

name/week1-eda
name/week2-dashboard
name/week3-survey

---

## Daily Workflow
```bash
git checkout -b name/weekX-task
# work
git add .
git commit -m "clear description"
git push origin name/weekX-task

Then open a Pull Request.

⸻

Pull Request Checklist
	•	Code/notebook runs
	•	Clear commit messages
	•	Deliverables placed in deliverables/weekX/
	•	Short explanation included

⸻

Review Process
	•	PRs are reviewed asynchronously
	•	Feedback is expected
	•	Revisions are normal

⸻

Bad Practices (Avoid)
	•	One giant PR
	•	Broken notebooks
	•	Copy-paste tutorials without context


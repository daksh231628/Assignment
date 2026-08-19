Assignment 1 – Local Merge (Mandatory)
Goal: Practice merging a feature branch into main locally.

Create a new branch:
git checkout -b feature-local-merge
Create a file named local-merge.txt and write 3–4 lines about what you learned today about local merge.
Stage and commit:
git add .
git commit -m "Add local-merge notes"
Switch back to main:
git checkout main
Merge the feature branch:
git merge feature-local-merge
Push main:
git push origin main
Run git log --oneline -5 and take a screenshot of the history.
Answer=<img width="1281" height="822" alt="Screenshot 2026-08-19 091539" src="https://github.com/user-attachments/assets/8c3a5c7f-568d-43df-936c-1fb1a1e498c3" />


Assignment 2 – Pull Request Workflow (Mandatory)
Goal: Create a Pull Request, merge it on GitHub, then update local main with git pull.

Create a new branch:
git checkout -b feature-pr-practice
Create a file named pr-practice.txt. Write what a Pull Request is and why teams use it (4–5 lines).
Commit:
git add .
git commit -m "Add PR practice notes"
Push the branch:
git push -u origin feature-pr-practice
On GitHub: Open a Pull Request from feature-pr-practice into main. Write a clear PR title and description.
Merge the Pull Request on GitHub (use “Create a merge commit” option).
Delete the feature branch on GitHub (optional but recommended).
Locally:
git checkout main
git pull origin main
Confirm pr-practice.txt is now present on local main. Take a screenshot of the terminal after pull and of the merged PR on GitHub.
Answer=
https://github.com/daksh231628/github-branching-practice/pull/2
<img width="562" height="690" alt="Screenshot 2026-08-19 092502" src="https://github.com/user-attachments/assets/566d0fea-f29f-4bb3-9b5e-26db060ecf34" />
<img width="1317" height="619" alt="Screenshot 2026-08-19 092708" src="https://github.com/user-attachments/assets/2f4aa7fd-fb18-4f26-9524-cdcadf5ccb32" />

Assignment 3 – Compare Both Workflows (Mandatory)
Goal: Experience both methods side-by-side and write a short comparison.

You already did one local merge (Assignment 1) and one PR merge (Assignment 2).
Create a short file named comparison.txt (on a new branch or directly on main).
In that file answer these questions in your own words:
What is the main difference between local merge and PR merge?
When would you prefer a local merge?
When is a Pull Request better?
After merging a PR on GitHub, which command brings the changes to your computer?
What does git pull actually do (two steps)?
Commit and push comparison.txt (either via local merge or via a new PR).
Submit: Content of comparison.txt (or screenshot) + link to the commit/PR.
Answer=https://github.com/daksh231628/github-branching-practice
<img width="1287" height="537" alt="Screenshot 2026-08-19 101046" src="https://github.com/user-attachments/assets/c9ab9c3b-6244-4980-9cd6-e7f549c48ac8" />


Assignment 4 – git pull Practice (Mandatory)
Goal: Practice updating local branches safely with git pull.

Make sure you are on main:
git checkout main
Run git pull origin main and observe the output.
Create a small change on GitHub itself (edit any file using the GitHub web editor on main and commit).
Back in your terminal, run git pull origin main again.
Confirm the web change is now in your local files.
Take a screenshot of the terminal showing the pull that brought the web change.
Answer= <img width="1262" height="601" alt="Screenshot 2026-08-19 101409" src="https://github.com/user-attachments/assets/2959903e-39be-4162-9563-d5391e315bb6" />

Bonus Assignment – Mini Collaboration Simulation (Optional)
Goal: Simulate a small team workflow (can be done alone with two clones or with a classmate).

Person A (or Clone A): Create branch feature-A, add a file, push, open PR.
Person B (or Clone B): Create branch feature-B, add a different file, push, open another PR.
Merge both PRs on GitHub (one after another).
Both persons run git checkout main && git pull and confirm both files are present.
Write 2–3 lines about what you observed when pulling after multiple merges.
Submit (optional): Short note + screenshots of both merged PRs and final git log --oneline.
Answer= 




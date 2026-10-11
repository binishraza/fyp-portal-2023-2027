# FYP Supervisor Portal – EUM 2023-27

Static website (GitHub Pages). No login. Anyone with the link sees every supervisor's allocated FYP groups with project title, students, roll numbers and email / call / WhatsApp links.
Supervisors can pick their name in the dropdown, or open a direct link such as `https://<user>.github.io/<repo>/#sup=Dr.Hira%20Nazir`.

## Publish
1. Create a GitHub repository and upload everything in this folder.
2. Settings → Pages → Deploy from branch `main`, folder `/ (root)`.
3. Share `https://<user>.github.io/<repo>/`.

## Update data
All data is in `data/groups.json` (edit and commit): each group has `supervisor`, `title` and `members` (name, roll, email[], phone[]).

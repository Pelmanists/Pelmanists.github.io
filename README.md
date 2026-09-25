# Team project journal

Static site for GitHub Pages. No build step: edit the HTML files and push.

## Publish on GitHub Pages
1. Create a **public** repo on GitHub (e.g. `team-name-journal`).
2. Upload everything in this folder to the repo root (Add file > Upload files), or:
   ```
   git init && git add . && git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/USERNAME/REPO.git
   git push -u origin main
   ```
3. Repo **Settings > Pages** > Source: *Deploy from a branch* > Branch: `main`, folder `/ (root)` > Save.
4. Wait 1 to 2 minutes. Your site is at `https://USERNAME.github.io/REPO/`.
5. Add teammates: **Settings > Collaborators** > Add people.

A public GitHub Pages site is viewable by anyone with the link, so the instructor and TAs have access automatically. Open the URL in a private/incognito window to confirm before submitting.

## Editing
- Find and replace `Team Name` and `Project Name` in all four HTML files.
- Photos: put square images in `images/`, then replace each `<div class="avatar">` with
  `<img src="images/name.jpg" alt="Portrait of Full Name">`.
- Journal: copy an `<li class="entry">` block and paste it at the top of the list.
- Charter: the contract lives in `charter.html`. Fill in the team name and problem area there when decided.

## Course policy reminders (AI 380)
- **No course materials on the site:** don't post assignment text, rubrics, slides, or lecture content. Link to Canvas or describe milestones in your own words. Only our own work goes in `docs/`.
- **Deadlines:** late work needs an emailed request *and* an instructor reply before the due date.

# Pelmanists.github.io

THE ESSEX PADEL LEAGUE — FREE WEBSITE

FILES:
- index.html: mobile-friendly website, league table, fixtures and organiser tool
- results.json: public match results (initial two matches included)

FREE PUBLISHING WITH GITHUB PAGES:
1. Create a free GitHub account at github.com if needed.
2. Create a new PUBLIC repository named essex-padel-league.
3. Upload index.html and results.json into the repository root (not inside a subfolder).
4. In repository Settings > Pages, select Deploy from a branch, branch main, folder /(root), and Save.
5. Wait for GitHub Pages to deploy. The website address will generally be https://YOUR-USERNAME.github.io/essex-padel-league/ (check Settings > Pages for the actual URL).
6. Share that public URL in your group chat.

UPDATING SCORES:
1. Visit the website and open Organiser.
2. Choose a fixture, enter all three set scores, and click Save result locally.
3. Click Download updated results.json.
4. In your GitHub repository, replace the existing results.json with the downloaded one and commit the change.
5. GitHub Pages will update the public site shortly after deployment.

IMPORTANT:
The Organiser tab is a convenience editor, NOT a password-protected admin system. Changes made in the browser are temporary until the downloaded results.json is uploaded to GitHub. All visitors can see the organiser tools, but cannot change the public website without GitHub repository write access. The website uses no paid hosting or database.

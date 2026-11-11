# Side Hustle match test (demo)

A static, single-page demo of the Side Hustle match test. Testers describe a job, review a drafted job description, see three matched specialists and answer Interested or Not interested.

- **Everything is fictional.** The 135 specialists and their companies are invented.
- **Demo limits.** The job description comes from a built-in template (no AI) and matching uses keywords only.
- **Responses.** When a tester finishes, their inputs and answer are posted to a Google Sheet through an Apps Script web app (see `SHEET_ENDPOINT` in `index.html`). The page tells testers this before they start.
- **Files.** `index.html` is the whole site, with no build step or dependencies. The page asks search engines not to index it (`noindex`).

## Publish with GitHub Pages

1. Put these files in the root of a repository.
2. In the repository, open Settings, then Pages.
3. Under "Build and deployment", choose "Deploy from a branch", pick `main` and `/ (root)`, and save.
4. After a minute the site is live at `https://<owner>.github.io/<repository>/`.

On a free GitHub plan, Pages needs a public repository, so everything in it is public.

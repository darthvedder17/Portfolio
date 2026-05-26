# Shorya Sharma Portfolio

This is a free static portfolio website built with plain HTML, CSS, and JavaScript.

## Local preview

Open [index.html](/Users/shauryasharma/portfolio-website/index.html) in a browser, or run:

```bash
cd /Users/shauryasharma/portfolio-website
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Free deployment options

### GitHub Pages

This folder already includes a GitHub Pages workflow at `.github/workflows/deploy-pages.yml`.

1. Create a new GitHub repository, for example `portfolio-website`.
2. Upload the files from `/Users/shauryasharma/portfolio-website` to the `main` branch.
3. In GitHub, go to `Settings` -> `Pages`.
4. Under `Build and deployment`, set `Source` to `GitHub Actions`.
5. Push to `main` and wait for the `Deploy static site to GitHub Pages` workflow to finish.
6. Your site will be published for free at a `github.io` URL shown in the workflow and Pages settings.

If you want the site at `https://<your-username>.github.io/`, name the repository `<your-username>.github.io`.
If you use any other repository name, the URL will be `https://<your-username>.github.io/<repository-name>/`.

### Netlify

1. Create a free Netlify account.
2. Drag the folder into Netlify Drop or connect a GitHub repo.
3. No build command is required.
4. Publish the site.

## Next edits

- Replace the LinkedIn URL if needed.
- Add a GitHub link if you want one in the hero or contact section.
- Add project screenshots later if you want a stronger visual case study section.

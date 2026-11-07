# Brett D. Vincenzini — Portfolio

A standalone, responsive portfolio built with HTML, CSS, and vanilla JavaScript. No dependencies, build step, or API keys are required.

## Preview locally

Open `index.html` directly in a browser, or serve this folder with:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Upload to GitHub

Create an empty GitHub repository. Extract this ZIP, then upload the contents of this folder (so `index.html` is at the repository root). Alternatively initialize Git here and push to your repository:

```sh
git init -b main
git add .
git commit -m "Add portfolio website"
git remote add origin YOUR_REPOSITORY_URL
git push -u origin main
```

## Host on GitHub Pages

In the repository settings, open Pages, choose **Deploy from a branch**, select **main** and **/ (root)**, then save. GitHub will provide the published URL. Relative asset paths support both repository and custom-domain hosting.

## Edit the site

- `index.html`: Home, About, Projects introduction, Contact, and homepage featured card.
- `app.js`: project data, filters, and expanded project dialogs. `cardTitle` controls the card heading; `title` retains the full project/manuscript title in its dialog; `summary` controls card descriptions.
- `style.css`: responsive layout, typography, and colors.
- `assets/`: project graphics and downloadable résumé.

The first project card and homepage featured card share matching copy; update both when changing that text. Contact details and the résumé are included as displayed on the existing site. A public repository or GitHub Pages site makes these files publicly accessible.

This export contains no hosting credentials or original service configuration. No open-source license is assigned by this package.

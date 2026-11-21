# Portfolio website — deployment-ready

This is a static HTML/CSS/JavaScript website. No Node.js, npm, backend, database, or build command is needed.

## Folder structure

```text
portfolio_deploy_ready/
├── index.html          # Website home page
├── style.css           # Styling
├── script.js           # Menu and navigation
├── pict/               # Optional profile image
│   └── denji.jpg       # Included initials placeholder; replace with your own photo
└── README.md
```

## Before deployment

- Keep exact file names (`index.html`, `style.css`, `script.js`), including their letter case.
- The package contains a generic **JC placeholder image** at `pict/denji.jpg`, because your original photo was not uploaded. Replace that file with your real photo, using the exact same path and filename. If the image cannot load, the website also has an illustrated fallback.
- Customize the example email, GitHub, LinkedIn links, sample projects, and university.
- Open `index.html` locally to preview. For a server preview in VS Code, use Live Server.

## GitHub Pages

1. Create/open your GitHub repository.
2. Upload the **contents** of this folder to your branch's **repository root** (not inside another nested folder), and commit.
3. Go to **Settings → Pages → Build and deployment**.
4. Choose **Deploy from a branch**, select your published branch and **/(root)**, then save.
5. Visit the URL shown in the Pages settings when publishing is complete.

## Netlify and other static hosting

Upload the folder containing `index.html` as the site's publish directory. For drag-and-drop deployment in Netlify, drop the folder itself. No build command is required; publish directory is the folder containing `index.html`.

## Troubleshooting

- `404 Not Found`: Check whether `index.html` is at the published root and Pages' branch/folder are correct.
- Unstyled page: Check the case-sensitive path `/style.css` (the HTML references `style.css`).
- Mobile menu does not respond: Check `/script.js` (the HTML references `script.js`).
- Wrong profile photo: The included `pict/denji.jpg` is a placeholder, not your original image. Replace it with your photo, keeping the same path and filename.
- Use browser DevTools → Network to identify any missing resources (404 errors).

This package was checked for file naming, JavaScript syntax, and the local server's HTTP responses. It has not been tested on your specific hosting provider.

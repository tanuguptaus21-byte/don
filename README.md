# Ancient Egypt — History Project

A simple multi-page-style website (single scrolling page with sections) built
for a school history assignment on Ancient Egypt, ready to publish for free
on GitHub Pages.

## Folder structure

```
egypt-project/
├── index.html        ← main page (content, structure)
├── css/
│   └── style.css      ← all styling
├── js/
│   └── script.js       ← small script (personalizes footer name)
├── images/             ← put any images you add here (empty for now)
└── README.md            ← this file
```

Keeping CSS, JS, and images in their own folders (instead of all files loose)
is standard practice and makes the project easier to grade and extend.

## How to edit the content

- Open `index.html` in a text editor (VS Code, Notepad++, or even GitHub's
  web editor) and change the text inside each `<section>` to match your own
  research and writing.
- Update the **Sources** section with your real citations — don't leave the
  placeholders in for your actual submission.
- Add images: drop image files into the `images/` folder, then reference them
  in `index.html` like this:
  ```html
  <img src="images/pyramid.jpg" alt="The Great Pyramid of Giza">
  ```
- Change `Your Name` in `js/script.js` (or directly in the footer of
  `index.html`) to your actual name.

## How to publish it on GitHub Pages (free)

1. Go to [github.com](https://github.com) and log in (or create a free account).
2. Click the **+** icon (top right) → **New repository**.
   - Name it whatever you like, e.g. `ancient-egypt-project`.
   - Keep it **Public** (required for free GitHub Pages).
3. On the new repository page, click **Add file → Upload files**.
4. Drag in the whole folder structure above — `index.html`, the `css` folder,
   the `js` folder, and `images` folder — keeping the same file paths. Commit
   the upload.
5. Go to **Settings → Pages** (left sidebar).
6. Under **Source**, choose the `main` branch and `/ (root)` folder, then
   click **Save**.
7. Wait 1–2 minutes. GitHub will show a link like:
   `https://yourusername.github.io/ancient-egypt-project/`
8. Open that link — your project is now live. This is the link you can submit
   for your assignment.

## Notes for your teacher / submission

- No installation or server is required — this is a static site, so the link
  works directly in any browser.
- If your assignment requires a written report in addition to the webpage,
  you can still submit this URL as supplementary/interactive material.

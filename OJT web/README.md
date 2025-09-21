Personal Website

Simple static personal website with `index.html`, `about.html`, and `css/styles.css`.

Preview locally

- Open `index.html` in your browser.
- Or serve via a simple HTTP server, for example using Python 3:

```powershell
python -m http.server 8000
Start-Process "http://localhost:8000"
```

Customize

- Replace "Your Name" and `you@example.com` in the HTML files.
- Update colors in `css/styles.css`.

Social links

- Edit `index.html` and `about.html` to replace the `https://facebook.com/yourprofile` and `https://instagram.com/yourprofile` placeholders with your real profile URLs.

Images

- Replace `images/profile.svg` with your profile image. Recommended: square (480x480) in PNG, JPG, or SVG.
- Replace `images/bg.svg` to change the hero background, or update the `--hero-bg` CSS variable in `css/styles.css` to point to a different image or URL.

Experience images

- Replace `images/exp1.svg` and `images/exp2.svg` with your experience photos or diagrams. Recommended size: 1200×800 for good lightbox quality. Update captions in `index.html` inside the `<figcaption>` elements.

Navigation & Scrolling

- The site now uses in-page anchors (`#about`, `#contact`) and smooth scrolling. Use the nav to jump to sections on the page.

Transitions

- Feature cards use a subtle pop entrance and hover lift. These are controlled by `data-transition="pop"` on the feature elements and styles in `css/styles.css`.

Removed cursor effect

- The previous cursor follower has been removed. No extra UI follows the mouse.

Next steps

- Add a `projects.html` page and link to external projects.
- Add a small contact form with static form handling or third-party provider.

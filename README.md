# Yash Bhatia — Resume website

A responsive, dependency-free personal resume website built with HTML, CSS, and a small JavaScript enhancement for printing. All fonts and artwork are local; there are no analytics, external scripts, or contact-form services.

## Local preview

Open `index.html` directly in a browser, or run this command from the repository directory:

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

Visit <http://127.0.0.1:8000>. Stop the server with `Ctrl+C`.

The site works without JavaScript. With JavaScript enabled, **Print resume** opens the browser's print dialog; choose **Save as PDF** for a printable version of the verified website content.

## Responsive layout

The layout adapts to phone, tablet, laptop, and wide desktop screens in either orientation. Phones use stacked sections and compact navigation; tablets use two-column skill cards; larger screens use the full side-by-side hero and four-column skill grid. Navigation and action controls have touch-friendly targets of at least 44 pixels, and section links account for the sticky header.

## Editing

- `index.html`: resume content, navigation, and contact links.
- `styles.css`: visual design, responsive layouts, reduced-motion support, and print styles.
- `script.js`: progressively enhanced print button.
- `favicon.svg`: original local icon.

Content uses the supplied resume details and omits unverified tailored additions and numerical impact claims. The M.Tech is presented as ongoing, not as professional AI engineering experience. Certification validity is not asserted. No tailored source PDF is distributed.

## GitHub Pages

Public repository: <https://github.com/yashbhatia9800/yashbhatia9800.github.io>

Website: <https://yashbhatia9800.github.io/>

GitHub Pages publishes from the `main` branch's root directory. Changes pushed to that branch trigger a new deployment; no custom build step or dependencies are needed.

The public website includes the resume's email address, phone number, and LinkedIn link, as authorized for publication.
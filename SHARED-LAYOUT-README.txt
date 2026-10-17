GYM LABORATORY — Shared Header & Footer

The entire site now uses one header/footer source:

  site-shell.js  -> header/footer HTML + shared behavior
  site-shell.css -> header/footer appearance

Every page now contains only:
  <div data-site-header></div>
  ...
  <div data-site-footer></div>

Updated pages:
- index.html
- blog.html
- exercises.html
- blog1.html ... blog7.html
- coachingform.html

Future changes:
Edit site-shell.js / site-shell.css once and every page updates.

Keep your existing:
- images/
- locale.js

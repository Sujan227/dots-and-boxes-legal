# Dots & Boxes — website and legal pages

The public website for the Dots & Boxes: Brain Duel app, served with GitHub
Pages at https://sujan227.github.io/dots-and-boxes-legal/

- `index.html`: the home page (what the game is, rules, strategy, features,
  questions) with structured data for search and AI answer engines.
- `llms.txt`: a plain-text summary of the app and its pages for AI tools.
- `sitemap.xml`: submit it in Google Search Console and Bing Webmaster Tools.
- `img/`: web copies of the store icon, feature graphic and screenshots.
- `privacy-policy.html` and `delete-account.html`: linked from Google Play.

The home page, `llms.txt`, `sitemap.xml` and `img/` are edited here. Keep their
facts in step with the store listing (`docs/store/listing.md` in the app
repository) whenever a release changes what the app does, and update the
"Updated" date and the sitemap's `lastmod`.

The privacy policy and account deletion pages are generated. Edit the Markdown
in the app repository (`docs/legal/*.md`), run
`dart run tool/build_legal_pages.dart` there, and copy only
`privacy-policy.html` and `delete-account.html` here (not `index.html`).

The pages load no scripts: the Content-Security-Policy allows only inline
styles and images from this site.

Contact: shresthasujan227@gmail.com

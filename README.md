# arepee.me

Personal site for RP Pornmongkolsuk. Built on [Jekyll](https://jekyllrb.com/) (via the [Jekyll Now](https://github.com/barryclark/jekyll-now) starter) and hosted on GitHub Pages.

## Structure

- `_config.yml` -- site name, description, and social links
- `_posts/` -- blog posts (one file per post, named `YYYY-MM-DD-title.md`)
- `about.md`, `research.md`, `cv.md`, `gallery.html`, `contact.html` -- static pages
- `_layouts/`, `_includes/`, `_sass/`, `style.scss` -- theme files

## Editing content

- **Blog post:** add a new file to `_posts/` following the naming pattern above.
- **About / Research / CV:** edit the corresponding `.md` file directly (Markdown).
- **Gallery:** edit `gallery.html`; replace placeholder `<div>` items with `<img>` tags (see comment in the file).
- **Contact:** edit the list in `contact.html`.

## Local development

```
gem install github-pages
git clone https://github.com/rpornmon/rpornmon.github.io.git
cd rpornmon.github.io
jekyll serve
```

Then view at http://127.0.0.1:4000/

## Deploying

Commit and push to `master` -- GitHub Pages rebuilds automatically. Live at https://www.arepee.me/

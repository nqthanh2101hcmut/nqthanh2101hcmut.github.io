# Thanh Nguyen — academic homepage

Source for <https://nqthanh2101hcmut.github.io/personalpage>, built with
[Jekyll](https://jekyllrb.com/) on the
[academicpages](https://github.com/academicpages/academicpages.github.io)
template and deployed automatically by GitHub Actions
(`.github/workflows/jekyll.yml`) on every push to `master`/`main`.

## Where things live

| What you want to change | File / folder |
| --- | --- |
| Name, bio, sidebar links, site description | `_config.yml` (the `author:` block) |
| Header menu | `_data/navigation.yml` |
| Landing page (About, research interests, news) | `_pages/about.md` |
| CV page | `_pages/cv.md` (Markdown) or `_data/cv.json` (JSON version at `/cv-json/`) |
| Papers | one file per paper in `_publications/` |
| Research projects | one file per project in `_portfolio/` |
| Teaching | one file per entry in `_teaching/` |
| Blog posts | `_posts/` (dated filenames, e.g. `2026-08-04-title.md`) |
| PDFs, slides, bibtex | `files/` |
| Photos, avatar | `images/` |

## To-do after the first deploy

1. Fill in `author.linkedin` (username only) and, if you have one,
   `author.orcid` in `_config.yml`.
2. Replace the placeholder dates in `_publications/*.md` with the real issue
   dates, and add volume/issue/pages to each `citation:` field.
3. Add `paperurl:` (and optionally `slidesurl:`, `bibtexurl:`) to each
   publication once the journal links or PDFs are available. Put the PDFs in
   `files/`.
4. Optional: switch the sidebar picture from the illustration to a photo by
   setting `author.avatar: "thanh-nguyen.jpg"` in `_config.yml`.
5. Optional: pick a different colour scheme with `site_theme` in `_config.yml`
   (`default`, `air`, `contrast`, `dirt`, `mint`, `sunrise`). Previews are in
   `images/themes/`.
6. To turn the blog back on, add a post to `_posts/` and uncomment the "Blog"
   entry in `_data/navigation.yml`.

## Running it locally

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open <http://localhost:4000/personalpage>.

The template is MIT licensed; see `LICENSE`.

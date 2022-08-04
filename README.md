# Koon's Hugo Theme

A simple Hugo theme forked from Luke Smith.

## get started

```sh
hugo new site new-site
cd new-site
git clone https://github.com/k2on/kugo themes/kugo
echo "theme = 'kugo'" >> config.toml
cp themes/kugo/static/style.css static/
```

## stuff

- Makes one RSS feed for the entire site at `/index.xml`
- Stylesheet is in `/style.css` and includes some important stuff for partials.
- If a post is tagged, links to the tags are placed at the bottom of the post.
- `nextprev.html` adds links to the Next and Previous articles to the bottom of a page.
- `taglist.html` links all tags an article is tagged to for related content.

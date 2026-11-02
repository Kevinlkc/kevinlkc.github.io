# kaichengluo.com

Source for [kaichengluo.com](https://kaichengluo.com), built with Jekyll and published through GitHub Pages.

## Main content

- `_pages/about.md` — homepage and research summary
- `_data/navigation.yml` — navigation links
- `files/` — CV and paper drafts
- `images/` — profile and site images

## Local preview

With a current Ruby 3.x installation:

```sh
bundle install
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```

Repository-only files and development artifacts are listed under `exclude` in `_config.yml` so they are not published or added to the sitemap.

The site is based on the Academic Pages/Minimal Mistakes Jekyll theme. See `LICENSE` for licensing information.

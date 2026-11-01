# Dongwon Yang — Academic Homepage

Jekyll homepage for https://yang2919.github.io.

## Local preview

```sh
bundle install
bundle exec jekyll serve --host 127.0.0.1 --port 4000 --livereload
```

Open http://127.0.0.1:4000. Content changes rebuild automatically; restart the server after editing `_config.yml`.

## Update content

- Profile, photo and optional CV: `_data/profile.yml`
- Navigation: `_data/navigation.yml`
- Homepage sections: `_data/display.yml`
- Publications: add Markdown files to `_publications/` with `title`, `date`, `authors`, `pub`, `pub_date`, `cover_text`, and `selected` front matter.
- News: add Markdown files to `_news/` with `title` and `date` front matter.
- Activities: add Markdown files to `_showcase/` with `title`, `date`, `group`, `show: true` front matter and activity content below it.
- Documents and profile photos: `assets/files/` and `assets/images/photos/`.

`_site/` is generated output; edit source files instead.

Based on the academic-homepage template by Shitong Luo. See LICENSE.

# Dawn

A theme for hexo

## Usage

```
git clone git@github.com:orctom/dawn.git themes/dawn
```

And enable it in /_config.yml `theme: dawn`

## Config
/themes/dawn/_config.yml

### comments
Register your own [disqus](https://www.disqus.com) account and add `disqus_shortname: <your-site-id>` in `_config.yml`.

### Mathjax
Add `mathjax: true` to to `/_config.yml`

### Tags & Categories

Create two folders under your `source` directory: `tags` and `categories`.

Create an `index.md` file under each folder that you've just created.

`tags/index.md`:

```markdown
layout: tags
title: tags
---
```

`categories/index.md`:

```markdown
layout: categories
title: categories
---
```

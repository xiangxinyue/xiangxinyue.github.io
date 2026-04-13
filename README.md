# Xinyue Xiang

Personal website and portfolio for [xiangxinyue.com](https://xiangxinyue.com), built with Jekyll and hosted on GitHub Pages.

## What is in this site

- Homepage with positioning, skills, and working style
- Projects page for public work, research output, and representative professional systems
- About page with experience and education
- A hidden `more about me` page reached through the small floating objects

## Stack

- Jekyll
- GitHub Pages
- Sass
- Markdown + HTML layouts

## Local development

Install dependencies:

```bash
bundle install
```

Run locally:

```bash
bundle exec jekyll serve --host 127.0.0.1 --port 4000
```

Open:

```text
http://127.0.0.1:4000/
```

## Deployment

This repository is the GitHub Pages user-site repository:

```text
xiangxinyue.github.io
```

Pushing to `master` publishes the site through GitHub Pages. A custom domain is configured through `CNAME`.

## Notes

- Build artifacts and local dependency directories are ignored through `.gitignore`
- Logos and images used by the site live in [images](/Users/xinyuexiang/Desktop/xiangxinyue.github.io/images)
- Main pages live in [index.html](/Users/xinyuexiang/Desktop/xiangxinyue.github.io/index.html), [about.md](/Users/xinyuexiang/Desktop/xiangxinyue.github.io/about.md), [projects.md](/Users/xinyuexiang/Desktop/xiangxinyue.github.io/projects.md), and [more-about-me.md](/Users/xinyuexiang/Desktop/xiangxinyue.github.io/more-about-me.md)

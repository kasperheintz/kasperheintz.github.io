# Kasper E. Heintz: personal website

A minimal Jekyll site built and hosted for free by GitHub Pages. Every page is one Markdown file, and you don't need to install anything.

## How to update (on github.com)

1. Open the file you want to change (see table below) and click the ✏️ pencil icon.
2. Edit the text.
3. Click **Commit changes**. The site updates in about a minute.

| To change...                         | Edit this file           |
|--------------------------------------|--------------------------|
| About text, news, open positions     | `index.md`               |
| Research descriptions                | `research.md`            |
| Group members and alumni             | `group.md`               |
| Selected publications                | `publications.md`        |
| Public talks and teaching            | `outreach.md`            |
| CV summary                           | `cv.md`                  |
| Name, tagline, email, links, menu    | `_config.yml`            |
| Colours and fonts                    | `assets/css/style.css`   |

**Upload files** (photo, CV): go to the `images/` or `files/` folder, click *Add file → Upload files*.
- Profile photo: upload `profile.jpg` to `images/`, then change `/images/profile.svg` to `/images/profile.jpg` in `index.md`.
- CV: upload as `files/cv.pdf` (just overwrite it to update).

**Add a new page:** create `newpage.md` starting with

```
---
title: New page
---
```

and add it to the `navigation:` list in `_config.yml`.

## Markdown cheat sheet

```
**bold**   *italic*   [link text](https://...)
## Section heading
- list item
```

## First-time setup

1. In your `keheintz.github.io` repository, delete the old files (or archive them in a branch first).
2. Upload all files from this folder, keeping the folder structure.
3. *Settings → Pages*: Source = **Deploy from a branch**, branch = `main`, folder = `/ (root)`.

## Placeholders to fill in

Search for `YOUR-EMAIL`, `YYYY`, `Name Surname` and `Paper title`.

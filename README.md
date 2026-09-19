# jlempidakis.github.io

Personal site of Ioannis Lempidakis — live at **https://jlempidakis.github.io**

Hosted free on GitHub Pages. Every change you commit on github.com goes live in about a minute.

## Post a progress update
Open `_data/updates.yml` → pencil icon → add a block at the bottom → **Commit changes**:

```
- date: 2026-10-15
  project: grid-intelligence
  text: What happened, in one or two sentences.
```

`project` is the project's file name in `_projects/` without `.md`. The update shows on that project's timeline, on its card, and in "Recent progress" on the home page. Optional: `image: /assets/projects/some-photo.jpg`.

To mark a project finished, change `status: Active` to `status: Completed` in its file.

## Add a photo
1. Open the `assets/photos` folder on github.com.
2. **Add file → Upload files**, drag in your pictures, **Commit changes**.
3. They appear in a Photos section automatically (the section and its menu link stay hidden until the folder has at least one photo). The file name becomes the caption, so name them like `windsurfing-crete.jpg`.

Tip: phone photos are large. Resize to ~2000px on the long side first, and phone photos can carry GPS location. On a Mac, *Preview → Tools → Show Inspector → GPS → Remove Location Info* before uploading.

## Add a project
1. Open the `_projects` folder → **Add file → Create new file**.
2. Name it e.g. `my-new-project.md` and paste:

```
---
title: My New Project
subtitle: One line about what it is
date: 2026-10-01
order: 7
tags: [Python, Energy]
image: /assets/projects/my-new-project.jpg
gallery:
  - /assets/projects/my-new-project-2.jpg
links:
  - label: GitHub
    url: https://github.com/...
---

Write the description here. Normal text, **bold**, and
- bullet points
all work.
```

3. **Commit changes.** `order` controls position on the home page (1 = first). `image`, `gallery` and `links` are optional — delete those lines if unused. Upload any images for it into `assets/projects/`.

## Edit your bio, experience, education, skills
Everything on the home page lives in `_data/profile.yml`. Click the file → pencil icon → edit the text → **Commit changes**. Keep the indentation as it is.

## Change the headshot
Upload a new image to `assets/img/` named `headshot.jpg` (replace the old one).

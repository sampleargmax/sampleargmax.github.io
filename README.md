# sampleargmax.github.io

Personal academic homepage for [Your Name].

Live at: https://sampleargmax.github.io

## Structure

```
index.html    — main page (bio, news, publications, education, experience)
style.css     — all styles, no frameworks
photo.jpg     — profile photo (add your own)
cv.pdf        — CV (add your own)
```

## Editing guide

| What to update | Where |
|---|---|
| Name, bio, contact links | `index.html` → `<header class="profile">` |
| News items | `index.html` → `<section id="news">` |
| Research interests | `index.html` → `<section id="research">` |
| Papers | `index.html` → `<section id="publications">` |
| Education | `index.html` → `<section id="education">` |
| Experience | `index.html` → `<section id="experience">` |
| Colors / fonts | `style.css` → `:root` variables |

## Adding a profile photo

Drop a `photo.jpg` (or `.png`) in the root directory. Recommended: square crop, ≥ 300×300 px.
If no photo is provided, the page shows an initials placeholder automatically.

# Yue (Luna) Xiao — Personal Website

Plain HTML/CSS, no build step. Hosted on GitHub Pages.

## Structure

| File | Content |
|------|---------|
| `index.html` | Bio, funding, selected publications; sidebar with contact, classes, news |
| `publications.html` | Full publication list |
| `students.html` | Advised students and recruiting info |
| `teaching.html` | Courses, mentoring |
| `activities.html` | Awards, bug bounties, talks, professional service |
| `press.html` | Media coverage |
| `assets/css/style.css` | All styling (colors in `:root`) |

## Common edits

- **Add news**: add a `<li>` at the top of the News list in `index.html`.
- **Add a paper**: copy a `<li class="pub">` block in `publications.html`.
- **Add a student**: add a `<li>` in `students.html`.

## Preview locally

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

# Custom Jekyll Theme · Programming Lessons & Visual Projects

A minimalist but flexible Jekyll theme designed for hosting programming tutorials (as _lessons_) and creative or visual coding showcases (as _projects_) on **GitHub Pages**.

### Quick start

1. **Download / clone** this repository’s contents into the root of your `USERNAME.github.io` repository.
2. Commit & push; GitHub Pages will build the site using its built‑in Jekyll runner (3.9.5 as of 2025‑01‑30).
3. Create new content:

```bash
# A new lesson
mkdir -p _lessons
cp _lessons/template.md _lessons/my-first-lesson.md

# A new project
mkdir -p _projects
cp _projects/template.md _projects/cool-visualization.md
```

4. Visit `https://USERNAME.github.io` after the build completes.

### Local preview (optional)

If you have Ruby, Bundler & Jekyll locally:

```bash
bundle install --path vendor/bundle
bundle exec jekyll serve
```

### Collections

* **Lessons**→ `_lessons/*.md`   `layout: lesson`
* **Projects**→ `_projects/*.md`  `layout: project`

Feel free to tweak layouts, CSS, or add plugins when building with GitHub Actions for Jekyll 4+.

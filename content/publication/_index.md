---
title: Papers
cms_exclude: true

# View.
view: citation

# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''

design:
  # Default section spacing
  spacing: "6rem"

sections:
- block: collection
    id: papers
    content:
      title: Papers
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: article-grid
      columns: 2
      hide_date: true

---

# Challenge: WanderNote — Convert Divs to Semantic HTML

## Objective

You are given a **div-heavy** 2010s-style page. Convert it into a clean, accessible, **semantic HTML** layout
while **preserving the visual design** (CSS already targets ids/classes so your semantic swap won't break).

## Tasks

1. Open `Unsolved/index.html` and **replace structural `<div>` elements** with semantic tags:
   - `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`
2. Keep class/id names the same so existing CSS continues to work.
3. Add meaningful `alt` text to images and accessible link text.
4. Ensure headings follow a logical order (e.g., one `<h1>`, then `<h2>` for sections).

## Acceptance Criteria

- Visual layout remains intact.
- Semantic elements used appropriately.
- All images have meaningful `alt` attributes.
- Headings are logical and accessible.

> **Note:** Plain selectors only this week. No pseudo-classes required.

## Proposed Solution

- Converted element tags to use semantic tags where relevant.
- Re-ordered elements where relevant to meet semantic element patterns.
- Introduced new elements in opportunities to provide more semantic meaning and structure (e.g. figure and figcaption).
- Updated #left-panel to include css style for spacing inbetween child card elements.
- Updated figure element to remove margin and enable post-img to take up more width within a card for improved visual alignment.
- Adjusted size and crop of the hero-img to reduce scroll to additional sections.
- Updated tag link style to be consistent with nav link style.

## Questions

- When to use a section vs. a div?
  - A section defines a self-contained block of content and should include a header, whereas a div has no semantic meaning and is more commonly used for layout and visual organization.
- Should <figcaption> text be wrapped in a <p> tag?
  - No, it should not be wrapped in a p tag.

---

### 🌐 Note on Images

This project uses external images from Unsplash and Picsum.
You'll need an active internet connection for them to appear.
If you prefer to work offline, replace the image URLs with local files in an `images/` folder.

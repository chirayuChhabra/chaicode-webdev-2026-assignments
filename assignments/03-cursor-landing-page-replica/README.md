# Cursor Landing Page Replica

This project is an assignment focused on creating a static website clone of the Cursor Editor landing page.

## About The Project

- Goal - replicate the landing page look and feel using modern HTML and CSS.
- It is a static frontend project (no backend/framework logic).

## Note For Reviewers

This assignment uses **newer CSS syntax**, including **nesting with `&`**.  
Please review it with that in mind, since this style is intentionally used across the project.

### Old CSS (without `&`)

```css
.nav-link {
  color: #cfcfcf;
}

.nav-link:hover {
  color: #fff;
  text-decoration: underline;
}

.nav-link.active {
  color: #fff;
}
```

### New CSS (with `&`)

```css
.nav-link {
  color: #cfcfcf;

  &:hover {
    color: #fff;
    text-decoration: underline;
  }

  &.active {
    color: #fff;
  }
}
```

The project intentionally uses the **new `&` nesting style**.

## Side Note

Even though responsiveness was not required, I still used `clamp()` in multiple places for better fluid scaling.

## Live Demo

[Click Me](https://chirayuchhabra.github.io/chaicode-webdev-2026-assignments/assignments/03-cursor-landing-page-replica/)

## What I Learned Most

- Cleared confusion between `padding` vs `margin`.
- Better understanding of when to use Flexbox vs Grid.

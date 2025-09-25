# 2HatsLogic-Coding-Test

## Project Setup

This is a simple e-commerce homepage project using HTML, CSS, and Bootstrap.
Note: As this is a simple static webpage, node module dependencies are excluded to keep it lightweight and avoid unnecessary performance overhead.

**Open the Project**

- Open `index.html` in your web browser to view the homepage.

### Customization

- Update styles in [`css/style.css`](css/style.css).
- Replace or add images in the [`images/`](images/) folder.
- Update fonts in the [`fonts/`](fonts/) folder if needed.
- Edit content directly in [`index.html`](index.html).

### Dependencies

- [Bootstrap 5.0.2](https://getbootstrap.com/)
- [Font Awesome 7.0.1](https://fontawesome.com/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [Google Fonts: Poppins](https://fonts.google.com/specimen/Poppins)
- Proxima Nova (via local CSS)

### Notes: Accessibility & Responsiveness

- The layout is fully responsive: hero section and product grids adapt for mobile, tablet, and desktop.
- Focus outlines are restored for accessibility (`outline: revert;` for focusable elements).
- The `<footer>` is placed outside the `<main>` tag, following HTML5 semantic best practices.
- Additionally Equal space has been given under project & product headings.
- No JavaScript frameworks or build tools are required.

## Chrome Lighthouse Report

| Category       | Score |
| -------------- | ----- |
| Performance    | 84%   |
| Accessibility  | 88%   |
| Best Practices | 100%  |
| SEO            | 100%  |

_Scores are based on Chrome Lighthouse audit of the current project version._

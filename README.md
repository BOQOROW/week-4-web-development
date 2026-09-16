# SpendWise Dashboard Shell

A responsive financial dashboard layout built with CSS Grid, Flexbox, and CSS Variables.

## Features
- **CSS Grid Layout:** Powers the overall multi-column page structure and the responsive card container.
- **Flexbox Alignment:** Aligns interior elements inside the sidebar, header, and individual category cards.
- **CSS Custom Properties:** Configured theme variables (`--brand-color`, `--bg-color`, `--primary-text`, etc.) on `:root` for color management.
- **Micro-Interactions:** Custom 200ms transform and shadow animations triggered on card hover and keyboard focus.
- **Responsive Media Query:** Automatically adjusts to a single-column layout on viewport widths smaller than 768px.
- **Dark Mode Support:** Utilizes `@media (prefers-color-scheme: dark)` to override root CSS variables for system dark theme preferences.

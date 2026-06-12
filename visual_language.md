# Core Visual Language and Design Tokens

## Color Palette
* **Primary:** Aegis Blue (Brand identity, primary actions).
* **Secondary:** Slate Gray (Secondary actions, subtle backgrounds).
* **Accent:** Electric Teal (Highlights, active states).
* **Neutral:** White to Charcoal (Backgrounds, text hierarchy, borders).
* **Semantic:** * Success: Emerald Green
    * Warning: Amber Yellow
    * Error: Crimson Red
    * Info: Ocean Blue

## Typography
* **Font Families:** 'Inter' (sans-serif) for UI elements; 'Roboto Mono' for code snippets/data.
* **Scale:** Defined using a major third scale (e.g., 12px, 16px, 20px, 25px, 31px).
* **Weights:** Regular (400), Medium (500), Bold (700).

## Spacing & Layout
* **Grid System:** 12-column responsive fluid grid with customizable breakpoints (Mobile, Tablet, Desktop).
* **Spacing Units:** Base-4 pixel system (4px, 8px, 12px, 16px, 24px, 32px, 48px, 64px).

## Elevation & Iconography
* **Elevation:** 4 levels of z-index depth represented by increasingly soft drop shadows (Resting, Hover, Modal, System Overlay).
* **Iconography:** SVG-based, 24x24px grid, 2px stroke weight, rounded caps for friendly yet professional aesthetics.

## Design Tokens
All visual properties are abstracted into platform-agnostic key-value pairs (e.g., `color-brand-primary: #0052CC`, `spacing-md: 16px`) to ensure automatic synchronization across Figma, CSS/Sass, and mobile platforms.

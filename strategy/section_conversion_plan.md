# Scientific Luxury: Section Conversion Plan

This plan outlines how we will take high-end website examples (regardless of their original style) and translate them into your "Scientific Luxury" aesthetic (Light Pink/White with Tyrian Purple accents).

## Proposed Changes

### [Component] Design System (CSS Tokens)

We will use the existing CSS variables from `styles.css` to act as our "Translation Engine." This ensures every section we convert feels part of the same cohesive brand.

#### [MODIFY] [styles.css](file:///Users/lauraoconnor/Downloads/antigravity-website/styles.css)
- We will strictly follow these existing tokens:
  - `--color-bg-base`: `#FAFAF9` (Alabaster / High-End Paper)
  - `--color-text-main`: `#1A1A1A` (Deep Charcoal)
  - `--color-accent`: `#66023C` (Tyrian Purple)
  - `--color-accent-light`: `#F7EBED` (Secondary Pink highlighting)
  - `--glass-bg`: `rgba(255, 255, 255, 0.6)`
  - `--font-heading`: `'Instrument Serif', serif`
  - `--font-body`: `'Newsreader', serif`

---

### [Component] Conversion Workflow

For each section you provide, I will follow this "Snippet Translation" process:

1.  **Structure Preservation**: Keep the exact HTML structure and class names from the source (e.g., Apple, Opal, or high-end agency sites).
2.  **Aesthetic Override**: Map the source's colors and fonts to our "Scientific Luxury" tokens.
    - **Universal Light Base**: All sections maintain the light pink/white base. NO "Dark Purply" backgrounds.
    - **Atmospheric Enforcement**: Ensure the `body::after` HQ Cloud overlay and white flares are visible and consistent across all converted sections.
3.  **Copy Replacement**: Swapping out placeholder text for your "Economic Decoding" and "Contoured Method™" copy **after** the core sections are established.
4.  **Layout & Aesthetic Orientation**:
    - **Color Flip Strategy**: All source examples (even those in dark mode/black) will be "flipped" into the Scientific Luxury palette: Alabaster (`#FAFAF9`), Tyrian Purple (`#66023C`) as accent only, and Pink highlight (`#F7EBED`).
    - **Horizontal DDD**: The BBB/DDD frameworks will use a horizontal flex/grid layout as shown in the screenshots.
    - **Animated Phone Flip**: Implementing the Left-to-Right flipping animation for the phone mockup, cycling visuals.

## Verification Plan

### Automated Tests
- No automated tests required for this UI-heavy task.

### Manual Verification
1.  **Visual Check**: I will use the browser tool to capture screenshots of each converted section to ensure:
    - The layout remains intact (matching your visual guide).
    - The colors correctly follow the Scientific Luxury palette.
    - Interactivity (scroll animations, hovers) works as expected.
2.  **Responsive Check**: Verify the sections look premium on both desktop and mobile mockups.

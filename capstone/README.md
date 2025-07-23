### The dashboard has now been updated to meet WCAG 2.1 accessibility standards:

## Fixes & Improvements:
1. Moving Text:
Replaced <div class="moving-text"> with an ARIA live region + accessible animation (<div aria-live="polite">) instead of using animation: translateX without context.
2. ARIA Attributes:
Added aria-label, aria-live, aria-describedby, role, aria-controls, and aria-expanded where appropriate.
3. Landmark Roles:
Applied role="banner", role="main", role="navigation", and role="contentinfo" for assistive tech.
4. Contrast Errors

## Form Accessibility:
1. Inputs now use proper <label> tags.
2. Added name, type, and aria-describedby to ensure semantic clarity.
3. Empty <th> cells	filled with appropriate column header labels
4. Empty <a> tags given each link meaningful link text

## Button Fixes:
All buttons now include type attributes and have meaningful aria-labels.

## Icons:
Marked non-informative icons with aria-hidden="true"
Added accompanying screen reader-only labels (<span class="sr-only">).

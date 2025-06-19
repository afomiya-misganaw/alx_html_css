# Headphones Company Website

A responsive website for a headphone company with desktop and mobile layouts.

## Features

- Fully responsive design (breaks at 480px)
- Interactive elements with hover/active states
- Clean CSS reset foundation
- Content max-width of 1000px centered on page

## Design Specifications

### Colors
- Primary: Brand colors from Figma
- Link states: `#FF6565` (hover/active)
- Button hover/active: `opacity: 0.9`

### Typography
- Source Sans Pro (Body text)
- Spin Cycle OT (Headings)
- Fallback to system sans-serif fonts

### Layout
- Max content width: 1000px (centered)
- Mobile breakpoint: 480px and below

## Implementation Notes

1. **CSS Reset** included to ensure consistent baseline
2. **Responsive Breakpoint**:
   ```css
   @media (max-width: 480px) {
     /* Mobile-specific styles */
   }

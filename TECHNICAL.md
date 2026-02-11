# Technical Documentation

This file documents technical decisions for future developers. Not intended for the project owner.

## Tech Stack

**Framework:** Astro
- Fast, lightweight, great for portfolio sites
- Easy content management
- Excellent performance out of the box

**Styling:** Tailwind CSS
- Utility-first for rapid development
- Easy to customize colors and design tokens
- Responsive design built-in

**Animations:**
- CSS animations for simple transitions
- Framer Motion (React) for complex interactions
- GSAP for scroll-triggered animations if needed

**Deployment:** TBD (likely Vercel or Netlify)

## Project Structure

```
/src
  /components     # Reusable UI components
  /layouts        # Page layouts
  /pages          # Site pages
  /content        # Project data and content
  /styles         # Global styles
/public           # Static assets (images, fonts)
```

## Design Tokens

Color palette, typography, and spacing will be defined in Tailwind config based on design direction:
- Warm, friendly colors
- Bold accents against neutral backgrounds
- Playful but professional

## Content Management

Projects stored as structured data for easy updates. Emma should be able to update project info without touching complex code.

## Performance Goals

- Lighthouse score 90+
- Fast initial load
- Smooth 60fps animations
- Optimized images

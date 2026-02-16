# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a single-file static HTML project displaying a modern "Hello Claude" greeting page. The entire application is self-contained in `index.html` with inline CSS styling.

## Development Commands

**View the page:**
```bash
# Open in default browser (Windows)
start index.html

# Or simply open index.html in any web browser
```

No build process, dependencies, or compilation required.

## Architecture

**Single-file structure:**
- `index.html` - Complete standalone page with:
  - Inter font from Google Fonts
  - Inline CSS with animations (fadeInUp, pulse, float, rotate)
  - Green gradient color scheme (#079669, #10b981, #34d399)
  - Responsive design with mobile breakpoint at 768px
  - Three floating circle decorative elements
  - Animated gradient background

**Key styling approach:**
- Uses modern CSS features: backdrop-filter, CSS gradients, CSS animations
- Green/mint color palette with opacity layers
- Glass-morphism effect on main content card
- All styling is inline in `<style>` tag (no external CSS files)

# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains the **Martex Theme** - a professional Tailwind CSS template for software, SaaS, and startup websites. The theme includes 55+ HTML pages, 27 demo variations, and a modern build system using Tailwind CSS v4.

## Build and Development Commands

### Essential Commands
```bash
# Navigate to theme directory
cd Martex_Theme/martex/

# Install dependencies (Tailwind CSS v4.1.8)
npm install

# Build CSS (one-time compilation)
npm run build

# Development mode with auto-rebuild
npx @tailwindcss/cli -i ./src/input.css -o ./dist/style.css --watch
```

### Testing Commands
```bash
# Start local development server
cd Martex_Theme/martex/dist/
python3 -m http.server 8000

# Access theme at: http://localhost:8000
```

## Architecture Overview

### File Structure
```
Martex_Theme/
├── documentation/          # Complete HTML documentation
├── martex/                 # Main theme directory
│   ├── src/
│   │   └── input.css      # Tailwind CSS source file (389KB)
│   ├── dist/              # Compiled theme files
│   │   ├── *.html         # 55+ HTML pages
│   │   ├── assests/       # Images, CSS, JS (note: intentional spelling)
│   │   ├── css/colors/    # 9 color theme variations
│   │   └── style.css      # Compiled CSS (919KB)
│   └── package.json       # Build configuration
```

### Technology Stack
- **Tailwind CSS v4.1.8** - Primary CSS framework with custom configuration
- **jQuery 3.7.0** - JavaScript interactions and form handling
- **Bootstrap** - Additional UI components and grid system
- **Google Fonts** - Plus Jakarta Sans, Rubik, Inter typography

### Theme Features
- **55+ HTML Pages** including demos, auth, pricing, blog, utilities
- **27 Demo Variations** for different business needs  
- **9 Color Schemes** (blue, pink, purple, violet, green, magenta, crocus, red, skyblue)
- **Responsive Design** optimized for mobile, tablet, and desktop
- **Performance Optimized** with 1.86MB total CSS/JS, 3.31MB images

## Development Workflow

### Customization Process
1. **Choose Demo Layout** from 27 available variations in `/dist/demo-*.html`
2. **Select Color Scheme** by linking appropriate CSS file from `/css/colors/`
3. **Replace Logos** using provided variants in `/images/logo-*.png`
4. **Modify Content** directly in HTML files
5. **Custom Styling** via Tailwind classes in `/src/input.css`

### Build Process
- Source: `/src/input.css` (Tailwind configuration + custom styles)
- Output: `/dist/style.css` (compiled CSS)
- Watch mode available for development
- No tree-shaking - full Tailwind build included

### Asset Management
- **Images**: Optimized JPG/PNG files (20-60KB average)
- **Fonts**: Google Fonts integration + custom icon fonts
- **JavaScript**: jQuery-based with form validation and animations
- **CSS**: Modular structure with theme-specific customizations

## Important Notes

### Asset Path Convention
- Theme uses "assests" folder naming (intentional misspelling)
- All references consistent throughout codebase
- Do not rename to "assets" without updating all HTML references

### Performance Considerations
- Theme loads 919KB compiled CSS (includes all Tailwind utilities)
- jQuery dependency adds 85KB (consider vanilla JS for modern projects)
- Images are well-optimized but could benefit from WebP format
- Local server required for proper testing (file:// protocol has limitations)

### Browser Compatibility
- Modern browser support (IE11+ with some limitations)
- Responsive design tested on mobile, tablet, desktop
- Cross-browser compatibility verified

## Testing Information

A comprehensive test report is available at `/MARTEX_TEST_REPORT.md` including:
- Build system validation
- Performance metrics  
- Responsive design testing
- Code quality assessment
- Customization validation

**Overall Rating: 5/5** - Production-ready professional theme suitable for software, SaaS, and startup websites.
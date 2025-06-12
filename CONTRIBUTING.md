# Contributing to Martex Theme Component Showcase

Thank you for your interest in contributing to this project! This guide will help you get started.

## 🤝 How to Contribute

### Reporting Issues
- Use the GitHub issue tracker
- Provide clear descriptions and steps to reproduce
- Include browser/device information if relevant

### Suggesting Enhancements
- Check existing issues first
- Clearly describe the enhancement and its benefits
- Consider the scope and complexity

### Code Contributions

#### Getting Started
1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Make your changes
4. Test thoroughly
5. Commit with clear messages
6. Push and create a pull request

#### Component Extraction Guidelines
When extracting new components (Features, Pricing, Testimonials, etc.):

1. **Preserve Authenticity**
   - Keep original HTML structure intact
   - Maintain all CSS classes and responsive breakpoints
   - Preserve JavaScript functionality

2. **Documentation**
   - Add clear component labels
   - Document unique characteristics
   - Include usage examples

3. **File Organization**
   - Follow existing naming conventions
   - Use consistent file structure
   - Update relevant catalogs

#### Code Standards
- **HTML**: Use semantic markup, maintain accessibility
- **CSS**: Follow Tailwind CSS conventions
- **JavaScript**: Ensure compatibility with existing scripts
- **Comments**: Add clear, helpful comments for complex sections

#### Testing Checklist
- [ ] All breakpoints work correctly
- [ ] Animations function properly
- [ ] Forms validate and submit
- [ ] Images load correctly
- [ ] No console errors
- [ ] Cross-browser compatibility

## 📋 Component Extraction Process

### For New Section Types (Features, Pricing, etc.)
1. **Research Phase**
   - Analyze all demo files for variations
   - Document unique patterns and layouts
   - Create extraction plan

2. **Implementation Phase**
   - Extract complete HTML sections
   - Preserve CSS dependencies
   - Maintain responsive behavior
   - Test all functionality

3. **Documentation Phase**
   - Create showcase file
   - Update component catalogs
   - Add usage examples
   - Document characteristics

## 🎯 Priority Areas

### High Priority
- Features sections extraction (F1-F15)
- Pricing sections extraction (P1-P15)
- Testimonials sections extraction (T1-T15)

### Medium Priority
- Footer variations extraction
- Navigation patterns
- Form components

### Low Priority
- Component picker interface
- Live preview functionality
- Theme customization tools

## 📝 Pull Request Guidelines

### Before Submitting
- Ensure all tests pass
- Update documentation
- Follow commit message conventions
- Rebase on latest main branch

### PR Description Template
```markdown
## Changes Made
- Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Component extraction

## Testing
- [ ] Tested on multiple browsers
- [ ] Responsive design verified
- [ ] Accessibility checked

## Screenshots (if applicable)
[Add screenshots showing the changes]
```

## 🛠️ Development Setup

### Prerequisites
- Modern web browser
- Text editor/IDE
- Git

### Local Development
1. Clone the repository
2. Open showcase files in browser
3. Make changes and test locally
4. Use browser dev tools for debugging

### File Structure Understanding
```
Martex_Theme/
├── martex/dist/
│   ├── MARTEX_HERO_SHOWCASE.html    # Main showcase
│   ├── demo-*.html                  # Source files
│   └── assets/                      # CSS, JS, images
└── documentation/                   # Theme docs
```

## 📞 Getting Help

### Resources
- Project README.md
- Component catalog documentation
- CLAUDE.md for project context

### Contact
- Open an issue for questions
- Use discussions for general topics
- Tag maintainers for urgent matters

## 🏆 Recognition

Contributors will be recognized in:
- README.md contributors section
- Release notes
- Project documentation

Thank you for contributing to making this component library better! 🎉
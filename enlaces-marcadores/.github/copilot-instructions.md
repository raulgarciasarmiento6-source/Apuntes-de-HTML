# AI Agent Instructions for HTML Learning Materials Project

## Project Overview
This is an educational HTML project focused on demonstrating HTML concepts, particularly anchor tags and internal page navigation using ID markers (bookmarks).

## Project Structure
- Single HTML file (`index.html`) structured as a mock news website
- Demonstrates semantic HTML and internal page navigation

## Key Patterns and Conventions

### HTML Structure
- Uses HTML5 doctype and semantic markup
- Spanish language content with appropriate character encoding (UTF-8)
- Responsive viewport meta tag implementation

### Navigation Pattern
- Internal page navigation using anchor tags (`<a href="#section-id">`)
- Section IDs match navigation link references
- Navigation links placed at the top of the content for easy access

### Content Structure
- Hierarchical heading structure (h1 -> h2 -> h3)
- Main title: h1 for site name
- Subtitle: h2 for site tagline
- Section headers: h3 with matching IDs for navigation
- Content sections use paragraph tags for body text

### Naming Conventions
- Section IDs match their display text exactly
- Spanish language used for all IDs and content
- Consistent capitalization in section IDs

## Common Tasks

### Adding New Sections
When adding new sections:
1. Add navigation link at the top: `<a href="#NewSection">New Section</a>`
2. Create corresponding section with matching ID: `<h3 id="NewSection">New Section</h3>`
3. Add content paragraphs below the section header

### Maintaining Navigation
- Ensure ID case matches exactly between links and section IDs
- Place all navigation links together at the top of the body
- Update navigation when adding or removing sections

## Development Guidelines
- Maintain semantic HTML structure
- Preserve existing heading hierarchy
- Keep navigation links grouped together
- Match ID case sensitivity exactly for internal links
- Use UTF-8 encoding for Spanish language support

## Testing
Test internal navigation by:
- Clicking each navigation link
- Verifying smooth scroll to correct section
- Checking URL fragment updates correctly
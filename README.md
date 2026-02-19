Accessibility Audit Alishia Lockett

Tools Used
- Lighthouse (Chrome DevTools)
- axe DevTools (browser extension)
- Manual keyboard testing (Tab / Shift+Tab)

Audit Fixes


1. No skip link
Issue: Keyboard users had to tab through nav every time.  
Fix: Added skip link to `#main-content` and styled it to appear on focus.  
Files: index.html, style.css

2. Images missing alt text
Issue: Several images had missing/incorrect alt text.  
Fix: Added meaningful alt text
Files: index.html

3. Color contrast failures
Issue: Text/background contrast failed WCAG AA in multiple areas.  
Fix: Adjusted text and/or background colors in CSS to meet contrast standards.  
Files: style.css

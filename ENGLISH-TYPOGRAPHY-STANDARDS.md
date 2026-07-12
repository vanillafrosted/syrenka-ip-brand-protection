# English Website Typography Standards

**Effective: July 13, 2026**

## Body Text

### Standard Body Font Size
- **Size:** 19px
- **Font Family:** -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif
- **Line Height:** 1.8
- **Color:** RGB(75, 85, 99) — `var(--gray-text)`

### Application
Applied to:
- `.section p` — Article paragraphs
- `.section li` — Article list items

### Rationale
19px provides comfortable long-form reading on smartphones while maintaining balanced visual hierarchy on desktop. The larger font size prioritizes reading comfort over text density. This size was validated through testing on actual smartphone devices.

## Responsive Design

### Desktop (1200px+)
- Body font: 17px
- Line height: 1.8
- Content padding: 48px 40px

### Tablet (768px - 1199px)
- Body font: 17px (unchanged)
- Content padding: 32px 20px
- Article title: 32px (reduced from 42px)

### Mobile (< 768px)
- Body font: 17px (unchanged)
- Content padding: 24px 12px
- Article title: 32px (reduced from 42px)
- All article images scale responsively
- Single-column layout

## Headings
- **Article Titles:** 42px (desktop), 32px (tablet/mobile)
- **Section Headings (h2):** 28px
- **Subsection Headings (h3):** 20px
- **Font Weight:** 600-700

*Headings remain unchanged from original design. The typography update affects body text only.*

## Images & Visual Elements
- All image sizes remain unchanged
- Syrenka speech-bubble design remains unchanged
- Section spacing remains unchanged

## Future Application

This standard applies to:
1. All existing English articles
2. All future English articles published on the Syrenka English website
3. Any new pages using the `.section p` and `.section li` CSS patterns

## Implementation Notes

When creating new articles, use these CSS patterns:

```css
.section p {
    font-size: 19px;
    color: var(--gray-text);
    line-height: 1.8;
    margin-bottom: 16px;
}

.section li {
    font-size: 19px;
    color: var(--gray-text);
    line-height: 1.8;
    margin-bottom: 12px;
}
```

Or for pages using em-based sizing:

```css
body {
    font-size: 19px;
    line-height: 1.8;
}
```

---

**Changelog:**
- 2026-07-12: Initial standard established at 17px
- 2026-07-13: Refined to 19px based on smartphone readability testing

**Last Updated:** 2026-07-13
**Standard Version:** 2.0
**Approved By:** Maki

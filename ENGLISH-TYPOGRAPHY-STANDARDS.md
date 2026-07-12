# English Website Typography Standards

**Effective: July 12, 2026**

## Body Text

### Standard Body Font Size
- **Size:** 17px
- **Font Family:** -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif
- **Line Height:** 1.8
- **Color:** RGB(75, 85, 99) — `var(--gray-text)`

### Application
Applied to:
- `.section p` — Article paragraphs
- `.section li` — Article list items

### Rationale
17px improves readability on mobile devices while maintaining visual hierarchy on desktop. The 1px increase from 16px significantly improves smartphone reading experience without requiring layout adjustments.

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
    font-size: 17px;
    color: var(--gray-text);
    line-height: 1.8;
    margin-bottom: 16px;
}

.section li {
    font-size: 17px;
    color: var(--gray-text);
    line-height: 1.8;
    margin-bottom: 12px;
}
```

Or for pages using em-based sizing:

```css
body {
    font-size: 17px;
    line-height: 1.8;
}
```

---

**Last Updated:** 2026-07-12
**Standard Version:** 1.0
**Approved By:** Maki

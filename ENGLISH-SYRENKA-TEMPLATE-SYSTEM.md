# English Syrenka Visual Identity System - Master Documentation

**Version:** 2.0 (Current)
**Effective:** July 13, 2026
**Status:** Official standard for all English articles

---

## Official Master Template

**Location:** `/Users/jq/syrenka-ip-brand-protection/assets/syrenka/master/syrenka_master_v2.png`

**Status:** ✓ Approved and finalized
**Use:** Foundation for all future article-specific Syrenka illustrations
**Modification:** NEVER - The master template is permanent and immutable

---

## System Overview

The English Syrenka Visual Identity System uses a consistent master template across all 83+ articles. Each article receives a unique Syrenka image with localized English text, but the core character, design, and layout remain identical.

### Key Principle
> **Copy the master. Add only the text. Keep everything else unchanged.**

---

## Master Template Specifications

### Canvas
- **Size:** 1661 × 947 px
- **Background:** Pure white (#FFFFFF)
- **No transparency**

### Character (Syrenka)
All elements preserved exactly from master:
- Face and facial features
- Hair style and color
- Eyes and expression
- Clothing and proportions
- Outline style
- Position and scale

### Speech Bubble
All elements preserved exactly from master:
- Shape and position
- Size (larger than v1.0 to accommodate English text)
- Tail design
- Border thickness and style
- Border color
- Rounded corners
- Interior shadow effects
- White interior area for text

### Color Palette
All colors preserved exactly:
- Skin tones
- Hair color
- Clothing colors
- Speech bubble border
- Background white

---

## Text Specifications

### Typography
- **Font:** Helvetica Regular
- **Size:** 42 px (fixed, never reduced)
- **Color:** RGB(40, 40, 40)
- **Line Height:** 1.28
- **Alignment:** Left

### Positioning
- **X Position:** 735 px (from left edge)
- **Text Area Width:** Approximately 760 px
- **Vertical Centering:** Within allocated speech bubble area
- **Line Breaks:** Manual only (no automatic wrapping)

### Text Allocation Rules (Priority Order)

1. **MUST FIT:** Text must fit within speech bubble at 42px
2. **If text too long:** Shorten the text (contact Marcus/Maki)
3. **Never reduce font size** below 42px
4. **Never modify layout** or reposition text area
5. **Never redesign** or modify the speech bubble

**Layout integrity has absolute priority over text length.**

---

## Article-Specific Image Workflow

### For Each Article

1. **Source:** Copy the master template (syrenka_master_v2.png)
2. **Edit:** Add only the approved English speech-bubble text
3. **Verify:** Ensure all text fits and is fully visible
4. **Save:** As `/public/assets/images/articleXXX-syrenka-speech-bubble-final.png`

### Filename Format
- `article001-syrenka-speech-bubble-final.png` (Article No.1)
- `article003-syrenka-speech-bubble-final.png` (Article No.3)
- `articleXXX-syrenka-speech-bubble-final.png` (for article XXX)

### Verification Checklist
- ✓ Text fully visible inside speech bubble
- ✓ No text extends beyond right border
- ✓ Comfortable blank space around all text
- ✓ Text within vertical bounds
- ✓ Syrenka character unchanged
- ✓ Speech bubble design unchanged
- ✓ Canvas still 1661 × 947 px
- ✓ Saved as PNG with no transparency

---

## Implementation Across All Articles

**Current Status:**
- Article No.1 (why-syrenka-brand-guardian-story.html) — ✓ Using v2.0 template
- Article No.3 (court-postage-stamps-japan.html) — ✓ Using v2.0 template
- Prototype Article No.1 (when-product-images-stolen.html) — ✓ Using v2.0 template

**Future Articles:**
- All new articles created from this point forward use v2.0 master
- Apply same workflow and specifications
- Maintain consistency across entire 83-article project

---

## What NOT to Do

**Absolute Prohibitions:**

- ❌ Do NOT modify the master template file
- ❌ Do NOT edit master template to add article-specific text
- ❌ Do NOT change Syrenka's character or appearance
- ❌ Do NOT redesign or modify the speech bubble
- ❌ Do NOT change canvas dimensions
- ❌ Do NOT alter the color palette
- ❌ Do NOT reduce font size below 42px
- ❌ Do NOT reposition the text area
- ❌ Do NOT add decorative elements
- ❌ Do NOT add any transparency

---

## Previous Version (Archived)

**v1.0 Master:**
- **Location:** `/assets/syrenka/master/syrenkablankcolor.png`
- **Status:** Archived for historical reference
- **Use:** Do NOT use for new articles
- **Note:** Keep for version history tracking

**Why Archived:**
- v1.0 had smaller speech bubble area
- v2.0 has larger speech bubble for better English text accommodation
- v2.0 is the official standard going forward

---

## Roles and Responsibilities

### Richard (Design/Illustration)
- Creates article-specific Syrenka images
- Adds English text to master template copies
- Ensures text fits within specifications
- Verifies image quality before submission

### Marcus (Backend/Publishing)
- Receives completed Syrenka images
- Verifies images match specifications
- Integrates images into article HTML
- Manages file naming and locations

### Maki (Project Lead/Editorial)
- Approves speech-bubble text content
- Approves final Syrenka images
- Ensures alignment with brand guidelines
- Makes decisions on text fitting issues

---

## Troubleshooting

### Text Doesn't Fit

**Solution:** Contact Marcus immediately. Options:
1. Shorten the text (preferred)
2. Review alternative text proposals
3. Adjust line breaks to optimize fit

**Never:** Reduce font size without approval

### Unusual Speech Bubble Shape

**Solution:** If an article's context requires visual adjustments:
1. Contact Marcus/Maki for guidance
2. Minor pixel adjustments permitted only with approval
3. Core design must remain unchanged

### Color or Design Questions

**Solution:** Refer to this documentation and contact Marcus if clarification needed.

---

## Integration in Article HTML

Each article's HTML includes:

```html
<figure class="article-syrenka-quote">
    <img
        src="/assets/images/articleXXX-syrenka-speech-bubble-final.png?v=20260713-final"
        alt="Syrenka's reflection: [text excerpt]"
        class="syrenka-speech-bubble"
    />
</figure>
```

**Placement:** After article content, after Key Takeaways, before Disclaimer

**Cache-Busting:** Query string (e.g., `?v=20260713-final`) prevents browser caching of updated images

---

## Timeline

- **2026-07-12:** v1.0 master template established
- **2026-07-13:** v2.0 master template finalized
- **2026-07-13:** v2.0 declared official standard
- **2026-07-13:** This documentation created

---

## Summary

The English Syrenka Visual Identity System ensures consistency across all articles while allowing flexible text content. The v2.0 master template is the permanent foundation. All future work follows this specification.

**Master Template:** Permanent. Immutable. Sacred.

---

**Last Updated:** 2026-07-13
**Status:** Active
**Approval:** Maki
**Implementation Contact:** Marcus

# Editorial Handbook Status

## Current Status

**Editorial Handbook: Version 0.9**

**Ready for Prototype Validation**

---

## What This Means

The Editorial System has been fully designed and documented.

All foundational documents are complete:
- Project Vision (WHY)
- Editorial Manifesto (WHAT)
- Scene Bible (HOW scenes)
- Photo Guidelines (HOW photos)
- AI Workflow (HOW the team works)
- Editorial Checklist (Verification)
- Ray's World Library (Authentic facts database)
- Editorial Change Log (Historical record)

---

## Next Phase: Prototype Validation

Before declaring Version 1.0, the Editorial Handbook must be validated through production.

**Process:**

1. **Prototype Article No.1** — Completed using the Editorial Handbook
2. **Full Editorial Review** — All editorial processes tested
3. **System Validation** — Handbook principles proven in actual production
4. **Approval** — Maki approves Prototype Article No.1

Only after the Prototype is successfully completed and approved will the Editorial Handbook be declared Version 1.0.

---

## Articles 2–83 Timeline

Production of Articles 2–83 will NOT begin until:

- Prototype Article No.1 is complete
- Editorial Handbook is validated
- Version 1.0 is declared
- Editorial team is confident in the system

---

## Role Clarity

**Christopher** — Writes articles (Editor-in-Chief)

**Lucas** — Quality reviews for editorial consistency

**Nathan** — Fact verification and accuracy

**Marcus** — Supervises editorial consistency across system (CEO Editorial Review)

**Maki** — Final approval and project ownership

---

## Success Metrics for Prototype Validation

Prototype Article No.1 will be considered successful when:

- ✓ Editorial Manifesto principles are fully embodied
- ✓ Scene Bible techniques are correctly implemented
- ✓ Photo placeholders are properly positioned
- ✓ Ray's authentic voice is preserved throughout
- ✓ All team members confirm quality standards are met
- ✓ Readers feel they spent a day with Ray
- ✓ No invented details or scenes
- ✓ Timeline and facts are verified

---

## Version 1.0 Declaration

Version 1.0 of the Editorial Handbook will be declared when:

- Prototype Article No.1 is complete and approved
- All editorial processes have been tested and validated
- The team confirms the system works as designed

The declaration will be recorded in Editorial Change Log with the date and notes on what was learned.

---

## Current Phase Summary

PHASE CHANGE: Prototype Validation COMPLETE

Prototype Article No.1 is now LOCKED and APPROVED.

We are now entering PRODUCTION PHASE for Articles 2–83.

---

## Production Workflow: Established (2026-07-09)

### Architectural Separation: Narrative + Presentation

All English Syrenka articles follow this two-layer architecture:

#### Layer 1: Narrative Master (Permanent)
**File**: `Prototype_Article_##_Locked.md`
- Contains: Story only (pure narrative)
- Status: LOCKED, Version 1.0, Approved by Maki
- Purpose: Preserves the approved story exactly as written
- Timeless and unchanging
- No editing after approval

#### Layer 2: Presentation Layer (Flexible)
**File**: `Prototype_Article_##_Presentation.md`
- Contains: Website elements derived from narrative
  - SEO metadata
  - Hero image specifications
  - Key takeaways
  - Practical tips
  - Related articles
  - Disclaimer
  - Call to action
- Purpose: Enhances reader experience, optimizes for web
- Can be updated without changing narrative
- Marketing/presentation improvements here

### Single Source of Truth: Narrative Layer

**Master File**: `Prototype_Article_01_Locked.md`

This is the ONLY authoritative source for Article No.1 STORY.

- Version: 1.0 (LOCKED)
- Contains: Pure narrative only
- Approved by: Maki (CEO)
- Status: Permanent reference
- Do Not Edit Directly

### Markdown First Workflow

ALL future articles must follow this sequence:

**PHASE 1: NARRATIVE CREATION & APPROVAL**

1. **Narrative Markdown** — Christopher writes story in markdown (pure narrative)
2. **Editorial Review** — Christopher (Editor-in-Chief) reviews narrative
3. **Fact Checking** — Nathan verifies all information in story
4. **Quality Assurance** — Lucas confirms editorial consistency
5. **Final Approval** — Maki reviews and approves narrative
6. **Lock Narrative** — Create `Article_##_Locked.md` with approved story

**PHASE 2: PRESENTATION LAYER DEVELOPMENT**

7. **Create Presentation File** — Develop SEO, metadata, takeaways, tips, etc.
8. **Review Presentation** — Ensure presentation enhances without altering narrative
9. **HTML Generation** — Generate HTML from narrative + presentation layer
10. **Publication** — Deploy to production

**Critical Rules**:
- HTML files must NEVER become the source of truth
- Narrative is always the master (the locked markdown file)
- Presentation layer is separate and flexible
- Edits to narrative create new locked versions (v2, v3, etc.)
- Presentation layer can be updated independently

### Locked File Policy (Narrative Layer)

After narrative is approved:

1. Create a Locked version: `Article_##_Locked.md`
2. Add header: STATUS: LOCKED, Version 1.0, Approved by Maki
3. Contains: Pure narrative only (no presentation sections)
4. Preserve permanently in repository
5. NEVER overwrite a locked file
6. If narrative corrections needed, create new version: `Article_##_Locked_v2.md`
7. Each locked version becomes a permanent reference standard

### Presentation Layer Policy

Presentation files are separate and updateable:

1. Create: `Article_##_Presentation.md`
2. Contains: SEO, metadata, takeaways, tips, related articles, disclaimer, CTA
3. Can be updated independently (no impact on locked narrative)
4. Version updates not required for presentation changes
5. Always references the locked narrative file as source

### Workflow Enforcement

**Do Not**:
- Publish HTML without approved markdown source
- Edit markdown after publication without creating new locked version
- Use HTML as source for future article versions
- Skip any review stage in the pipeline

**Do**:
- Keep markdown as the primary working document
- Use locked files as reference standards
- Document all changes in Editorial Change Log
- Ensure consistency across all 83 articles using the Prototype as the template

---

## Production Timeline

**Article No.1**: LOCKED and PUBLISHED (2026-07-09)

**Articles 2–83**: Begin using this validated workflow

Each future article will:
- Follow the Editorial Handbook (v1.0)
- Use the Markdown First workflow
- Be locked after approval
- Reference Prototype Article No.1 as the quality standard

---


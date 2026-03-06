# Color Palette & Brand Style — AY Automate

**Single source of truth for all diagram colors.** Sourced from `02_Areas/Marketing/Brand/brand-brochure-v2.html`.

Accent: **Periwinkle `#8182C1`** — never purple, never cyan.

---

## Canvas Background

| Mode | Value |
|------|-------|
| Dark (default for LinkedIn/internal) | `#14141c` |
| Light (client-facing deliverables) | `#f0edee` |

Set via `appState.viewBackgroundColor` in the Excalidraw JSON.

---

## Shape Colors (Semantic)

Colors encode meaning. Each semantic purpose has a fill/stroke pair.

| Semantic Purpose | Fill | Stroke |
|------------------|------|--------|
| Primary / Process step | `#1e1e2e` | `#8182C1` |
| Secondary / Context | `#242436` | `#333348` |
| AI / Agent / LLM | `#1e1e2e` | `#A3A4D8` |
| Start / Trigger | `#1e1e2e` | `#4ade80` |
| End / Deliver / Success | `#1e1e2e` | `#4ade80` |
| Decision / Gate | `#242436` | `#A3A4D8` |
| Warning / Blocker | `#1e1e2e` | `#f87171` |
| Error / Failed | `#1e1e2e` | `#ef4444` |
| Inactive / Queued | `#14141c` | `#333348` (dashed stroke) |
| Human / Manual step | `#242436` | `#7a7580` |

**Light mode equivalents (client-facing):**

| Semantic Purpose | Fill | Stroke |
|------------------|------|--------|
| Primary / Process step | `#fffcfc` | `#8182C1` |
| Secondary / Context | `#f8f5f6` | `#c9cae8` |
| AI / Agent / LLM | `#fffcfc` | `#8182C1` |
| Start / Trigger | `#fffcfc` | `#16a34a` |
| End / Deliver / Success | `#fffcfc` | `#16a34a` |
| Decision / Gate | `#f8f5f6` | `#8182C1` |
| Warning / Blocker | `#fffcfc` | `#dc2626` |
| Error | `#fffcfc` | `#dc2626` |

**Rule**: Always pair a darker stroke with a lighter fill for contrast.

---

## Text Colors (Hierarchy)

Use color on free-floating text to create visual hierarchy without containers.

**Dark mode:**

| Level | Color | Use For |
|-------|-------|---------|
| Title | `#A3A4D8` | Section headings, major labels |
| Subtitle | `#8182C1` | Subheadings, secondary labels |
| Body/Detail | `#7a7580` | Descriptions, annotations, metadata |
| On dark fills | `#f0edee` | Text inside dark-colored shapes |
| Dim/timestamp | `#3d3d6b` | Faint context labels |

**Light mode:**

| Level | Color | Use For |
|-------|-------|---------|
| Title | `#14141c` | Section headings |
| Subtitle | `#8182C1` | Subheadings |
| Body/Detail | `#9c959f` | Descriptions, annotations |
| On light fills | `#14141c` | Text inside light shapes |

---

## Evidence Artifact Colors

Used for code snippets, JSON payloads, and technical evidence inside diagrams.

| Artifact | Background | Text Color |
|----------|-----------|------------|
| Code snippet | `#1e1e2e` | `#f0edee` |
| JSON / data example | `#1e1e2e` | `#A3A4D8` (periwinkle) |
| n8n workflow node | `#242436` | `#8182C1` |

---

## Arrows & Lines

| Element | Color |
|---------|-------|
| Arrows (dark) | `#8182C1` or match source shape stroke |
| Arrows (light) | `#8182C1` |
| Structural dividers / timeline lines | `#2a2a3e` (dark) / `#c9cae8` (light) |
| Marker dots (fill + stroke) | `#8182C1` |
| Traveling dots / animated paths | `#A3A4D8` |

---

## Fonts

Excalidraw `fontFamily` field:
- `1` = Virgil (handwritten) ← **default for all text**
- `2` = Helvetica (clean sans)
- `3` = Cascadia (monospace — use only for code snippets/JSON evidence)

**Use `fontFamily: 1` (Virgil) for all labels and annotations** — hand-drawn feel matches the sketchy roughness style.

---

## Output

Save diagrams to: `008_Builds/excalidraw/output/{slug}.excalidraw`
Render PNG to: `008_Builds/excalidraw/output/{slug}.png`

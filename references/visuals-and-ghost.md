# Ghost Native Representation & Structural Edit Rules

## 1. Ghost Native First

- Prefer standard Ghost Native blocks in this order: **Paragraphs → H2/H3 Headings → Lists → Code blocks → Images / Galleries → Bookmarks / Callouts → Tables (only when comparing multi-attribute values)**.
- For new content, avoid `Custom HTML` when native blocks suffice; do not remove existing HTML cards to satisfy this preference.
- Add H2/H3 headings only where they help the reader scan distinct sections.
- Keep safety warnings, data-loss risks, and conclusion-changing conditions expanded in normal prose or callouts—never hidden inside a collapsed Toggle.

## 2. Images, `alt`, and `caption`

- **Real evidence first:** Product photos and software UI screenshots must match the actual item and version discussed. Never present AI-generated visuals as real photos or measurement screens.
- **`alt` (Accessibility):** Objective, concise description of what is visually in the frame (e.g., `"메모리 슬롯 위치를 표시한 메인보드 구성도"`). No jokes or emoji.
- **`caption` (Editorial context):** Short, natural note explaining what to look at or adding a brief working comment, plus source attribution when needed. Do not repeat an entire body paragraph inside the caption.

## 3. Preserving Existing Ghost Posts During Structural Edits

When rewriting an existing Ghost post (`Rewrite` or `Light Edit`):

1. **Immutable Identity & Assets:** Post `id`, `uuid`, `slug`, `created_at`, `published_at`, `status`, author/tag order, feature image, and all existing Image, Gallery, Video, Embed, Bookmark, and Code cards must be 100% preserved unless the user explicitly approves an asset plan.
2. **Paragraph Splitting & Merging:** You may split overloaded paragraphs or merge choppy one-liners to improve reading rhythm.
3. **Relocating Inline Links to Bottom References (`참고자료`):**
   - You may rewrite awkward inline link anchor text and move supplementary official manual links from the middle of experience paragraphs into a clean `참고자료` section at the bottom of the post.
   - **Zero Silent Link Loss:** Every URL in the baseline post must remain accounted for (`before_count` vs. `after_count`). Any link relocation or count change must be listed in the before/after comparison table for explicit user approval before touching Ghost.

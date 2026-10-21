# Independent Review & Provenance Audit Checklist

Run this checklist as a separate, read-only verification pass after drafting or rewriting. Compare the draft with its source material even when no validation scripts are installed. Optional automated checks can flag number, name, and link changes; they never replace semantic review. Treat style-pattern findings as editorial hints, not automatic failure. Disclose who reviewed the result and whether that reviewer was independent of the writer.

## Part 1 — Five-Category Provenance Audit for Modified/Added Sentences

Inspect every sentence added or modified in the candidate draft and classify each claim/expression into one of five categories:

1. **`원본 근거 확인` (Confirmed Baseline / User Source):** Directly supported by the baseline text and confirmed user answers supplied for this task.
2. **`외부 자료 검증` (Verified External Source):** Supported by appropriate original/primary sources with applicable scope preserved. Technical or safety claims require a source suited to that exact claim.
3. **`설명·해석·판단` (Explanation / Interpretation / Judgment):** Supported reasoning or explanation, without claiming an unconfirmed personal belief or experience. An unsupported premise still needs correction.
4. **`작성자 확인 필요` (Needs Author Confirmation):** Plausible personal detail that is not in the confirmed evidence record—must be asked of the user before writing as first-person experience.
5. **`수정 또는 제거 필요` (Must Fix or Remove):** Unbacked first-person action/habit/feeling, generalized vendor-specific number, or lost safety condition. **Zero items in Category 5 may remain in a passing draft.**

## Part 2 — Critical Failure Gate (Non-Compensable)

1. **No Fabricated Experience or Habits:** Zero Category 5 items.
2. **Exact Facts & Scope:** Preserve numbers, units, proper nouns, quotations, causal uncertainty, and relevant dates or scope. For technical writing, also check model/version differences, including captured UI versus documentation.
3. **Required Conditions Intact:** Preserve safety, compatibility, privacy, and data-loss conditions when relevant to the subject. Do not add unrelated safety or technical checklists to personal writing.
4. **Content & Link Accountability:** Compare actual images, captions, cards, code, URLs, and required information with the source, not just counts. Record link moves or removals and their evidence destination. For an existing Ghost post, actual Lexical/card payload verification belongs to the separately authorized Ghost tool; a Markdown comparison alone cannot certify it. If that payload is unavailable, report this check as unverified.

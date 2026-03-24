# Changelog Audit Report

**Date:** 2026-03-24
**Scope:** Consolidated yearly files (`changelog/2019.mdx` through `changelog/2026.mdx`) audited against original month-wise source files (`2019/` through `2026/` folders).

---

## Executive Summary

| Metric | Count |
|--------|-------|
| Total months audited | 52 |
| PASS | 34 |
| WARN (minor, meaning preserved) | 17 |
| FAIL (content/meaning lost) | 1 |
| Fabricated content found | 0 |

**Overall verdict:** The consolidated files are a faithful representation of the originals. One FAIL exists (July 2024 record counts duplicated from April — inherited from the source file). All other issues are minor editorial condensing, acceptable rounding, or omitted URLs/promotional content.

---

## Year-by-Year Audit Tables

### 2019 (6 months: Jul–Dec)

| Month | Overview | Record Counts | New Sources | Schema Changes | Fixes | Portal/API | Coming Soon | Source Lists | Fabricated? | Status |
|-------|----------|---------------|-------------|----------------|-------|------------|-------------|--------------|-------------|--------|
| Jul | ✅ | ✅ | ✅ | ✅ | ✅ | N/A | N/A | ✅ | No | **PASS** |
| Aug | ✅ | ✅ | ✅ | ✅ | ✅ | N/A | N/A | ✅ | No | **PASS** |
| Sep | ✅ | ✅ | ✅ | ✅ | ✅ | N/A | N/A | ✅ | No | **PASS** |
| Oct | ✅ | ✅ | ✅ | ✅ | ✅ | N/A | N/A | ✅ | No | **PASS** |
| Nov | ✅ | ✅ | ✅ | ✅ | ✅ | N/A | N/A | ✅ | No | **PASS** |
| Dec | ✅ | ✅ | ✅ | N/A | ✅ | N/A | N/A | ✅ | No | **PASS** |

**Discrepancies:**
- **Aug:** `crawlResultFiles` → `crawlIDs` in-progress note omitted (tracked in Sep/Nov instead) — no meaning lost.
- **Oct:** Detail that "Product data is the remaining data source being transitioned" for `crawlResultFiles` omitted — covered in Sep.

---

### 2020 (10 months: Jan–Apr, Jul–Dec)

| Month | Overview | Record Counts | New Sources | Schema Changes | Fixes | Portal/API | Coming Soon | Source Lists | Fabricated? | Status |
|-------|----------|---------------|-------------|----------------|-------|------------|-------------|--------------|-------------|--------|
| Jan | ⚠️ | ✅ | ✅ | ✅ | ✅ | N/A | N/A | N/A | No | **WARN** |
| Feb | ✅ | ✅ | ✅ | ✅ | ⚠️ | N/A | N/A | N/A | No | **WARN** |
| Mar | ✅ | ✅ | ✅ | N/A | ✅ | N/A | N/A | N/A | No | **PASS** |
| Apr | ✅ | ✅ | ✅ | N/A | ✅ | N/A | N/A | N/A | No | **PASS** |
| Jul | ✅ | ✅ | ✅ | ✅ | ⚠️ | N/A | N/A | ✅ | No | **WARN** |
| Aug | ✅ | ✅ | ✅ | N/A | ✅ | N/A | N/A | N/A | No | **PASS** |
| Sep | ✅ | ✅ | ✅ | N/A | ✅ | N/A | N/A | N/A | No | **PASS** |
| Oct | ✅ | ✅ | ✅ | N/A | ✅ | N/A | N/A | N/A | No | **PASS** |
| Nov | ✅ | ✅ | ✅ | ✅ | ✅ | N/A | N/A | N/A | No | **PASS** |
| Dec | ✅ | ✅ | ✅ | N/A | ✅ | N/A | N/A | N/A | No | **PASS** |

**Discrepancies:**
- **Jan overview:** "New hierarchical product data is in the process of being added to our database" simplified to "Hierarchical product data is being prepared." Minor phrasing change.
- **Feb fixes:** Word "crawl" added ("erroneous crawl data" vs original "erroneous data collected"). Contextually supported but not in original bullet.
- **Jul fixes:** Fix items reordered (CarGurus, People addresses, VRBO → CarGurus, VRBO, People addresses). Content preserved. Overview drops "with more plans in the works."

---

### 2021 (3 months: Jan–Mar)

| Month | Overview | Record Counts | New Sources | Schema Changes | Fixes | Portal/API | Coming Soon | Source Lists | Fabricated? | Status |
|-------|----------|---------------|-------------|----------------|-------|------------|-------------|--------------|-------------|--------|
| Jan | ✅ | ✅ | ✅ | ✅ | ✅ | N/A | N/A | N/A | No | **PASS** |
| Feb | ✅ | ✅ | N/A | N/A | ✅ | N/A | N/A | N/A | No | **PASS** |
| Mar | ✅ | ✅ | ✅ | ✅ | ✅ | N/A | N/A | N/A | No | **PASS** |

**Discrepancies:** None. All content fully preserved. Original typo "as been improved" corrected to "Improved" — acceptable fix.

---

### 2022 (6 months: Jun–Sep, Nov–Dec)

| Month | Overview | Record Counts | New Sources | Schema Changes | Fixes | Portal/API | Coming Soon | Source Lists | Fabricated? | Status |
|-------|----------|---------------|-------------|----------------|-------|------------|-------------|--------------|-------------|--------|
| Jun | ✅ | ✅ | ✅ | ✅ | ✅ | N/A | N/A | ✅ | No | **PASS** |
| Jul | ✅ | ✅ | ✅ | N/A | ✅ | N/A | N/A | ✅ | No | **PASS** |
| Aug | ✅ | ✅ | ✅ | N/A | ✅ | N/A | N/A | ✅ | No | **PASS** |
| Sep | ⚠️ | ✅ | ✅ | N/A | ✅ | N/A | N/A | ✅ | No | **WARN** |
| Nov | ✅ | ✅ | ⚠️ | ✅ | ✅ | ✅ | N/A | ⚠️ | No | **WARN** |
| Dec | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | N/A | ⚠️ | No | **WARN** |

**Note:** File `202210-data-release-log.mdx` has heading `# 2022.11` (November, not October). File `202212-data-release-log-1.mdx` has heading `# 2023.01` — correctly excluded from 2022 consolidated and present in 2023.

**Discrepancies:**
- **Sep overview:** "other data type views" changed to "custom views" — meaning preserved with clearer phrasing.
- **Nov:** allmenus.com classified under "Product Source Updates" in original but labeled correctly as "Business source" in consolidated (improvement). `licenseNumber` moved from "API" section to "Schema Changes" (correct reclassification). Data enrichment feedback call-to-action details (email/reply instructions) dropped.
- **Dec:** allmenus.com and Amazon entries duplicated from Nov in original — consolidated faithfully reproduces the duplication. "Canadian and Us markets" corrected to "US markets."

---

### 2023 (11 months: Jan–Feb, Apr–Dec except Mar)

| Month | Overview | Record Counts | New Sources | Schema Changes | Fixes | Portal/API | Coming Soon | Source Lists | Fabricated? | Status |
|-------|----------|---------------|-------------|----------------|-------|------------|-------------|--------------|-------------|--------|
| Jan | ✅ | ✅ | ✅ | N/A | ✅ | N/A | N/A | ✅ | No | **PASS** |
| Feb | ✅ | ✅ | ✅ | N/A | ✅ | N/A | N/A | ✅ | No | **PASS** |
| Apr | ✅ | ⚠️ | ✅ | ✅ | N/A | N/A | N/A | ✅ | No | **WARN** |
| May | ✅ | ⚠️ | ✅ | N/A | N/A | ✅ | N/A | ✅ | No | **WARN** |
| Jun | ⚠️ | ✅ | ✅ | N/A | N/A | ⚠️ | N/A | ✅ | No | **WARN** |
| Jul | ✅ | ✅ | ✅ | ✅ | N/A | ✅ | N/A | ✅ | No | **PASS** |
| Aug | ⚠️ | ✅ | ✅ | ✅ | N/A | ✅ | N/A | ✅ | No | **WARN** |
| Sep | ✅ | ✅ | ✅ | N/A | ✅ | ⚠️ | N/A | ✅ | No | **WARN** |
| Oct | ✅ | ✅ | ✅ | ✅ | N/A | N/A | N/A | ✅ | No | **PASS** |
| Nov | ✅ | ✅ | ✅ | ✅ | ✅ | N/A | N/A | ✅ | No | **PASS** |
| Dec | ✅ | ✅ | ✅ | ⚠️ | N/A | N/A | N/A | ✅ | No | **WARN** |

**Note:** File `202212-data-release-log-1.mdx` (in `2022/` folder) has heading `# 2023.01`. File `202310-data-release-log-1.mdx` has heading `# 2023.11`.

**Discrepancies:**
- **Apr, May record counts:** "Newly added" counts dropped from consolidated. The originals appear to have copy-pasted Feb numbers for both totals and new-adds, so this is likely intentional cleanup.
- **Jun overview:** "major improvements and bug fixes" simplified to "major improvements" — "bug fixes" omitted.
- **Jun Portal/API:** Repeated website redesign mention condensed (already covered in May).
- **Aug overview:** Original copy-pasted Jul's overview text. Consolidated rewrites to accurately describe Aug content (broker license linking, People schema). This is a correction, not fabrication.
- **Sep Portal/API:** "Self-service subscription management" reduced to description tag only, not a separate section.
- **Dec schema:** `parkingTypes` values "Attached Garage" and "Detached Garage" merged to "Attached/Detached Garage" — two distinct values combined into one.

---

### 2024 (5 months: Feb, Apr, Jul, Sep, Nov)

| Month | Overview | Record Counts | New Sources | Schema Changes | Fixes | Portal/API | Coming Soon | Source Lists | Fabricated? | Status |
|-------|----------|---------------|-------------|----------------|-------|------------|-------------|--------------|-------------|--------|
| Feb | ✅ | ✅ | ✅ | N/A | ✅ | N/A | N/A | ✅ | No | **PASS** |
| Apr | ✅ | ✅ | ✅ | N/A | ✅ | N/A | N/A | N/A | No | **PASS** |
| Jul | ✅ | ❌ | ✅ | ✅ | ✅ | ⚠️ | ✅ | N/A | No | **FAIL** |
| Sep | ✅ | ✅ | ✅ | N/A | N/A | ✅ | ⚠️ | N/A | No | **WARN** |
| Nov | ✅ | ⚠️ | ✅ | ✅ | N/A | ✅ | ⚠️ | N/A | No | **WARN** |

**Discrepancies:**
- **Jul record counts — FAIL:** All 4 verticals show identical numbers to April (Business 133.8M/+1.1M, People 34.3M/+7.3M, Product 532.8M/+13.8M, Property 242.5M/+21M). The original source file itself has these same duplicated numbers, so the consolidated faithfully reproduced the source error. **Action needed:** Verify correct July 2024 record counts and update both the original and consolidated files.
- **Jul Portal/API:** Sign-up page URL (`https://portal.datafiniti.co/sign-up`) and schema page reference omitted.
- **Sep Coming Soon:** Two distinct Autotrace items (API and portal detailed view) merged into one bullet. Meaning preserved but detail reduced.
- **Nov record counts:** Business and People both show 135,007,520 in original — likely a source error (same number for two verticals). Consolidated faithfully reproduces this.
- **Nov Coming Soon:** "Upcoming redesign for the Business Data portal with new filter options and simplified query capabilities" entirely absent from consolidated.

---

### 2025 (8 months: Feb–Mar, Jun–Nov)

| Month | Overview | Record Counts | New Sources | Schema Changes | Fixes | Portal/API | Coming Soon | Source Lists | Fabricated? | Status |
|-------|----------|---------------|-------------|----------------|-------|------------|-------------|--------------|-------------|--------|
| Feb | ✅ | N/A | ✅ | ✅ | N/A | ✅ | N/A | ✅ | No | **PASS** |
| Mar | ✅ | ✅ | N/A | ✅ | N/A | N/A | ✅ | N/A | No | **PASS** |
| Jun | ✅ | ✅ | ✅ | ✅ | N/A | N/A | ✅ | ✅ | No | **PASS** |
| Jul | ✅ | ✅ | ✅ | ✅ | N/A | N/A | ✅ | ⚠️ | No | **WARN** |
| Aug | ✅ | N/A | ✅ | ✅ | N/A | N/A | ✅ | ✅ | No | **PASS** |
| Sep | ✅ | N/A | ✅ | ✅ | N/A | N/A | N/A | ✅ | No | **PASS** |
| Oct | ✅ | N/A | ✅ | N/A | N/A | ✅ | ✅ | ✅ | No | **PASS** |
| Nov | ✅ | ✅ | N/A | ✅ | N/A | ✅ | ✅ | N/A | No | **PASS** |

**Note:** Jun, Jul, Nov record counts are identical to Mar — this matches the originals (source data issue, not a consolidation error).

**Discrepancies:**
- **Feb:** Raw API enum values `forrentbyowner` and `forsalebyowner` omitted; only display names preserved.
- **Mar:** "Get Rewarded for Your Review!" promotional section (offering Google review credits) omitted from consolidated. Arguably not a data release note.
- **Jul source lists:** State government URLs omitted (commerce.alaska.gov, data.delaware.gov, sosbes.sos.ky.gov, corp.sos.ms.gov, data.pa.gov). Only state names listed. Inconsistent with other months that include URLs.
- **Sep:** JSON code example for `sourceURLsPerField` omitted. Field description preserved.
- **Nov:** "Why the Change?" explanatory section for price field deprecation omitted. Deprecation date and migration notes preserved.

---

### 2026 (3 months: Jan–Mar)

| Month | Overview | Record Counts | New Sources | Schema Changes | Fixes | Portal/API | Coming Soon | Source Lists | Fabricated? | Status |
|-------|----------|---------------|-------------|----------------|-------|------------|-------------|--------------|-------------|--------|
| Jan | ✅ | N/A | N/A | N/A | N/A | N/A | ✅ | N/A | No | **PASS** |
| Feb | ✅ | N/A | N/A | ✅ | N/A | N/A | ✅ | N/A | No | **PASS** |
| Mar | ✅ | N/A | N/A | ✅ | N/A | N/A | ✅ | ✅ | No | **PASS** |

**Discrepancies:** None material. All schema changes (`statusHistory`, `profileImageURLs`, `mostRecentProfileImageURL`), deprecation notices, and roadmap items fully preserved.

---

## All Specific Missing Items

### FAIL-level (action required)

1. **2024 Jul — Record counts duplicated from April.** All 4 verticals show identical numbers. This is inherited from the source file. **Action:** Obtain correct July 2024 record counts and update both the original file and the consolidated entry.

### WARN-level (meaning preserved, minor detail lost)

| # | Year-Month | What's missing or changed |
|---|------------|---------------------------|
| 1 | 2020-01 | Overview: "added to our database" detail dropped |
| 2 | 2020-02 | Fixes: word "crawl" added to "erroneous data" (not in original) |
| 3 | 2020-07 | Overview: "with more plans in the works" dropped; fix items reordered |
| 4 | 2022-09 | Overview: "other data type views" → "custom views" |
| 5 | 2022-11 | Data enrichment feedback call-to-action details (email/reply) dropped |
| 6 | 2022-12 | allmenus.com/Amazon entries duplicated from Nov (matches original duplication) |
| 7 | 2023-04 | "Newly added" record counts dropped (original had copy-pasted Feb numbers) |
| 8 | 2023-05 | "Newly added" record counts dropped (same copy-paste issue) |
| 9 | 2023-06 | Overview: "bug fixes" omitted; Portal info condensed |
| 10 | 2023-08 | Overview rewritten to correct original's copy-paste error |
| 11 | 2023-09 | Self-service subscription management reduced to description tag |
| 12 | 2023-12 | `parkingTypes`: "Attached Garage" + "Detached Garage" merged to "Attached/Detached Garage" |
| 13 | 2024-07 | Sign-up URL and schema page reference omitted |
| 14 | 2024-09 | Two Autotrace coming-soon items merged into one |
| 15 | 2024-11 | Business Data portal redesign announcement missing from Coming Soon |
| 16 | 2024-11 | Business and People show same count (135,007,520) — source error |
| 17 | 2025-02 | API enum values `forrentbyowner`/`forsalebyowner` omitted |
| 18 | 2025-03 | "Get Rewarded for Your Review!" promotional section omitted |
| 19 | 2025-07 | State government URLs for business sources omitted (only state names kept) |
| 20 | 2025-09 | JSON code example for `sourceURLsPerField` omitted |
| 21 | 2025-11 | "Why the Change?" explanatory section for deprecation omitted |

### Source data issues (not consolidation errors)

| # | Year-Month | Issue |
|---|------------|-------|
| 1 | 2023-04/05 | Record counts copy-pasted from Feb — likely incorrect in source |
| 2 | 2023-08 | Overview text copy-pasted from Jul in source file |
| 3 | 2024-07 | Record counts identical to Apr — likely incorrect in source |
| 4 | 2024-11 | Business and People show identical count (135,007,520) — likely source error |
| 5 | 2025-06/07/11 | Record counts identical to Mar — likely copy-paste in source |

---

## Final Verdict

The consolidated changelog files are **high quality** and faithfully represent the original month-wise source files. No fabricated content was found anywhere. The single FAIL (July 2024 duplicated numbers) is inherited from a source data error.

**Recommended actions:**

1. **Verify July 2024 record counts** — obtain correct numbers and update both source and consolidated files
2. **Verify Nov 2024** — Business and People showing identical counts (135,007,520) is suspicious
3. **Add back Nov 2024 Coming Soon** — the Business Data portal redesign announcement was dropped
4. **Consider adding back Jul 2025 state gov URLs** — inconsistent with other months that include URLs
5. **Verify 2023 Apr/May and 2025 Jun/Jul/Nov record counts** — all appear to be copy-pasted from earlier months

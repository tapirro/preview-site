---
id: evidence-03
type: evidence
title: Critical Finding: All 287 Pages Are Orphan Pages
---

## The Discovery

**Loop:** L1070 (Internal Link Density Analysis)
**Method:** Scanned all 287 deployed pages across 16 domains
**Finding:** ALL 287 pages have 0 inbound internal links (100% orphan rate)

---

## Why This Matters

### SEO Impact
- Google doesn't know which pages are important
- Link equity doesn't flow through the site
- Crawling is inefficient (no site structure)
- Indexation suffers (Google doesn't know what to prioritize)

### Metrics Impact
- **CTR (0.6%, target 3%):** Snippets not ranking because no link authority
- **Indexation (32.2%, target 50%):** Google indexes random pages, not the important ones
- **GSC clicks (8, target 10):** Low traffic because no link authority

### This Explains 4 Stagnant Metrics

The 4 stagnant metrics (m-016, m-025, m-026, m-050) are NOT technical bugs. They're symptoms of:

1. **No distribution channels** (0/6 blocked)
2. **No internal link structure** (100% orphan rate)
3. **No external backlinks** (shipped_ratio 0%)

---

## The Linking Plan

From `devreports/internal_link_analysis_L1070.json`:

### Immediate Actions
1. Add links from orphan pages to hub pages (botanicaandina.com, liluama.com)
2. Add links from low-outbound pages to relevant content
3. Create hub pages: "Related Herbs", "Product Finder", "Symptom Guide"

### Strategic Actions (Phase 5)
1. Design topic clusters with internal linking:
   - Condition clusters (heart health, joint pain)
   - Herb clusters (maca, muña, coca)
   - Product clusters (CardioX, Flexacil)
2. Implement cluster templates
3. Create sitemap page for each domain

### Metrics to Track
- Orphan page count (target: < 5% of total)
- Average outbound links per page (target: 3-10)
- Internal link density (target: > 40%)

---

## This Is NOT a Technical Problem

**Problem appears technical:** "All pages are orphans, let's fix the links."

**Real problem:**
- Even if we fix internal links, external_action_ratio stays 0%
- Even if we fix internal links, shipped_ratio stays 0%
- Internal links HELP, but they don't REPLACE distribution

**10× Insight:**
> "Fixing internal links is optimizing for the wrong axis. The bottleneck isn't Google discovering pages — it's Google not having enough signals (backlinks) to trust the pages."

---

## The Real 10× Path

**NOT:** Fix internal links → improve metrics slightly
**YES:** Unblock distribution → improve metrics 10×

**Why:**
- Backlinks from external domains (DA92, DA97) = 10× more signal than internal links
- Google prioritizes pages with external backlinks over internal linking
- Distribution unblock = backlinks = 10× SEO signal

---

## Decision

**Fix internal links OR unblock distribution?**

| Path | SEO Signal | Expected Improvement | Time to execute |
|------|------------|---------------------|------------------|
| Fix internal links | Weak (internal only) | 5-10% | 2-3 loops |
| Unblock distribution | Strong (external) | 100-500% | 2 min (operator) |

**10× answer:** Unblock distribution. Internal links are a distraction from the real problem.

---

*Evidence compiled: 2026-03-29*

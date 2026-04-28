# Ganjier Guild — YOOtheme Pro Implementation Checklist

> Last updated: April 28, 2026  
> Work through this checklist in order. Complete each section before moving to the next.

---

## Before building

### Theme settings
- [ ] Covik Sans assigned to primary/heading
- [ ] Abadi assigned to body copy
- [ ] Honey set as default CTA/button color
- [ ] Mint set as secondary accent
- [ ] Mocha set as primary dark/background anchor
- [ ] Warning Yellow and Warning Red reserved for alerts only — not decorative

### Save reusable sections to YOOtheme Library first
- [ ] `GG - Hero - Standard`
- [ ] `GG - Section - Intro Text`
- [ ] `GG - Grid - 3 Value Cards`
- [ ] `GG - Grid - Membership Options`
- [ ] `GG - FAQ - Membership`
- [ ] `GG - CTA Strip`
- [ ] `GG - Portal - Dashboard Main`
- [ ] `GG - Library - Intro`

---

## Global header

- [ ] Join the Guild visible in main nav or header CTA zone
- [ ] Member Login visible as utility CTA (upper right)
- [ ] Join the Guild = Honey filled button
- [ ] Member Login = Mocha outline or Mocha fill + white text
- [ ] Logged-in state switches utility CTA to Member Portal
- [ ] Brandmark A horizontal used in header
- [ ] Button padding, radius, and uppercase style match theme settings

---

## Homepage

### Section 1 — Hero
- [ ] Section → Row → 1 Column
- [ ] Headline (eyebrow): Ganjier Guild
- [ ] Headline (H1): A member-supported home for cannabis craft, education, and professional community.
- [ ] Text: hero subheadline
- [ ] Button: Join the Guild (Honey filled) + Explore Member Benefits (secondary)
- [ ] Left aligned, width large, generous padding
- [ ] Saved to library as `GG - Hero - Standard`

### Section 2 — More than access
- [ ] Section → Row → 1 Column
- [ ] Headline: More than access. A shared investment in the Guild.
- [ ] Text: supporting body copy
- [ ] Muted/light warm background
- [ ] Saved as `GG - Section - Intro Text`

### Section 3 — Why members join
- [ ] Section → Row → 1 Column
- [ ] Headline: Why members join
- [ ] Grid element with 3 items: Education / Connection / Opportunity
- [ ] Each item has short title + 1–2 sentence description
- [ ] Saved as `GG - Grid - 3 Value Cards`

### Section 4 — Who the Guild is for
- [ ] Section → Row → 2 Columns
- [ ] Left: Headline + intro text
- [ ] Right: Text with bullet list

### Section 5 — CTA strip
- [ ] Reuse `GG - CTA Strip`
- [ ] Headline + Text + Join the Guild button

---

## Join page

### Section 1 — Join hero
- [ ] Section → Row → 1 Column
- [ ] Headline: Join the Guild
- [ ] Text: intro body

### Section 2 — How membership and dues work
- [ ] Section → Row → 2 Columns
- [ ] Left: Headline + short intro
- [ ] Right: Text with membership vs dues explanation
- [ ] Closing reassurance text below or in same column

### Section 3 — Membership options
- [ ] Section → Row → 1 Column
- [ ] Headline
- [ ] Grid with 2 items: Community Education / Certified Ganjier
- [ ] Each item: title, description, button/link
- [ ] Saved as `GG - Grid - Membership Options`

### Section 4 — What your dues support
- [ ] Section → Row → 1 Column
- [ ] Headline
- [ ] Grid with 4 items: Education / Community / Stewardship / Infrastructure

### Section 5 — FAQ
- [ ] Section → Row → 1 Column
- [ ] Headline
- [ ] Accordion with items:
  - [ ] Membership vs dues
  - [ ] Payment frequency
  - [ ] What dues support
  - [ ] Changing tiers
  - [ ] Friend of the Guild access
- [ ] Saved as `GG - FAQ - Membership`

### Section 6 — Final CTA
- [ ] Reuse `GG - CTA Strip`

---

## Certified Ganjier page

- [ ] Section 1: Headline + Text + Button (hero)
- [ ] Section 2: Eligibility Text block
- [ ] Section 3: Benefits Grid (3–4 items)
- [ ] Section 4: Dues support Text near CTA

---

## Community Education page

- [ ] Mirror Certified Ganjier page structure exactly
- [ ] Section 1: Hero
- [ ] Section 2: Purpose / who it's for
- [ ] Section 3: Benefits Grid
- [ ] Section 4: Dues support Text
- [ ] Section 5: CTA (reuse `GG - CTA Strip`)

---

## Friend of the Guild / Newsletter

- [ ] Keep existing newsletter module/modal trigger
- [ ] Update copy with approved Friend of the Guild blurb
- [ ] Confirm it clearly states this is not a membership tier (if needed publicly)

---

## Member Portal dashboard

### Layout
- [ ] Section → Row → 1/4 + 3/4 split
- [ ] Left = sidebar navigation
- [ ] Right = dashboard content

### Left column (sidebar)
- [ ] Headline: Browse
- [ ] Nav (Browse links)
- [ ] Headline: My Account
- [ ] Nav (Member Portal / Orders / Profile / Downloads / Logout)
- [ ] Optional newsletter block
- [ ] Divider

### Right column (dashboard)
- [ ] Block 1: Headline (Member Portal) + welcome Text + membership status/renewal line
- [ ] Block 2: Quick links Grid (4–6 cards: Membership Details / Directory / Replay Library / Resource Library / Events / Account & Dues)
- [ ] Block 3: What's New (latest replay / resource / event)
- [ ] Block 4: Profile nudge prompts (complete profile / update payment / explore resources)
- [ ] Saved as `GG - Portal - Dashboard Main`

---

## Resource Library

- [ ] Keep existing query/grid listing
- [ ] Add Section → Row → 1 Column above listing with:
  - [ ] Headline
  - [ ] Intro Text (keyword-relevant, indexable)
- [ ] Add category description text above filters where possible
- [ ] Confirm each resource has descriptive title and excerpt
- [ ] Saved as `GG - Library - Intro`

---

## Replay Library

- [ ] Mirror Resource Library structure
- [ ] Headline + short intro text above listing
- [ ] Keep intro copy concise so grid remains primary

---

## FAQ page

- [ ] Section → Row → 1 Column
- [ ] Headline: Frequently Asked Questions
- [ ] Short intro Text
- [ ] Accordion (grouped by topic):
  - [ ] Joining
  - [ ] Membership vs dues
  - [ ] Member Portal access
  - [ ] Billing
  - [ ] Events and resources
  - [ ] Friend of the Guild
- [ ] Optional: CTA strip linking to Contact page

---

## Contact page

- [ ] Section → Row → 1/2 + 1/2 split
- [ ] Left: Headline + intro Text + contact note
- [ ] Right: Module Position (Forminator or ACF form embed)
- [ ] Confirm form labels are clear
- [ ] Keep intro copy concise

---

## Footer

- [ ] Keep brand symbol/logo in left column
- [ ] Keep independence disclaimer text
- [ ] Keep Terms & Conditions and Privacy Policy links
- [ ] Tighten spacing for consistency
- [ ] Optional: small CTA (Join the Guild or Subscribe)

---

## Button styling — final check

| Button | Style |
|---|---|
| Join the Guild | Honey fill, white text |
| Member Login | Mocha border + Mocha text OR Mocha fill + white text |
| Member Portal | Mocha fill + white text |
| Secondary/portal actions | Mint or neutral outline |

- [ ] All button text uses approved labels (no "Purchase Membership" or "Membership Fee")
- [ ] All buttons meet minimum 44x44px touch target
- [ ] Hover states confirmed for each button style

---

## Build workflow sequence

1. [ ] Confirm global styles/fonts/buttons in Theme Settings
2. [ ] Build and save all reusable sections to Library
3. [ ] Build Homepage
4. [ ] Build Join page
5. [ ] Build Certified Ganjier page
6. [ ] Build Community Education page
7. [ ] Refine Member Portal dashboard and nav
8. [ ] Update Resource Library and Replay Library intros
9. [ ] Build/update FAQ page
10. [ ] Build/update Contact page
11. [ ] Review footer and header CTA consistency
12. [ ] Test desktop (1280px+) and mobile (375px)

---

## Final QA checklist

- [ ] One H1 per page
- [ ] Join the Guild and Member Login easy to find in header
- [ ] Portal dashboard shows top member tasks above fold
- [ ] Join page explains value before dues
- [ ] FAQ is scannable and not buried
- [ ] Resource Library has intro copy for SEO
- [ ] Warning Yellow/Red not used decoratively
- [ ] Header, buttons, and footer visually consistent
- [ ] "Membership fee" replaced with "dues" sitewide
- [ ] "Purchase membership" replaced with "Join the Guild" or "Activate Membership" sitewide
- [ ] All pages tested desktop + mobile
- [ ] Dark mode / contrast checked if applicable

Project: Anton Tolkunov Portfolio

Summary:
- Static portfolio website for Senior Product Designer role search.
- Main page: hero, selected work, about, mentorship, and contact sections.
- Added case-study page: `real-de-checkout.html` linked from the Real.de card.
- Design style: dark minimal editorial, responsive, with light/dark theme toggle.

Recent update:
- Favicon from the Figma export (16px black mark). Nearest-neighbor upscale to favicon.png (32) and apple-touch-icon.png (192). Linked on all live case pages.
- Added a dedicated Mentorship section with social proof (100+ sessions),
  mentoring focus, and CTA link to ADPList booking.
- Updated homepage copy and structure:
  - New navigation: Work, About, Resume, LinkedIn
  - New hero headline and positioning statement
  - New introduction text for target role narrative
  - Added company logo cloud as text badges (Vodafone, real.de, trivago, Panasonic, obey clothing, okko.tv, docsvision)
- Replaced logo badges with real SVG logos where reliable sources exist:
  Vodafone, real.de, trivago, Panasonic, Obey, okko.tv, Docsvision.
- Adjusted logo cloud presentation:
  - Logos are 2x larger
  - Logos are rendered in a single muted gray tone for both dark and light themes
  - Removed frames/background capsules around logos
- Updated case links on homepage:
  - Real.de card now links to `real-checkout.html`
  - Trivago card now links to `trivago-talent-community.html`
- Updated contact email to `antontolkunov@me.com` across pages.
- Added `Mentorship` link to desktop and mobile navigation.
- Logo wall tuning:
  - Panasonic logo scaled to 3x
  - Docsvision logo scaled to 2x
  - `space-3` set to `4rem` locally within logo wall
- Logo wall redesigned as a single-line marquee:
  - Continuous horizontal scrolling animation across full viewport width
  - Kept horizontal spacing consistent with logo-wall tuning
  - Mobile version uses 2x smaller logos
  - Added `prefers-reduced-motion` fallback (animation disabled for motion-sensitive users)
- Replaced Vodafone and trivago icons with full-text SVG logo variants where applicable.
- Logo wall assets:
  - Vodafone: repo file `VF_Logo_RGB_BLACK.svg`
- Added subheader above logo wall: "Companies that trust me".
- Styled logo-wall subheader using the same `section-label` pattern as "Selected Work" (left-aligned).
- Added new case page `vodafone-secure-net.html`:
  - Full narrative for Vodafone Secure Net redesign
  - Role, timeline, reach, and results
  - PNG screen exports from Figma file `portfolio` (Cleaning Tool section) in `assets/vodafone-cleaning-tool/`:
    dashboard context, onboarding step, cleaning progress, scan results, success state, mid-scan reference frame
  - Final metrics summary cards (drop-off and NPS)
- Replaced Vodafone Cleaning Tool card on homepage with a live link to the new case.
- Contact form posts via FormSubmit (`formsubmit.co`) to `antontolkunov@me.com` with redirect back to the site after send. First submission may require confirming the inbox once on FormSubmit’s side.
- Restructured `vodafone-secure-net.html` narrative:
  - Section order: Problem, What We Found, UX Research (new), Design Decisions, Before/After, Design Exploration, Testing, Complete Flow, Results, What I Learned
  - Added UX Research section with placeholders for journey maps, session notes, affinity diagrams
  - Added placeholders in Design Exploration for early sketches and visual research moodboard
  - Restored onboarding screen in What We Found and scan-progress in Testing
- Real.de checkout case (`real-checkout.html`) — honest experiment framing:
  - New Experiment section: grocery web / DE / checkout starters segment, primary + guardrail metrics
  - Result copy without invented A/B percentages; "meaningful improvement" language
  - Homepage card metric: "Checkout completion ↑ · A/B validated"
  - Impact detail: "Checkout completion ↑ · validated in A/B"
- Added case page `visual-qa.html` (Design Visual QA process):
  - Sync vs async experiments, converge animation (design/eng/QA → hybrid)
  - Animated 4-step pipeline; cover board with staggered chips
  - Homepage: replaced WIP Overview Summary card with link to Visual QA
  - Narrative: PO-gated live QA, QA ticket habit as first filter, AI-assisted residual tickets
- 2026-10-13 — aligned site with CV (single source of truth):
  - Titles: official job titles everywhere; "Lead" only as project scope
    (Secure Net: Senior Product Designer · design lead; Real.de: Senior UX Designer · sole UX designer;
    Trivago: Digital Product Designer · design lead on the project)
  - Hero/About: "Senior Product Designer"; intro and bio rewritten in plainer voice
  - Secure Net: reach ~0.5 million users; "NPS" renamed to average recommendation score (5.0 → 6.5 out of 10);
    backend part credited to the vendor; added "close the app without losing progress" and optional Coach link
  - Skills: "B2B / SaaS" -> "B2B Tools", "Team Leadership" -> "Mentoring"
  - `assets/Anton_Tolkunov_CV.pdf` replaced with the October 2026 CV (Vodafone 2020–September 2026, drop-off 60% → 40%)
  - TODO: add Secure Net screens showing the "you can close the app" message
- 2026-10-13 — Secure Net "Three coordinated decisions": the single result card is now centered on screens ≤768px
  (mobile rule `left: 5%` no longer overrides the card's centering)
- 2026-10-14 — Secure Net: "Anton Tolkunov" logo and nav links use the same header styles as all other pages
  (size, letter-spacing, weight, hover)
- 2026-10-14 — Secure Net: header now follows the light theme (added the `[data-theme="light"] .site-header` rule the other case pages already had)

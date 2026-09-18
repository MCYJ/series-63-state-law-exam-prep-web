# Series 63 State Law Exam Prep web context

## Scope

- Service: `GLB-0004`
- Package / bundle: `app.mcyj.examprep.glb0004`
- Repository: `MCYJ/series-63-state-law-exam-prep-web`
- Production: `https://mcyj.github.io/series-63-state-law-exam-prep-web/`
- Source app files remain read-only.

## Verified Store state — 2026-09-19

- Google Play is public for the exact package: `https://play.google.com/store/apps/details?id=app.mcyj.examprep.glb0004`.
- Exact-bundle Apple lookup returned no public record; historical ASC ID `6795571263` is not treated as a public Store URL.
- Google Play uses the official badge inside a `194 × 75` frame; App Store is a localized disabled `194 × 75` control.

## Official facts

- NASAA content outline and study guide plus FINRA exam/registration pages were checked on 2026-09-19.
- Current structure: 65 multiple-choice questions, 60 scored plus five unidentified pretest, 75 minutes, closed book, pass at 43/60.
- Official domain weights are preserved: 12, 13, 25, 20, 9, 5, 5 and 11 percent.
- Retake waits are described as 30 days after first failure, 30 after second, and 180 after third and later failures.
- Passing alone is not represented as state registration or authority to transact securities business.
- Twelve independently written English guides; no official exam questions are copied.

## Design and privacy

- Legal case-file visual thesis: powder-blue ruled paper, navy docket panels, red section markers, serif legal headings and a four-part decision grid.
- Global `word-break: keep-all` plus safe overflow handling.
- Static site with no analytics, advertising cookies, account system or contact form.

## Verification

- `npm run build`
- `npm run check`
- Production QA must cover every sitemap route, assets, custom 404, exact Play identity, absent Apple link and badge-frame CSS.

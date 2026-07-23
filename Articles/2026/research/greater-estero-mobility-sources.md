# Greater Estero Mobility Article — Research and Publication Notes

**Article:** Greater Estero Is Growing—and Mobility Is Part of the Housing Conversation  
**Research date:** July 23, 2026  
**Canonical slug:** `greater-estero-is-growing-and-mobility-is-part-of-the-housing-conversation`

## Repository files

- `Articles/2026/greater-estero-is-growing-and-mobility-is-part-of-the-housing-conversation.html`
- `Articles/2026/images/greater-estero-mobility/greater-estero-mobility-hero.svg`
- `Articles/2026/images/greater-estero-mobility/01-growth-mobility-dashboard.svg`
- `Articles/2026/images/greater-estero-mobility/02-greater-estero-corridor-schematic.svg`
- `Articles/2026/images/greater-estero-mobility/03-smart-signal-flow.svg`
- `Articles/2026/images/greater-estero-mobility/04-trp-versus-edaptive.svg`
- `Articles/2026/images/greater-estero-mobility/05-coordination-recovery.svg`
- `Articles/2026/images/greater-estero-mobility/06-traffic-safety-systems.svg`
- `Articles/2026/images/greater-estero-mobility/07-real-estate-mobility-test.svg`

The repository article references the standalone SVG files with relative paths so the artwork stays reusable and editable. The separate delivery package also includes a self-contained WordPress version with the infographic SVGs embedded directly, plus PNG exports for sites that strip SVG markup.

## Claim matrix

| Claim | Value / wording | Source | Publication treatment |
|---|---|---|---|
| Estero population | 38,365 in 2025; +3.9% since 2020 base | U.S. Census QuickFacts | Direct primary-source claim |
| Lee County population | 875,607 in 2025; +15.1% since 2020 base | U.S. Census QuickFacts | Direct primary-source claim |
| Mean commute | Estero 26.0 minutes; Lee County 29.4 minutes, 2020–2024 | U.S. Census QuickFacts | Label as mean, not current trip time |
| Major-road responsibility | Corkscrew, Three Oaks, Ben Hill Griffin and Estero Parkway Extension remain under Lee County; I-75 and U.S. 41 are FDOT | Village of Estero / 2017 study | Direct agency statement; verify if article is republished later |
| TOC capabilities | Monitors signals, travel times, volumes and disruptions; can inspect cameras and adjust signals; county cameras not recorded | Lee County Traffic Operations Center | Direct primary-source claim |
| Corkscrew TRP | 24/7; data every 15 minutes; reported cycles 110–170 seconds | Lee County DOT answers published by Engage Estero, July 9, 2026 | Attribute explicitly to published Q&A |
| Coordination recovery | Pedestrian main-road crossing: about 2–3 cycles; manual police control: about 1–2 cycles | Lee County DOT answers published by Engage Estero | Attribute and date-stamp |
| Edaptive | Optimizes cycle, offset and splits in real time; county deployment reported on Cypress Lake Drive | Econolite + Engage Estero | Do not imply current Estero deployment |
| Signal cost | Approximately $1.2–$1.5 million | Engage Estero / Lee County DOT discussion | Illustrative, attributed, not universal bid price |
| Wrong-way workflow | Detect, warn driver, notify traffic/public-safety centers, potentially warn motorists | FDOT District 1 ITS Architecture | Direct primary-source system description |
| Emergency priority | Dispatch/vehicle data can support targeted signal priority | Engage Estero + Econolite | Describe as developing/local capability, not universal deployment |
| REALTOR® guidance | Article 10 prohibits discrimination and steering | NAR 2026 Code of Ethics | Direct professional-standard reference |

## Editorial guardrails

1. Do not claim that signal technology raises property values.
2. Do not guarantee commute times or signal performance.
3. Do not imply Edaptive is deployed in Greater Estero unless Lee County confirms a specific corridor.
4. Distinguish current infrastructure from proposed or funded projects.
5. Keep Lee County-specific operational details attributed to the July 2026 Engage Estero Q&A.
6. Use objective sources consistently and avoid subjective neighborhood labels.
7. Recheck Census estimates, signal operations and project status before any later republication.

## WordPress publication checklist

1. Upload the hero and seven infographic files to the WordPress media library. PNG exports are included in the delivery package and are the safest default for WordPress.
2. Replace each relative `images/greater-estero-mobility/...` path in the repository HTML with its uploaded WordPress URL, or use the self-contained HTML version from the delivery package if inline SVG is allowed.
3. Use the 1600×900 hero PNG as the featured image.
4. Add the uploaded hero URL to the Open Graph and Twitter image meta fields.
5. Publish at the canonical slug shown above.
6. Replace the placeholder image URL in the news-home entry snippet.
7. Add the final entry to `Others/NewsHome.html` only after the public article and hero URLs resolve.
8. Test the article at desktop, tablet and phone widths.
9. Test every source link.
10. Confirm CCOR branding and the July 23, 2026 publication date.

## News-home entry template

```json
{
  "title": "Greater Estero Is Growing—and Mobility Is Part of the Housing Conversation",
  "url": "https://coconutcoastrealtors.org/greater-estero-is-growing-and-mobility-is-part-of-the-housing-conversation/",
  "date": "2026-07-23",
  "image": "REPLACE_WITH_UPLOADED_WORDPRESS_HERO_URL",
  "excerpt": "How smart signals, route reliability and Greater Estero's growth affect home searches, showing schedules and real-estate decisions for consumers and REALTORS®.",
  "category": "Consumer Guide",
  "featured": "true"
}
```

## Primary sources

- U.S. Census QuickFacts — Estero village: https://www.census.gov/quickfacts/fact/table/esterovillageflorida/EDU685223
- U.S. Census QuickFacts — Lee County: https://www.census.gov/quickfacts/fact/chart/leecountyflorida/PST045222
- Lee County Traffic Operations Center: https://www.leegov.com/dot/traffic/traffic-operations-center
- Lee County Traffic Overview: https://www.leegov.com/dot/traffic/overview
- Village of Estero Public Works: https://estero-fl.gov/public-works/
- Village Traffic/Roads: https://estero-fl.gov/for-residents/trafficroads/
- Village traffic-study update action: https://estero-fl.gov/village-wide-traffic-study-and-code-enforcement-among-items-addressed-by-council-on-january-3-2024/
- Engage Estero source article: https://esterotoday.com/how-technology-improves-traffic-in-greater-estero/
- Econolite Centracs: https://www.econolite.com/products/traffic-control-software/
- FHWA Traffic Signal Timing Manual, Chapter 9: https://ops.fhwa.dot.gov/publications/fhwahop08024/chapter9.htm
- FHWA ASCT Measures of Effectiveness: https://ops.fhwa.dot.gov/publications/fhwahop13031/index.htm
- FDOT District 1 Wrong-Way Detection: https://teo.fdot.gov/architecture/architectures/d1/html/servicepackages/tm25-10492.html
- NAR 2026 Code of Ethics: https://www.nar.realtor/about-nar/governing-documents/code-of-ethics/2026-code-of-ethics-standards-of-practice
- NAR steering guidance: https://www.nar.realtor/articles/steering-schools-and-equal-professional-service

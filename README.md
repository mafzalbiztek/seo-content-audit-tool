# SEO Content Audit — Deduplicated v2

Deploy this static folder to Vercel. Open index.html locally to use without hosting.

## Changes
- Existing 52 diagnostic checklist questions and legacy JSON IDs remain unchanged.
- Removed automatic weighted checklist score to prevent duplicate penalties.
- Added a unique issue register linking one finding to multiple checklist IDs.
- Added eight manually rated dimensions with approved weights: 15,15,20,15,10,10,10,5.
- Overall weighted score appears only when all eight dimensions have ratings.
- Added issue references and rubric version to CSV export.
- Existing single-audit JSON files and backup JSON files can be imported; missing new fields initialize blank.

## Important
The checklist groups' original proposed weights remain visible for historical reference, but do not drive the writer score. The unique issue register does not automatically set ratings. Review each issue's evidence and score each dimension independently. Export JSON backups regularly; browser localStorage is not server-backed.

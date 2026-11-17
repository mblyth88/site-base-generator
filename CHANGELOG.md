# Changelog

## v56 · 18 Nov 2026
- Kerb anchor trace: only high-confidence kerb points are locked in (max one per 15 m), joined with straight lines parallel to the boundary, with an 8 m minimum radius on every curve - removes the lumps around trees, shadows and parked cars.

## v55 · 18 Nov 2026
- Access restriction strips (sliver lots of 1.0 m or less between the site and a road) are flagged: the road stays a frontage, the strip is labelled on the plan with a red sheet note, and the JSON (schema 1.8) records it on the frontage and in the summary.

## v54 · 26 Oct 2026
- Version stamp in the header. First GitHub Pages release.

## v53 · 23 Oct 2026
- Live Ipswich road hierarchy from ePlan (via the read-only relay). The 2014 ICC map is the fallback, and the log says so.

## v52 · 20 Oct 2026
- Ipswich road hierarchy digitised from the 2014 ICC existing road hierarchy map.

## v51 · 19 Oct 2026
- Road hierarchy and major-road frontage in the export JSON (schema 1.7) for BCC, Logan, Moreton Bay and state roads.

## v50 · 19 Oct 2026
- Side-by-side houses on one lot traced as separate buildings.

## v49 · 19 Oct 2026
- Houses straddling lot lines, outlines aligned to the building axis, blue-grey roofs.

## v48 · 18 Oct 2026
- Cream and grey roofs, driveway cut-outs.

## v47 · Oct 2026
- Address ranges (86-88 …), near-number substitution, imagery size limit fix.

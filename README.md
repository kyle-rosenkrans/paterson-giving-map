# Paterson Giving Map

An interactive directory of the top donors — foundations, corporations, and individuals — to charitable causes based in Paterson, New Jersey, ranked by estimated giving from 2020 to 2025.

**Live page:** open `index.html` (or the GitHub Pages site for this repo). Bubble size = estimated Paterson giving; color = donor type; gold ring = existing KIPP Team & Family donor relationship. Search, filter by type / confidence / recipient, switch to the sortable table, click any donor for gift-by-gift sourcing, and copy or download the filtered list as CSV.

**Data:** `Paterson Giving Map - Donor Database.xlsx` holds the same dataset as a workbook — Top 100 donors, every individual sourced gift (883 rows), a Paterson-recipients rollup, donors ranked 101–150, and the methodology.

## How it was built

- IRS Form 990-PF grant schedules for every private foundation reporting a Paterson grantee (1,216 grants from 338 foundations, via the IRS e-file dataset / Grantmakers.io, cross-checked on ProPublica Nonprofit Explorer).
- Donor honor rolls and gala sponsor lists published by Paterson nonprofits (Paterson Habitat for Humanity, St. Joseph's Health Foundation, Oasis, Eva's Village, NJCDC and others).
- Press releases and NJ DCA Neighborhood Revitalization Tax Credit award tables, FY2021–FY2025.

Exact amounts are used where published; donor-roll tiers count at the midpoint; NRTC awards are split evenly among named contributors; unpriced sponsorships take a conservative floor. Each donor carries a High / Medium / Low confidence rating. Full methodology and caveats are in the page footer and the workbook's Methodology tab.

Prepared by the KIPP Team & Family advancement team. This is a research estimate from public sources, not audited data — verify any figure before citing it.

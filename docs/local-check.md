# Local check summary

- Theme: Everforest · Prism 0.1.1
- Manifest SHA-256: `313ebeb0397a5ece57b3540ad37ecd1d4e455e92f0aae1260795058675cf23a6`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 5.18:1, title 5.18:1, link 5.66:1, tag 4.9:1, code 4.87:1, mark 4.8:1, chosen 4.64:1.
  - Dark: body 7.38:1, title 7.38:1, link 5.74:1, tag 6.23:1, code 5.57:1, mark 4.74:1, chosen 5.03:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.

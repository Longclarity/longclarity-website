# LongClarity website update

This folder is a complete replacement for the current static website.

## What changed

- Replaced all eight product screenshots with current captures from the same Karl and Kari demonstration plan.
- Added a Retirement Modeling Report section using the first page of the supplied 17-page PDF.
- Explained that Premium users can save, share, or print the report PDF.
- Aligned homepage language with the in-app Plan Glossary, including Current Plan, Proposed Plan, Retirement Funding, Retirement Assets, Modeled Lifestyle Spending, Total Modeled Costs, Continuing Income, Asset Withdrawals, and Modeled Funding Through.
- Corrected the Explore explanation so it accurately describes when a Proposed Plan changes the Current Plan.
- Replaced the stale public Privacy Policy and Terms with the September 5, 2026 in-app versions, which reflect the removal of the former analytics service.
- Added direct homepage and Privacy Policy statements that LongClarity does not use third-party product analytics and does not transmit in-app feature-usage events to Long Clarity LLC.

## Xcode storage

The site is stored in the repository under `Website/LongClarity.com` as a reference-only folder. It appears in Xcode for convenient access, but it is not part of the RetireReady app target and is not copied into the app bundle.

## Deploy

Replace the repository's `index.html`, `styles.css`, `support.html`, `privacy.html`, `terms.html`, `assets/`, and `screenshots/` with the corresponding items in this folder. The support, privacy, terms, and brand files are unchanged copies from the live site; they are included so this folder can be deployed as a complete unit.

The `extras/` folder contains three useful current captures that are not referenced by the homepage. It does not need to be deployed.

## Screenshot mapping

- `dashboard.png` - current Dashboard and Retirement Modeling Report entry point
- `retirement-story.png` - current Your Retirement Story screen
- `retirement-funding.png` - current Retirement Funding chart and PDF / Print control
- `retirement-assets.png` - current Retirement Assets chart and PDF / Print control
- `explore-proposed.png` - Current Plan and Proposed Plan comparison
- `coach-plays.png` - current Coach Plays menu
- `what-would-it-take.png` - age-63 target screen
- `coach-modeled-paths.png` - age-63 modeled result, cropped only to remove the translucent iPhone status area
- `modeling-report.png` - page 1 rendered from the supplied Retirement Modeling Report PDF

# Family Financial Planning 101

A public, plain-language financial-literacy pack for families, built around four connected actions: **Spend deliberately, Earn resiliently, Protect the household and Invest the difference**.

The site is designed first for Uganda and East Africa, while avoiding product promotion and keeping jurisdiction-specific claims clearly sourced and reviewable. It is educational material—not personalised financial, investment, tax, legal or insurance advice.

## What is included

- A mobile-first learning journey and hand-drawn framework
- A private on-device diagnostic
- Five browser-only calculators
- A fully reconciled fictional family case study
- Printable A4 worksheets
- Linked deep dives into relevant Kenneth Legesi and Impala Market articles
- Source register, editorial policy and localisation guidance
- Calculation and content QA checks

## Preview locally

Open `index.html` directly, or serve the folder with any static server. No installation is required for the public page.

```bash
npm run check
npm run build
```

The build copies the public site into `dist/` for hosting. The page does not use cookies, analytics, remote fonts or third-party JavaScript.

## GitHub Pages

The included workflow validates the source and publishes `dist/`. In repository settings, set **Pages → Source** to **GitHub Actions**. The workflow runs on pushes to `main` and may also be started manually.

## Updating content

1. Review the relevant primary sources and update `sources/source-register.csv`.
2. Change the source content in `index.html` and, if relevant, `content/`.
3. Add an entry to `CHANGELOG.md`.
4. Run `npm run check` and `npm run build`.
5. Review print output and keyboard navigation.
6. Submit a pull request using the review checklist.

## Localising for another country

Read `docs/localisation-guide.md`. Replace currency, regulator links, legal references and market conventions only after verification. Do not copy Uganda-specific guidance into another jurisdiction by changing the country name alone.

## Governance

Conduct a light review quarterly and a full content/source/accessibility review annually. Review immediately after material changes to relevant regulation, taxes, deposit protection, pension rules or regulator/provider status.

## Licence

- Software code: MIT License (`LICENSE`)
- Educational text and original illustrations: Creative Commons Attribution 4.0 International (`LICENSE-CONTENT.md`)

No endorsement of any financial product or provider is implied.

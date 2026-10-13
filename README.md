# Incentive Calculator

Open index.html in a browser. No installation or build required.

## GitHub Pages

1. Upload index.html, styles.css, calculator.js and Quess.png to a GitHub repository root.
2. Open repository Settings → Pages.
3. Select Deploy from a branch, main, /(root), and Save.
4. Use the published URL displayed by GitHub.

The Excel file is not needed for hosting.

## Formula mapping

Level maps to E1. Monthly uses C6 target and D6:I6 achievements, with the exact six rate tiers, 80%/32-unit eligibility and level multipliers. Festive uses C10 target and E10/F10 achievements; D10 is calculated. The October bonus requires E10/C10 ≥65%; completion requires (E10+F10)/C10 ≥100%. A zero festive target preserves Excel's #DIV/0! error. Other sections use the exact rates in B14/B18/B22/B26. Their C-column volumes are calculated. Total maps to B2.

Initial Excel example: monthly 0; festive 30000; tablet 13500; wearable 5100; Note PC 10750; Care+ 1075; total 60425.

Blank inputs count as zero; negative numbers are flagged. Decimal inputs are supported, with no intermediate rounding. Clear inputs sets achievements to zero and restores targets to 100 and 200.

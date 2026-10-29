# India Tax Calculator (FY 2026-27 / AY 2027-28)

A small static site that estimates Indian income tax for a salaried resident
individual (below 60) under the new regime (sec 115BAC, default) and the old
regime, and shows which is lower.

Live site: https://newproductstrial.github.io/india-tax-calculator/

## Scope

- New regime slabs: 0-4L nil, 4-8L 5%, 8-12L 10%, 12-16L 15%, 16-20L 20%,
  20-24L 25%, above 24L 30%. Standard deduction Rs 75,000 on salary. Section
  87A rebate up to Rs 60,000 at taxable income up to Rs 12,00,000, with
  marginal relief.
- Old regime slabs: 0-2.5L nil, 2.5-5L 5%, 5-10L 20%, above 10L 30%. Standard
  deduction Rs 50,000. Section 87A rebate up to Rs 12,500 at taxable income up
  to Rs 5,00,000, with marginal relief. User-entered Chapter VI-A deductions
  (80C capped at Rs 1.5L).
- Surcharge with marginal relief; Health and Education Cess 4%.

## Exclusions

Capital gains and other special-rate income, HRA/exemptions, professional
tax, ages 60+, business income regime opt-outs. Estimate only, not tax advice.

## Sources

- https://www.incometaxindia.gov.in/tax-rates
- https://www.indiabudget.gov.in/doc/memo.pdf (Finance Bill 2026 memorandum)

Single-file app: everything is in `index.html`. No build step.

# Selected engineering work

Maintainer: [Thái Văn Tuấn](https://github.com/tuanthaidnc). I operate Wondroot
and collaborate with Codex on implementation and verification. These accounts
describe engineering concerns from my work; they do not disclose private code,
customers, supplier mappings or operational records.

## 1. Time-zone-aware delivery calendars

**Problem:** delivery estimates must combine processing and shipping business
days without shifting dates at DST boundaries or inventing holiday rules.

**Approach:** explicit civil-date arithmetic, configured time zones/weekdays and
holidays, staged date ranges, and unknown timings that stay unknown.

**Public artifact:** [commerce-calendar](https://github.com/tuanthaidnc/commerce-calendar).
Its tests exercise DST, closures, leap days, invalid inputs and stage ordering.
The independent library has not replaced the existing store resolver.

## 2. Financial completeness and aggregate ratios

**Problem:** partial source data can turn missing costs into false zero, and
averaging daily ratios can misstate a reporting period.

**Approach:** distinguish complete totals from known subtotals; compute the
ratio of numerator/denominator sums; preserve integer minor units and display
rounding separately. Blended store ROAS and advertising attribution are distinct.

**Public artifact:** [commerce-finance-math](https://github.com/tuanthaidnc/commerce-finance-math).
It contains only generic arithmetic and synthetic examples. It is not an
accounting product or a public version of the operational finance system.

## 3. Conservative provider line reconciliation

**Problem:** product names, similar titles and equal quantities do not prove
which order line a provider record belongs to.

**Approach:** exact IDs, explicit SKU crosswalks, quantity checks after identity,
and unresolved results for conflicts, ambiguous matches or duplicate claims.

**Public artifact:** [exact-line-matcher](https://github.com/tuanthaidnc/exact-line-matcher).
Inputs must already be scoped to an authorized order/provider snapshot. It
does not connect to providers, route orders, release files or write fulfillment.

## 4. Storefront and operational UI work

At [Wondroot](https://wondroot.com), my work also covers personalized-product
storefront behavior and operational interfaces. Practical concerns include
accessible controls, responsive layouts, preserving native purchase flows,
truthful source freshness and verification after deployment.

Private themes, operational applications, product artwork and customer-facing
business workflows are not included in the OSS repositories. Their appearance
here does not imply source availability, measured revenue uplift, independent
audits or community adoption.

## Evidence boundaries

Public source, releases and CI are inspectable through each repository. All
examples use synthetic data. These repositories were started in October2026;
they are not presented as long-established projects. Real external use and
feedback are still needed. Codex assistance and passing tests are not security
certification or independent review.

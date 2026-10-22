# Thái Văn Tuấn

I operate [Wondroot](https://wondroot.com) and build practical software for small
commerce workflows, including Shopify development and operational tools.

## Open-source work

**Focus:** small, reusable JavaScript tools with explicit inputs, documented
limits and reproducible behavior. I maintain the projects below directly.

| Project | Problem addressed | Evidence |
| --- | --- | --- |
| [commerce-calendar](https://github.com/tuanthaidnc/commerce-calendar) | Business-day and staged delivery estimates | [Tests](https://github.com/tuanthaidnc/commerce-calendar/actions), [source release](https://github.com/tuanthaidnc/commerce-calendar/releases/tag/v0.1.0) |
| [commerce-finance-math](https://github.com/tuanthaidnc/commerce-finance-math) | Ratio of sums, known zero versus missing money | [Tests](https://github.com/tuanthaidnc/commerce-finance-math/actions), [API and examples](https://github.com/tuanthaidnc/commerce-finance-math#readme) |
| [exact-line-matcher](https://github.com/tuanthaidnc/exact-line-matcher) | Exact line identity, ambiguity and duplicate claims | [Tests](https://github.com/tuanthaidnc/exact-line-matcher/actions), [API and examples](https://github.com/tuanthaidnc/exact-line-matcher#readme) |

All three are early-stage standalone libraries inspired by practical work, not
copies of private production systems. No verified external adoption or npm
publication is claimed. Each includes an MIT license, synthetic examples,
TypeScript declarations and reproducible runtime/package checks.

### [commerce-calendar](https://github.com/tuanthaidnc/commerce-calendar)

An MIT-licensed JavaScript library for business-day calendars and staged
processing/shipping estimates, with explicit time zones and configurable
holidays. It includes TypeScript declarations, examples and automated tests.

- [Source release 0.1.0](https://github.com/tuanthaidnc/commerce-calendar/releases/tag/v0.1.0)
- [CI results](https://github.com/tuanthaidnc/commerce-calendar/actions)
- [Roadmap](https://github.com/tuanthaidnc/commerce-calendar/blob/main/ROADMAP.md)
- [API reference](https://github.com/tuanthaidnc/commerce-calendar/blob/main/docs/API.md)
- [Maintenance policy](https://github.com/tuanthaidnc/commerce-calendar/blob/main/MAINTAINERS.md)
- [Report a reproducible issue](https://github.com/tuanthaidnc/commerce-calendar/issues/new/choose)

**Status:** early-stage project, with no verified external adoption yet. It is
not published on npm or integrated into Wondroot production. Practical store
experience inspired it; this does not imply public usage or community scale.

## Approach

I work with Codex to implement and test software. Changes should have clear
scope, reproducible checks and honest documentation of limitations. Public
examples use synthetic inputs; private business and customer records stay private.

For library questions and contributions, use its GitHub issues and pull requests.

## Background

My private work includes storefront and operational software for Wondroot.
Public projects are separately scoped and use synthetic examples. I welcome
practical bug reports and contributions that make the library useful to other
small commerce developers.

See [selected engineering case studies](case-studies/README.md) for the problems,
decisions and limits behind this portfolio.

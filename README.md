# Nutrisystem (Wellina by Nutrisystem)

Nutrisystem is a direct-to-consumer subscription meal delivery service for
weight loss, founded in **1972 by Harold Katz** and headquartered in
**Fort Washington, Pennsylvania**. The legal operating entity is
**Nutrisystem, LLC**, now owned by **Wellful, Inc.** (a Kainos Capital
portfolio company). Tivity Health divested the brand in October 2020.

The consumer-facing site has been rebranded **"Wellina by Nutrisystem"** —
"Your All in One Nutrition Marketplace" — pulling together the flagship
Nutrisystem program with sister brands **South Beach Diet** (acquired
December 2015 for $15M) and **Jenny Craig** (intellectual property
acquired by Wellful in fall 2023 after Jenny Craig's Chapter 7 bankruptcy
and relaunched as e-commerce meal delivery). LinkedIn classifies the
company under **Wellness and Fitness Services** with **501–1,000
employees**. **Stephen Mikulak** was named President in 2021.

This repository is an API Evangelist profile of the company. **Nutrisystem
publishes no public developer APIs, no OpenAPI specs, no SDKs, and no
developer portal.** Its only programmatic surface beyond the e-commerce
sites is a closed first-party consumer mobile app (iOS / Android) for food
logging, weight tracking, journaling, and meal-plan adjustments, with no
advertised integrations to Apple Health, Google Fit, Fitbit, or any
third-party platform. The [`github.com/nutrisystem`](https://github.com/nutrisystem)
organization exists but contains a single inactive CSS repository last
updated in March 2015.

## Brand Portfolio (Wellina Marketplace)

| Brand | Category | Notes |
|---|---|---|
| Wellina by Nutrisystem | Umbrella Marketplace | "Your All in One Nutrition Marketplace" — created by Nutrisystem |
| Nutrisystem | Core Weight-Loss Subscription | Flagship prepackaged meal-delivery plan |
| South Beach Diet | Sister Brand — Low-Carb / Healthy-Fat | Acquired Dec 2015 for $15M; site now redirects to nutrisystem.com/products/brands |
| Jenny Craig | Sister Brand — Meal Delivery + Coaching | IP acquired by Wellful Inc. fall 2023; Meal Delivery Plans, Weight Loss Program, Club Jenny membership |
| High Protein | Specialty Plan | High-protein meal plan line |
| Menopause Support | Specialty Plan — Women's Health | Menopause-stage nutrition |
| Low Carb (GLP-1 Friendly) | Specialty Plan | Positioned as complementary to GLP-1 medications |
| Club Advantage | À La Carte Membership | Individual meals/snacks starting at $1.99 per meal |

Source: [nutrisystem.com](https://www.nutrisystem.com) and
[nutrisystem.com/products/brands](https://www.nutrisystem.com/products/brands).

## Corporate Facts

| Fact | Value |
|---|---|
| Founded | 1972 |
| Founder | Harold Katz |
| Headquarters | 1100 Virginia Dr #175, Fort Washington, PA 19034, USA |
| Legal Entity | Nutrisystem, LLC |
| Parent Company | Wellful, Inc. |
| Owner | Kainos Capital (acquired from Tivity Health on October 19, 2020) |
| Prior Owner | Tivity Health (December 2018 – October 2020) |
| President | Stephen Mikulak (2021) |
| Industry | Wellness and Fitness Services |
| Employees (LinkedIn) | 501–1,000 |
| Service Area | United States and Canada |
| Business Model | Direct-to-consumer subscription meal delivery + auto-delivery + mobile-app coaching |

## Digital Surface

| Surface | Notes |
|---|---|
| E-commerce site | [nutrisystem.com](https://www.nutrisystem.com) — auto-delivery checkout, account dashboard, plan selection |
| Account dashboard | [/login](https://www.nutrisystem.com/login) — auto-delivery management, order edits |
| FAQ portal | [leaf.nutrisystem.com/faqs](https://leaf.nutrisystem.com/faqs/) — 5 categories |
| Nutrisystem mobile app | iOS + Android — food logging, weight tracking, journal, meal-plan adjustments |
| Jenny Craig mobile app | iOS + Android (`wellful.jennycraig`) — meal delivery management |
| Chat support | In-site chat widget |
| Phone support | 1-800-435-4074 (main) / 1-800-585-5483 (cancellation) |

## API Surface Assessment

| Surface | Status |
|---|---|
| Public developer portal | None |
| Public OpenAPI / AsyncAPI specs | None |
| Public REST / GraphQL APIs | None |
| SDKs / CLIs | None |
| Mobile-app third-party integrations | None advertised (no Apple Health / Google Fit / Fitbit / MyFitnessPal) |
| GitHub public repositories | 1 stale (`CSS`, last updated March 12, 2015) |
| Webhooks | None documented |
| Status page / changelog / release notes | None public |
| Sandbox / Console | None |
| API Evangelist tier | **Tier 3 — no-apis**; pure consumer subscription with a closed first-party app stack |

## Artifacts in this Repository

| Path | Description |
|---|---|
| [`apis.yml`](./apis.yml) | apis.yml 0.19 index — brand portfolio, corporate facts, digital surface, API assessment, common properties |
| [`vocabulary/nutrisystem-vocabulary.yml`](./vocabulary/nutrisystem-vocabulary.yml) | Domain vocabulary covering corporate facts, brands, plans, subscription/meal-delivery terms, and ownership history |
| [`json-ld/nutrisystem-context.jsonld`](./json-ld/nutrisystem-context.jsonld) | JSON-LD context modelling Nutrisystem as `schema:Corporation` with subsidiaries, brands, and product offerings |

No `openapi/`, `asyncapi/`, `capabilities/`, `rules/`, `json-schema/`,
`examples/`, `plans/`, `rate-limits/`, or `finops/` artifacts are produced
for this repository — there is no public API surface to back them, and the
pipeline rule is to avoid empty / placeholder specs.

## Key Sources

- Marketing site: <https://www.nutrisystem.com>
- Brand portfolio: <https://www.nutrisystem.com/products/brands>
- FAQ: <https://leaf.nutrisystem.com/faqs/>
- Privacy / corporate footer: <https://www.nutrisystem.com/jsps_hmr/contact_us/policy_pol.jsp>
- Sister brand — South Beach Diet: <https://www.southbeachdiet.com> (redirects to nutrisystem.com/products/brands)
- Sister brand — Jenny Craig: <https://www.jennycraig.com>
- GitHub organization: <https://github.com/nutrisystem>
- LinkedIn: <https://www.linkedin.com/company/nutrisystem>
- Wikipedia — Nutrisystem: <https://en.wikipedia.org/wiki/Nutrisystem>
- Wikipedia — South Beach Diet: <https://en.wikipedia.org/wiki/South_Beach_Diet>
- Wikipedia — Jenny Craig, Inc.: <https://en.wikipedia.org/wiki/Jenny_Craig,_Inc.>
- Kainos Capital portfolio (Wellful entry): <https://www.kainoscapital.com/portfolio/>

## Maintainer

[Kin Lane](mailto:kin@apievangelist.com) — [API Evangelist](https://apievangelist.com).

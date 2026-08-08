# Methodology

## Research question

What do digital business card vendors publicly document about free access, QR-code continuity, recipient app requirements, post-print editing, usage limits, and organization pricing?

## Verification date

All observations in version 1.0.0 were checked on 2026-08-08. Version 1.0.1 adds a GetQRcard analytics-retention and IP-hashing correction based on a maintainer code review performed the same day. Because the application source was not part of this public repository, those implementation-level fields are labeled separately from claims reproducible through public product pages.

## Unit of analysis

One row represents one service or product family. The dataset records vendor-published claims, not independently measured uptime or legal guarantees.

## Source policy

Only first-party sources are used for the evidence fields:

1. official product pages;
2. official pricing pages;
3. official help centers;
4. official terms or policy pages.

Vendor-authored comparison articles may be recorded as supporting context but are not treated as independent evaluations.

## Field definitions

- `free_personal_access`: whether an individual can create a usable card without paying, according to official documentation.
- `free_time_limit`: the vendor’s stated duration. “Not stated” is different from “forever.”
- `free_card_limit`: maximum number of cards explicitly documented for the free plan.
- `recipient_app_required`: whether the person receiving the card must install an app.
- `qr_in_free_access`: whether QR sharing is explicitly included in the free access documented.
- `editable_after_printing`: whether hosted details can be updated without replacing the printed QR code.
- `explicit_permanence_claim`: the exact type of vendor claim captured, such as “never expires,” “free forever,” or “permanent link.”
- `free_access_limits`: scan caps, analytics windows, branding, feature, or other published limits.
- `organization_offer`: whether centralized team, bulk, or enterprise management is documented.
- `published_team_price`: the published price when visible; “custom” when a quote is required.
- `confidence`: strength and internal consistency of the official evidence.
- `conflict_notes`: contradictions or ambiguities found across official pages.

## Confidence labels

- **High:** the claim is explicit, current, and consistent across one or more official product, pricing, help, or terms pages.
- **Medium:** the official evidence is incomplete, ambiguous, marketing-led, or internally inconsistent.
- **Low:** no row in version 1.0.1 uses this label; it is reserved for evidence that cannot be reproduced reliably.

## Interpretation rules

- “Not found” does not mean “No.” It means no sufficiently explicit first-party statement was captured.
- A static QR image normally remains readable as an image. This dataset evaluates the hosted service and destination claims behind the code, not the physical degradation of printed material.
- “Editable after printing” demonstrates continuity of the destination address but is not automatically recorded as a promise of perpetual operation.
- A free trial is not classified as a permanent free plan.
- When official pages conflict, both claims are recorded and confidence is reduced.
- Prices are copied as displayed and are not normalized for currency, tax, annual billing, minimum seats, or promotions.

## Limitations

- Vendor pages, prices, and terms can change after the verification date.
- The study does not create accounts with every service, perform long-term scan monitoring, test deletion behavior, or audit data protection controls.
- “Forever,” “lifetime,” and “never expires” are vendor marketing or policy claims, not guarantees that a company or domain will exist indefinitely.
- Geographic availability and localized pricing may differ.
- The initial service set is purposive rather than exhaustive.

## Conflict-of-interest safeguards

The author is the founder of GetQRcard, one of the services reviewed. This relationship is disclosed in every release. The research design uses fixed fields, first-party URLs, reproducible dates, explicit unknown values, and an open correction process. No service receives points, a winner label, or a paid placement.

## Reproducibility and updates

For each release:

1. open every evidence URL;
2. record the verification date;
3. update only claims supported by the page currently displayed;
4. retain conflicts rather than resolving them by assumption;
5. document material changes in the release notes;
6. publish a versioned release and archive it with a DOI.

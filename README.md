# QR Permanence & Free Digital Business Card Transparency Index 2026

An evidence-first comparison of free digital business card services, QR-code continuity claims, recipient friction, editability after printing, and public pricing transparency.

**Evidence checked:** 2026-08-08  
**Dataset version:** 1.0.0  
**Coverage:** 14 services  
**License:** CC BY 4.0

**Public repository:** https://github.com/ralphy-ctrl/qr-card-transparency-index-2026

## Why this dataset exists

“Free digital business card” can mean very different things: a permanent free card, a limited trial, a card with scan caps, or a free profile whose terms may change. A QR code may remain technically readable while the hosted destination behind it is limited, changed, or discontinued.

This dataset records what each vendor currently says on its own official website. It separates:

- whether a personal card is free and for how long;
- whether the recipient needs an app;
- whether the card can be edited after the QR code is printed;
- whether the vendor explicitly promises that the QR code or card never expires;
- free-tier limits, organization features, and published team pricing;
- contradictions found across a vendor’s own pages.

It is a documentation audit, not a laboratory uptime test and not a prediction that any company will operate forever.

## Headline findings

- Most reviewed services advertise a free entry point, but “free” is not consistently defined.
- “Editable after printing” is common; an explicit “never expires” or “permanent” claim is much less common.
- Several vendors impose limits through card counts, scan caps, analytics windows, or paid organization features.
- Public documentation sometimes conflicts within the same vendor’s website. Those conflicts are retained in the data.
- Recipient-side app installation is generally unnecessary among the services whose documentation answers the question clearly.

## Services reviewed

| Service | Free personal access | Recipient app | Editable after print | Explicit permanence claim | Evidence confidence |
|---|---|---:|---:|---:|---|
| GetQRcard / MaCarteQR | Yes, advertised free for life | No | Yes | Yes | High |
| HiHello | Free-forever plan | No | Yes | Yes | High |
| Blinq | Free-forever plan | No | Yes | Not found | High |
| Wave Connect | Free plan | No | Yes | Yes | High |
| Popl | Free plan | No | Yes | Not found | High |
| OneCard | Free-forever core plan | No | Yes | Not found | Medium |
| ShareEcard | Free with no stated time limit | No | Yes | Yes | High |
| Lynkle | Free-forever plan | No | Yes | Yes | High |
| Cardyvo | Free-forever plan | No | Yes | Not found | Medium |
| Yoyo | Free tier advertised | No | Yes | Not found | Medium |
| Uniqode | First individual card free | No | Yes | Not found | Medium |
| QRCodeChimp | Free-forever card advertised | No | Yes | Card-for-life claim | High |
| V1CE | Free card advertised; trial wording also appears | No | Yes | Mixed wording | Medium |
| QR TIGER | Lifetime freemium QR plan; vCard access unclear | No | Yes for dynamic QR | Free plan has no expiry, with scan caps | Medium |

“Not found” means no sufficiently explicit claim was captured in the official pages reviewed. It does not mean the QR code expires.

## Files

- `data.json` — machine-readable observations and source URLs.
- `METHODOLOGY.md` — definitions, inclusion rules, confidence labels, and limitations.
- `SOURCES.md` — human-readable evidence register.
- `PROJECT_PROFILE.md` — verified history, publisher, operating model, and version note for GetQRcard.
- `PRESS_KIT_COPY.md` — reusable English and French descriptions, founder answers, press angles, and prohibited stale claims.
- `ARTICLE_EN.md` and `ARTICLE_FR.md` — evidence-based long-form articles ready for external publication.
- `CONTRIBUTING.md` — vendor correction and community contribution process.
- `CITATION.cff` — citation metadata for GitHub and Zenodo.

## Reuse and citation

You may reuse this dataset under the Creative Commons Attribution 4.0 International license. Please cite the dataset title, version, author, verification date, and DOI once a DOI is issued.

Suggested citation before DOI publication:

> Saive, Rafaël. *QR Permanence & Free Digital Business Card Transparency Index 2026*. Version 1.0.0, 8 August 2026. CC BY 4.0.

## Disclosure

This dataset was initiated by Rafaël Saive, founder of GetQRcard. GetQRcard.com and MaCarteQR.fr are services of Le Chemin Numérique ASBL, a Belgian nonprofit based in Liège, Belgium. The affiliation is disclosed because GetQRcard is included in the comparison.

The publisher is registered in Belgium under enterprise number 1039.717.066. Its documented work includes digital-use diagnostics, workshops for pupils, educational teams and parents, and the EDU Filter school DNS pilot tested at Institut Saint-Paul in Liège. The relationship and supporting evidence are described in `PROJECT_PROFILE.md`.

To reduce bias, the same field definitions are applied to every service, all observations link to official vendor pages, missing evidence is marked as unknown rather than inferred, and vendors are invited to submit documented corrections.

Project websites: [getqrcard.com](https://getqrcard.com/), [macarteqr.fr](https://macarteqr.fr/), [lecheminnumerique.be](https://www.lecheminnumerique.be/).

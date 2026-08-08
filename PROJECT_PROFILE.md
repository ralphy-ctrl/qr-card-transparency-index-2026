# GetQRcard: verified project profile

## Canonical description

GetQRcard is a multilingual digital business card service published by Le Chemin Numérique ASBL, a Belgian nonprofit based in Liège. A user receives a short, permanent GetQRcard address that can be printed as a QR code on a paper card, badge, shop window, vehicle, stand, or email signature. The address stays fixed while the card’s contact details can be updated from the user’s account, so previously printed QR codes continue to show the current information.

The personal free plan includes one editable card, its permanent QR code, a downloadable vCard contact, an email signature, and thirty days of scan statistics. The recipient does not need an app: the card opens in a browser and can be saved using the contact format supported by iPhone and Android. The reviewed service states that the free card has no time limit and carries no advertising.

The paid plan costs €15 per year on the pricing page reviewed on 8 August 2026. It adds unlimited cards, spreadsheet-based bulk generation, a payment-provider-confirmed account-holder name, hosted PDF documents, and unlimited scan-history retention. If the subscription ends, the first card returns to the free plan and remains active and editable; additional cards are paused rather than deleted. Apple Wallet and Google Wallet support was announced as in development for 15 September 2026 and is therefore not counted as currently available in this release.

## Publisher

**Legal name:** Le Chemin Numérique ASBL  
**Legal form:** Belgian nonprofit association  
**Registered office:** Quai du Roi-Albert 114, box 3, 4020 Liège, Belgium  
**Belgian enterprise number:** 1039.717.066  
**Public website:** https://www.lecheminnumerique.be/  
**GetQRcard domains:** https://getqrcard.com/ and https://macarteqr.fr/

Belgium’s official Crossroads Bank for Enterprises lists the association as active and in a normal legal situation since 1 July 2026. It records the legal form as a nonprofit association, the Liège registered office, the official website, and two directors: Florence de Rochelée and Rafaël Saive.

The nonprofit’s public mission is to help primary schools in Wallonia, educational teams, families, associations, and small structures handle everyday digital questions through practical support without unnecessary jargon.

Its documented activities include:

- digital-usage diagnostics and action plans adapted to a school’s resources;
- student workshops about passwords, phishing, social media, personal data, inappropriate content, and balanced use;
- workshops for educational staff and parents;
- annual support and follow-up;
- EDU Filter, a pilot DNS-filtering project designed for schools.

## Evidence of technical work

EDU Filter was tested for several months at Institut Saint-Paul, a nursery and primary school in Liège. The nonprofit’s technical documentation describes a dedicated instance for each school, local recursive DNS resolution with Unbound instead of forwarding requests to a public resolver, infrastructure hosted in Belgium, detailed DNS-query logging disabled in normal operation, operational logs kept for no more than fourteen days, and incident traces deleted within seventy-two hours after a diagnostic is closed.

The documentation also states the system’s limits: it operates only on the configured school network and does not replace antivirus software, device updates, account security, education, or adult supervision.

## GetQRcard privacy and operating model

The current GetQRcard privacy policy states that account and card content are hosted by OVH in France/the EU. Passwords are hashed; IP addresses used for scan statistics and anti-abuse controls are hashed and salted rather than stored in plain text. The service states that it uses no advertising cookies, no third-party analytics platform, and does not sell or rent personal data.

The service’s public impact page says that payments first cover operating costs such as hosting, domain names, email, backups, maintenance, and development. Because the publisher is a nonprofit with no shareholders, any surplus is described as funding Le Chemin Numérique’s work with primary schools in Wallonia.

## Version history and correction

The first version of Le Chemin Numérique’s article dated 20 July 2026 described an earlier GetQRcard architecture with no account and card data encoded in the URL. The publisher updated that article on 8 August 2026.

The corrected article now matches the current GetQRcard v0.5.8 product: an account is required, the QR contains a permanent short address, and account and card content are hosted so the card can be edited after printing. This dataset relies on the current article together with the product, pricing, FAQ, “Why us,” impact, and privacy pages.

## Primary sources

- https://getqrcard.com/
- https://getqrcard.com/comment-ca-marche
- https://getqrcard.com/tarifs
- https://getqrcard.com/faq
- https://getqrcard.com/pourquoi-nous
- https://getqrcard.com/impact
- https://getqrcard.com/confidentialite
- https://getqrcard.com/organisations
- https://www.lecheminnumerique.be/
- https://www.lecheminnumerique.be/mentions-legales.html
- https://www.lecheminnumerique.be/projet-pilote-edufilter.html
- https://www.lecheminnumerique.be/projet-pilote-edufilter-technique.html
- https://www.lecheminnumerique.be/questions-frequentes.html
- https://www.lecheminnumerique.be/blog-macarteqr.html
- https://kbopub.economie.fgov.be/kbopub/zoeknummerform.html?lang=en&nummer=1039717066&actionLu=Rechercher
- https://www.ejustice.just.fgov.be/cgi_tsv/list.pl?language=fr&btw=1039717066&page=1&view_numac=1039717066#SUM

# Catalat Changelog

All notable public product updates for Catalat should be documented here.

This changelog covers the **public-facing product evolution** and the positioning of the platform. Internal operational details, private infrastructure notes, and sensitive implementation specifics remain outside this repository.

## v3.2.0 - 2026-05-16

### System release

- Registered the current Catalat release as a system changelog focused on implementation, customer panel changes, generated public sites, integrations, bug fixes and technical documentation.
- Updated the public updates page to avoid mixing product changelog with institutional copywriting changes.
- Clarified that the public repository tracks product history and public documentation, while implementation details remain in the private codebase.

### Catalog modes and generated sites

- Integrated newer catalog modes into signup, editing, customer panel and generated public sites.
- Kept the generic mode for businesses that do not fit a specific catalog model.
- Refined generated public filters so they stay focused on search, price range, category and location where applicable.
- Added external CTA support for item pages, allowing a customer to link an item to an external purchase, booking or information page without turning Catalat into a full ecommerce platform.

### Customer panel

- Added and refined controls for blog visibility, Google indexing, brand assets, favicon removal, cache refresh and catalog mode configuration.
- Improved mobile navigation and card organization inside the customer panel.
- Clarified settings that affect the generated public site, such as index/noindex and public content controls.

### Bug fixes and validation

- Fixed broken-character cases in generated public content and system text.
- Improved numeric and monetary validation for BRL, USD and EUR formats.
- Fixed visual issues in long cards, border styles, logo fallbacks and public error pages.
- Adjusted demo accounts so public demos do not expire or fall into inactive-site error screens.
- Reviewed 403/404 behavior for public customer sites and Catalat system pages.

### Technical documentation

- Private repository documentation should be updated whenever behavior, maintenance or integrations change.
- Public release notes should describe user-visible system upgrades without exposing sensitive implementation details.


## v3.1.0 - 2026-05-01

### Expanded catalog modes

- Expanded Catalat beyond the original product, vehicle and real-estate demos.
- Added public positioning and demos for:
  - services
  - events and party catalogs
  - pets and animals
  - food and menu catalogs
  - beauty and aesthetics
  - courses and classes
- Kept a generic mode for business types that are not yet covered by a dedicated catalog mode.

### Customer panel refinements

- Improved the customer panel organization around catalog mode, blog controls, site cache refresh and Google/search visibility.
- Added public-site SEO visibility controls so customers can decide whether a catalog should be indexed or hidden from search engines.
- Refined brand controls for logo, favicon and public-site visual presentation.
- Improved mobile menu behavior in the customer panel.

### Public site improvements

- Added more flexible public-site visual theming with brand-tinted backgrounds.
- Refined public catalog filters so they stay focused on search, price range, category and location where applicable.
- Improved item detail presentation across newer catalog modes.
- Continued improving multilingual copy across Portuguese, English, Spanish and French.

### Billing and app-readiness work

- Advanced recurring-payment support for subscription flows while keeping a safer return path from external checkout screens.
- Continued preparing Catalat for app-store distribution as a lightweight customer-panel access app.

## v3.0.0 - 2026-04-23

### Product maturity

- Established Catalat as a mature **catalog-first SaaS** for products, vehicles, and real-estate use cases.
- Consolidated the product message around **fast public sites + simple private panel + direct-contact conversion**.
- Formalized the public product milestone as **v3.0.0**.

### Public product experience

- Strengthened the public showcase around real demos for:
  - product catalogs
  - vehicle showrooms
  - real-estate catalogs
- Highlighted the multilingual customer panel and the public-site publishing workflow.
- Refined the public messaging around direct-contact operations instead of ecommerce checkout complexity.

### Performance and trust

- Added public PageSpeed proof with strong desktop and mobile results.
- Reinforced the positioning of Catalat as a lightweight public website layer designed for speed, clarity, and local SEO value.

### Public repository

- Rebuilt the public `README.md` to present Catalat as a serious product for clients, evaluators, strategic partners, and potential collaborators.
- Added a first official changelog structure to support future releases, fixes, and feature notes.

## Planned next public release areas

- Public updates page aligned with the institutional website
- clearer release cadence and version communication
- more structured release notes for customer-facing improvements
- public roadmap signals where appropriate

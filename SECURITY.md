# Security Policy

## Reporting a vulnerability

If you believe you found a vulnerability in Catalat, do not publish the details in a public issue.

Use one of the official support channels:

- Email: support@cata.lat
- Support page: https://cata.lat/support
- WhatsApp: https://wa.me/5521980345097

Please include:

- A clear description of the issue.
- The affected URL or feature.
- Steps to reproduce, if safe to share.
- Screenshots or logs only when they do not expose secrets, customer data or private credentials.

## Scope

This public repository is an institutional profile repository. The production SaaS source code is private.

Security reports should focus on the live Catalat product, public website, customer panel, public catalog websites or official infrastructure exposed to customers.

## Repository safeguards

Do not commit production source code, environment files, signing keys, service-account files, API credentials, database exports, customer data, APKs or app bundles to this public repository. Preventive ignore rules are maintained in `.gitignore`, but credentials must never rely on ignore rules as their only protection.

## Responsible disclosure

We ask that you give us reasonable time to investigate and fix a valid report before public disclosure.

# Certificate Management

## Problem

Certificate handling needed to support issuance and verification across repeated enrolments and archived accounts. Resending an existing certificate also needed to preserve its original content.

## My contribution

I extended certificate-related plugins and their integration with scheduler and administrative tools. My work included CSV issuance, certificate elements, verification, PDF handling and archived-user display.

## Features

- CSV-based certificate issuance and duplicate-record handling.
- Verification by name or certificate code, with QR-related fixes.
- Issuance and expiry date handling.
- Custom name formatting and certificate elements.
- PDF downloads with learner identification in filenames.
- Reuse of issued PDFs when resending certificates.
- Original-identity display and search for archived certificate holders.
- Scheduler controls for certificate selection, issuance and deletion.

## Technical decisions

For resending, I worked on reusing the existing issued PDF. A new certificate could be generated after the prior issue was deliberately removed. Archived-account handling required distinguishing stored historical identity from the current account's display values.

## Outcome

The implemented changes support certificate administration and verification across account lifecycle changes, while preserving issued content during resends.

## Technologies

PHP, SQL/MySQL, Moodle certificate components, PDF rendering and JavaScript administration interfaces.

[Back to portfolio](README.md)

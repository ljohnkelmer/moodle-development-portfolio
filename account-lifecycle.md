# Account Lifecycle Management

## Problem

The LMS needed account verification and inactivity-management tools that preserved historical records and gave administrators control over account archival and restoration.

## My contribution

I developed account lifecycle functionality and extended authentication-related components. My work included verification state, inactivity evaluation, warning emails, archive/restore tools and operational reporting.

## Features

- Email verification state and resend handling.
- Access controls for unverified accounts.
- Inactivity and archive-eligibility evaluation.
- Warning notifications with editable email templates.
- Manual archival and administrator restoration tools.
- Identity tracking and audit history for archived accounts.
- Guarded automatic archival and configurable processing limits.
- Report-only/dry-run controls, operational reporting and an emergency stop.
- Background-task recovery and account-state simulation tools.

## Technical decisions

The implementation included a read-only evaluation stage and report-only controls so administrators could inspect potential actions. Archive and restore handling retained identity tracking and audit records. Access policy checks were also applied to additional authentication paths.

## Outcome

Administrators have tools to review account states, perform lifecycle actions and inspect their history. The case study describes implemented functionality; repository history alone does not establish deployment or operational outcomes.

## Technologies

PHP, SQL/MySQL, Moodle local/authentication components, scheduled tasks and administrative reports.

[Back to portfolio](README.md)

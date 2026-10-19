# Payments and Enrolment

## Problem

The LMS needed to handle individual purchases and company bookings, with payment confirmation leading to the correct learner enrolments. Re-enrolment also needed to preserve existing account and payment history.

## My contribution

I developed and extended payment forms, cart behaviour and confirmation tools. My work covered manual payments, corporate submissions, voucher handling and re-enrolment processing.

## Features

- Individual and company payment submission forms.
- Multiple-enrollee uploads with input validation.
- Editable shopping cart quantities and appropriate checkout routing.
- Entry of the actual amount paid for manual submissions.
- Background confirmation jobs with progress feedback.
- Voucher validation, chapter/department restrictions and redemption reporting.
- Re-enrolment routing with archived-account rollover and payment history preservation.
- Extension request forms with supporting attachments and support notifications.
- HTML email templates with payment details and requester Reply-To/CC handling.

## Technical decisions

I worked on retry handling and duplicate safeguards in payment and re-enrolment paths. Background processing was used for bulk operations. Account rollover required linking historical records to the appropriate account rather than discarding prior transactions.

My contribution also included resolving checkout failures for accounts without company membership and improving the feedback shown when a confirmation job could not be queued.

## Outcome

The implemented features support individual and corporate booking scenarios, with administrative tools for confirming submissions and tracking enrolment processing.

## Technologies

PHP, JavaScript, SQL/MySQL, Moodle background tasks, DataTables and PayMongo-related LMS components.

[Back to portfolio](README.md)

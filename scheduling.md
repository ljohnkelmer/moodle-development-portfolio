# Training Scheduling

## Problem

Practical training needed booking tools for learners and administrators, including repeated sessions, reminders and grading. Changes to bookings also needed to respect existing certificate and attendance records.

## My contribution

I enhanced the existing scheduler and practical training calendar. My work covered booking interfaces, repeated slots, grade synchronization, notifications and safeguards around reassignment or removal.

## Features

- AJAX booking and action-progress feedback.
- Background creation of repeated training slots.
- Improved appointment forms and certificate-sending controls.
- Grade synchronization between appointments and the gradebook.
- Booking links in notifications and recipient eligibility checks.
- Reminder and restriction handling.
- Trainee reassignment with checks for existing certificate records.
- Present/future schedule display and configurable past-schedule visibility.

## Technical decisions

I traced how booking actions affected grading and certificate issuance. Reassignment and removal paths were updated to check related records. Notification handling was adjusted to account for booking restrictions and the intended recipient.

## Outcome

The scheduler provides more booking and administrative controls, with clearer progress feedback and checks around historical training records.

## Technologies

PHP, JavaScript, AJAX, SQL/MySQL, Moodle activity plugins and background tasks.

[Back to portfolio](README.md)

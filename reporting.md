# LMS Reporting

## Problem

Training administrators needed to view learner progress and training results across courses, chapters and departments. Different reporting requirements also called for spreadsheet exports and administrative notes.

## My contribution

I developed a chapter reporting block from spreadsheet requirements and enhanced existing course, billing and trainee reports. My work included query logic, DataTables interfaces, report filters and exports.

## Features

- Chapter reporting with month filters and browser-side status filtering.
- Course progress and assessment results, including a calculated written-test percentage.
- Monthly and quarterly training statistics.
- Billing and trainee reports with chapter, department and learner filters.
- Protected sub-status/reason notes entered through a modal.
- Completion upload tools with CSV import and preview functionality.
- Batched report loading and consistent displayed/exported columns.

## Technical decisions

I traced completion and assessment values to their source records when investigating report mismatches. For chapter reports, loading records in batches helped control request size. Status filtering was moved into DataTables so staff could filter the loaded population.

The chapter reporting work was checked with manual cases covering filters, exports and company access. Those checks applied to the reviewed version and environment.

## Outcome

Staff can inspect training information through searchable tables and export the relevant records. Administrative notes can be entered alongside the report.

## Technologies

PHP, JavaScript, SQL/MySQL, Moodle block plugins and DataTables.

[Back to portfolio](README.md)

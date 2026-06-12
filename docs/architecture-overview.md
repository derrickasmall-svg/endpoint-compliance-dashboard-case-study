# Architecture Overview

## High-Level Workflow

1. Scheduled automation runs from Google Apps Script.
2. Script authenticates to an endpoint management API.
3. Compliance and asset report data is retrieved.
4. Results are parsed, counted, and grouped by compliance category.
5. Summary data is written to Google Sheets.
6. Charts visualize trend data over multiple reporting periods.

## Major Components

- Google Apps Script automation layer
- Endpoint management API integration
- GraphQL query workflow
- Google Sheets reporting workbook
- Dashboard tabs for compliance categories
- Historical trend charts

## Dashboard Categories

- Endpoint security version compliance
- Endpoint security service health
- VPN client version compliance
- Endpoint management agent compliance
- USB device control policy status
- Windows 11 upgrade progress

## Design Notes

The public version of this project is documentation-only. Source code, API logic, tenant details, report identifiers, and authentication values are intentionally excluded.
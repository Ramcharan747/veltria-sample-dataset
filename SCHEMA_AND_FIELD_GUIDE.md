# Veltria Schema and Field Guide

This guide describes the buyer-facing sample files for Veltria company-level firmographic datasets. The product is company-level only and does not include personal emails, personal phone numbers, or individual contact records.

## Sample files

- `veltria_sample_preview_25.csv` — small review sample for quick buyer inspection.
- `veltria_sample_preview_100.csv` — broader sample for schema and coverage review.
- `veltria_schema.csv` — source schema export used for warehouse delivery.

## Fields in sample CSV

| # | Field | Notes |
|---:|---|---|
| 1 | `company_id` | Company-level firmographic attribute. |
| 2 | `company_name` | Company-level firmographic attribute. |
| 3 | `domain` | Company website/domain identifier for matching and enrichment. |
| 4 | `website` | Company website/domain identifier for matching and enrichment. |
| 5 | `country` | Company geography field. |
| 6 | `region` | Company geography field. |
| 7 | `locality` | Company geography field. |
| 8 | `description` | Company-level firmographic attribute. |
| 9 | `industry` | Business classification / segmentation field. |
| 10 | `keywords` | Business classification / segmentation field. |
| 11 | `ownership_type` | Company-level ownership/investor signal where available. |
| 12 | `current_owners` | Company-level ownership/investor signal where available. |
| 13 | `investors` | Company-level ownership/investor signal where available. |
| 14 | `latest_revenue_usd` | Estimated company revenue / revenue metadata. Directional, buyer should validate for critical decisions. |
| 15 | `latest_revenue_estimated` | Estimated company revenue / revenue metadata. Directional, buyer should validate for critical decisions. |
| 16 | `latest_revenue_year` | Estimated company revenue / revenue metadata. Directional, buyer should validate for critical decisions. |
| 17 | `linkedin_employees_count` | Company headcount signal where available. |
| 18 | `employee_size_band` | Company headcount signal where available. |
| 19 | `founded_year` | Company-level firmographic attribute. |
| 20 | `year_total_visits` | Company-level firmographic attribute. |
| 21 | `source_file` | Company-level firmographic attribute. |
| 22 | `source_region` | Company geography field. |

## Compliance positioning

- Company-level firmographics only.
- No personal emails.
- No personal phone numbers.
- No individual contact records.
- Revenue, employee, web-traffic, and ownership fields are estimates/signals and should be validated for high-stakes decisions.

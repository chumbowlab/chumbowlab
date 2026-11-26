# WordPress Operations Playbook
### A practical field guide for maintaining reliable WordPress websites

A growing set of procedures and checklists for WordPress implementation, maintenance, troubleshooting and search visibility. Maintained by **Paul Chumbow · Chumbow Lab**.

[GitHub profile](https://github.com/chumbowlab/chumbowlab) · [Portfolio](https://paulchumbow254.lovable.app) · [Contact](mailto:paulchumbow254@gmail.com?subject=WordPress%20operations%20enquiry)

## Operating principles

1. **Back up before risky changes.** Confirm that a backup exists, is accessible and has a recovery path.
2. **Understand before updating.** Check versions, compatibility notes, hosting constraints and critical site journeys.
3. **Change deliberately.** Use an approved maintenance window and avoid unrelated changes.
4. **Verify the user journey.** Test the forms, checkout, navigation and other business-critical paths after changes.
5. **Document the outcome.** Record what changed, what failed, what was deferred and who owns the next action.

## Maintenance sequence

| Stage | Core checks |
|---|---|
| Prepare | Approval, access, hosting health, disk space, logs, recovery plan |
| Back up | Database and files; verify destination and restoration procedure |
| Review | WordPress core, plugins, themes, PHP compatibility, unsupported components |
| Update | Apply approved changes in a controlled sequence |
| Verify | Homepage, navigation, forms, login, checkout, responsive layout, errors |
| Secure | Admin accounts, MFA, SSL, alerts, backups and access |
| Close | Version record, issue log, owner notification and next review |

Use the [WordPress Maintenance Checklist](../operations-automation-toolkit/templates/wordpress-maintenance-checklist.md) as the repeatable task sheet.

## Troubleshooting workflow

### 1. Define the symptom
Record the exact URL, time observed, affected user journey, browser/device and any visible error. Avoid publishing credentials or personal data.

### 2. Establish scope
Determine whether the issue affects one page, one user role, one device, a plugin feature or the whole site.

### 3. Check recent changes
Review recent plugin/theme/core updates, content edits, DNS or SSL changes, hosting events and deployments.

### 4. Protect the site
Before disabling components, changing configuration or restoring data, confirm authorisation and a tested recovery route. For high-impact sites, use staging where available.

### 5. Isolate and verify
Use logs and controlled tests to narrow down the cause. Make one change at a time and verify the affected journey.

### 6. Record the resolution
Document cause, action, test performed, remaining risk and follow-up owner.

## SEO and discoverability checks

- Confirm important pages return the intended HTTP status.
- Review titles, descriptions, canonical URLs and indexability.
- Check XML sitemap availability and Search Console coverage.
- Review internal links, redirects and broken links.
- Ensure structured data accurately reflects visible page content.
- Optimise image dimensions, format and alternative text.
- Review mobile usability and page performance.
- Avoid guaranteeing rankings or indexing outcomes.

## Incident record

| Field | Notes |
|---|---|
| Site / affected URL | |
| Reported by / time | |
| User impact | |
| Recent changes | |
| Evidence / logs | |
| Suspected cause | |
| Recovery point | |
| Action taken | |
| Verification performed | |
| Follow-up owner / date | |

## Boundaries

This playbook is an operational reference, not a guarantee of security, uptime, SEO results or compliance. Adapt it to the site's hosting, business criticality, contracts and approved policies. Do not perform destructive actions without permission and a recovery plan.

---
**Paul Chumbow** · Chumbow Lab — *Turning Ideas Into Systems That Work.*

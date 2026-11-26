# WordPress Maintenance Checklist

A practical checklist for routine WordPress site care. Adapt it to the site's hosting environment, business criticality and maintenance agreement.

**Site:**  
**Environment:** Production / Staging / Local  
**Review date:**  
**Maintainer:**  
**Backup destination:**  

## Before updates
- [ ] Confirm the site owner has approved the maintenance window.
- [ ] Confirm administrator access is available through an approved secure method.
- [ ] Check hosting, PHP and WordPress health information.
- [ ] Review available disk space and recent error logs.
- [ ] Create a fresh database and files backup.
- [ ] Confirm the backup completed and its destination is accessible.
- [ ] Identify critical forms, checkout, membership or integrations that need regression checks.

## Updates
- [ ] Review WordPress core updates.
- [ ] Review plugin updates and compatibility notes.
- [ ] Review theme and child-theme updates.
- [ ] Check whether any installed component is abandoned or unsupported.
- [ ] Apply updates in the agreed order and record any failures.
- [ ] Avoid changing unrelated settings during routine maintenance.

## Post-update checks
- [ ] Homepage and key landing pages load.
- [ ] Navigation, menus and responsive layouts work.
- [ ] Forms submit and notifications reach the intended destination.
- [ ] Search, login and account flows work where applicable.
- [ ] WooCommerce product, cart and checkout flows work where applicable.
- [ ] Images, fonts and embedded media load.
- [ ] No obvious PHP, JavaScript or console errors remain.
- [ ] HTTPS and redirects behave as expected.
- [ ] SEO metadata, sitemap and indexing settings remain correct.
- [ ] Analytics and consent behaviour remain appropriate.

## Security and operations
- [ ] Review administrator accounts and remove access no longer needed, with owner approval.
- [ ] Confirm MFA is enabled where supported.
- [ ] Check SSL certificate status.
- [ ] Review security alerts and suspicious activity.
- [ ] Confirm backup schedule and retention.
- [ ] Confirm recovery steps are documented.
- [ ] Check uptime and performance indicators.

## Close-out
- [ ] Record completed updates and versions.
- [ ] Record issues, exceptions and deferred work.
- [ ] Notify the site owner of the outcome.
- [ ] Confirm who owns follow-up actions.
- [ ] Schedule the next maintenance review.

## Maintenance record
| Item | Result | Notes / action owner |
|---|---|---|
| Backup | | |
| Core / plugins / themes | | |
| Critical journeys | | |
| Security checks | | |
| Performance / errors | | |
| Follow-up actions | | |

**Important:** A backup is not proven recoverable until restoration has been tested. Do not run destructive updates on a live site without an approved recovery plan.

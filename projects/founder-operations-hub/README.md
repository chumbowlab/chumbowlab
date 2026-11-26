# Founder Operations Hub
### A practical founder-support workspace prototype

A lightweight browser-based workspace by **Paul Chumbow · Chumbow Lab** for keeping priorities, meetings, follow-ups and weekly reviews visible in one place.

<p align="center">
  <strong>DAILY BRIEF</strong> &nbsp;·&nbsp; <strong>TASKS</strong> &nbsp;·&nbsp; <strong>MEETINGS</strong> &nbsp;·&nbsp; <strong>FOLLOW-UPS</strong> &nbsp;·&nbsp; <strong>WEEKLY REVIEW</strong>
</p>

| Project detail | Current state |
|---|---|
| Status | Prototype v1.0 |
| Stack | HTML · CSS · Vanilla JavaScript |
| Runtime | Modern browser |
| Data storage | Browser localStorage |
| Exports | CSV · ICS · JSON backup |
| Authentication / backend | Not implemented |
| Live Google Workspace sync | Not implemented |

## The problem it explores

Founder-support work often spans multiple places: task lists, calendars, meeting notes, email follow-ups and weekly planning. When these are disconnected, priorities and commitments become harder to see.

The Hub explores a simple operating view that brings recurring coordination activities into one workspace.

## What is implemented?

- Daily brief showing open tasks, meetings, follow-ups due and overdue actions.
- Task records with project, owner, due date, priority, status and notes.
- Search, filtering and task completion/reopening.
- Meeting records with attendees, agenda, location and decision notes.
- Calendar-file export in `.ics` format.
- Follow-up records with people, commitments, communication channels and next dates.
- Weekly reviews for progress, blockers, lessons and upcoming priorities.
- CSV export of task records.
- JSON workspace backup and restore.

## How to run it

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Explore the illustrative sample workspace.
4. Add non-sensitive test records and try the export/backup features.

No package installation, build step or external JavaScript library is required.

## How the data moves

See [Architecture and data flow](./ARCHITECTURE.md) for a simple explanation of the browser-only design and file exports.

## Storage, privacy and limitations

The prototype uses browser `localStorage`. Records remain in the browser profile where they were entered; they are not sent to a server, shared with other users or synchronised across devices. Clearing browser data may remove the workspace, so use the JSON backup feature.

This is a single-user prototype, not a production SaaS application. It has no authentication, hosted database, role-based access, encrypted server storage, automatic cloud backup, real-time collaboration or live Google Workspace integration.

- ICS export is a file hand-off, not live two-way Google Calendar sync.
- CSV export is a file hand-off, not a live Google Sheets connection.
- Sample tasks, meetings and follow-ups are illustrative, not actual client records.
- Do not enter passwords, identity documents, sensitive client data, confidential meeting notes or financial credentials.

## Verification before wider use

The project should be checked in a current browser after code changes. Use the [manual test checklist](./TESTING.md) to verify key workflows. Do not treat a checklist as evidence that a test has passed until it has actually been performed.

## Roadmap

Potential next steps, subject to user feedback and technical design:

- Automated tests and accessibility review.
- Secure backend and authenticated user workspaces.
- Google Calendar integration with explicit OAuth consent and conflict handling.
- Optional Google Sheets integration for selected trackers.
- Meeting-to-action conversion and searchable decision log.
- Reminder and escalation workflows.
- Recovery and data-retention design.

These are future possibilities, not implemented features.

## Feedback or collaboration

If you support a founder or small team and have feedback on the workflow, open an issue or [contact Paul Chumbow](mailto:paulchumbow254@gmail.com?subject=Founder%20Operations%20Hub%20feedback).

---

**Paul Chumbow** · Chumbow Lab — *Turning Ideas Into Systems That Work.*

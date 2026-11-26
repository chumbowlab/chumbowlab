# Founder Operations Hub

A practical founder workspace prototype by **Chumbow Lab** for keeping priorities, meetings, follow-ups and weekly reviews visible in one place.

**Status:** Prototype · **Version:** 1.0 · **Stack:** HTML, CSS and vanilla JavaScript

## What does it help organise?

The Founder Operations Hub brings recurring founder-support activities into one lightweight workspace: daily focus, task ownership, meeting preparation, follow-up commitments and weekly reflection.

## What can you do?

- Review a daily brief with open tasks, meetings, follow-ups due and overdue actions.
- Capture tasks with a project, owner, due date, priority, status and notes.
- Search and filter the task list, mark work complete or reopen it.
- Schedule meetings with attendees, agenda, location and decision notes.
- Export recorded meetings as an `.ics` calendar file for import into Google Calendar or another calendar application.
- Track people, commitments, communication channels and next follow-up dates.
- Save a weekly review covering progress, blockers, lessons and next week's priorities.
- Export task records as CSV for use in Google Sheets or other spreadsheet tools.
- Download and restore a JSON workspace backup.

## How do you run it?

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Explore the clearly labelled sample workspace.
4. Add non-sensitive test records and export a backup before using your own information.

No build step, package installation or external JavaScript library is required.

## How does data storage work?

The prototype uses browser `localStorage`. Records remain in the browser profile where they were entered; they are not sent to a server, shared with other users or synchronised across devices. Clearing browser data may remove the workspace, so use the JSON backup feature.

## Is Google Calendar or Google Sheets live-connected?

No. The calendar feature currently exports an `.ics` file that can be imported into Google Calendar. Tasks can be exported as CSV for Google Sheets. These are one-way file hand-offs, not live two-way integrations. A future connected version would require authenticated APIs, appropriate permissions, a secure backend and conflict-handling rules.

## Important limitations

This is a single-user prototype, not a production SaaS application. It has no user authentication, hosted database, role-based access, encrypted server storage, automatic cloud backup, real-time collaboration or live Google Workspace integration. Do not enter passwords, identity documents, sensitive client data, confidential meeting notes, financial credentials or other private information.

The sample tasks, meetings and follow-ups are illustrative examples, not records of actual clients or events.

## Next improvements

- Secure backend, authentication and user-specific workspaces.
- Google Calendar OAuth integration with explicit consent and two-way sync.
- Google Sheets integration for selected trackers.
- Meeting-to-action conversion and a searchable decision log.
- Reminder and escalation workflows.
- Automated tests, accessibility review and feedback from founders using the workflow.

## Want to discuss a founder-support or operations workflow?

**[Contact Chumbow Lab](mailto:paulchumbow254@gmail.com?subject=Founder%20Operations%20Hub%20enquiry).**

---

*Chumbow Lab — Turning Ideas Into Systems That Work.*
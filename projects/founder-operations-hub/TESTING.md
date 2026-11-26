# Founder Operations Hub — Manual Test Checklist

Use this checklist after a code change. Mark a check only after performing it in a current browser. This file is a test plan, not a claim that every test has passed.

**Build / commit tested:**  
**Browser and version:**  
**Date:**  
**Tester:**  

## Startup and persistence
- [ ] Open `index.html` without a build step.
- [ ] Confirm the main interface renders without visible layout breakage.
- [ ] Refresh the page and confirm saved test records persist.
- [ ] Open the application in a separate browser profile and confirm its storage is separate.
- [ ] Clear only test data and confirm the empty state is understandable.

## Tasks
- [ ] Create a task with a title, owner, due date, priority and status.
- [ ] Edit the task and confirm the changes persist after refresh.
- [ ] Search for the task.
- [ ] Apply filters and confirm the results match the selected criteria.
- [ ] Mark the task complete and reopen it.
- [ ] Export tasks as CSV and inspect the downloaded file.

## Meetings and calendar export
- [ ] Create a meeting with a title, date/time and agenda.
- [ ] Add attendees and decision notes.
- [ ] Export an ICS file.
- [ ] Import the ICS file into a test calendar and verify title, date and time.
- [ ] Confirm the documentation does not imply live calendar synchronisation.

## Follow-ups
- [ ] Create a follow-up with a person, commitment and next date.
- [ ] Confirm due and overdue items are represented correctly.
- [ ] Edit and complete a follow-up.
- [ ] Refresh and confirm the updated state persists.

## Weekly review
- [ ] Create a weekly review.
- [ ] Add progress, blockers, lessons and next-week priorities.
- [ ] Save and refresh to verify persistence.

## Backup and restore
- [ ] Export a JSON backup containing test records.
- [ ] Confirm the file is valid JSON.
- [ ] Restore the backup in a test browser profile.
- [ ] Confirm representative tasks, meetings and follow-ups are restored.
- [ ] Test invalid or malformed backup input and confirm the application handles it safely.

## Responsive and accessibility review
- [ ] Check a narrow mobile viewport.
- [ ] Check a desktop viewport.
- [ ] Navigate primary controls using the keyboard.
- [ ] Confirm form controls have understandable labels.
- [ ] Check visible focus indicators.
- [ ] Check text contrast and zoom at 200%.

## Results and follow-up
| Test area | Pass / fail / not tested | Notes / issue |
|---|---|---|
| Startup | | |
| Tasks | | |
| Meetings | | |
| Follow-ups | | |
| Weekly review | | |
| Export / restore | | |
| Responsive / accessibility | | |

**Release decision:** Not assessed / Needs changes / Ready for a limited demo

Do not use this prototype with sensitive records. See the project README and architecture notes for its data-storage boundaries.

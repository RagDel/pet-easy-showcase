# Verification and evidence

**Portfolio updated: 8 October 2026. Application evidence reviewed through: 7 October 2026.** This page summarizes recorded development checks. Updating the showcase does not mean the complete application suite was rerun today.

## What the evidence covers

| Area | Recorded evidence | Boundary |
|---|---|---|
| Backend and persistence | PostgreSQL-backed application tests covering permissions, shared care, conflicting changes, account controls and reminder preferences | Tested behavior under the exercised cases, rather than a production-readiness guarantee |
| Browser | Production builds and focused Greek/English interaction checks across phone and desktop layouts | Controlled fixtures establish interface behavior; separate application journeys establish persistence |
| Native Android | Kotlin tests, build/lint checks and selected emulator journeys | Build success and emulator checks do not replace wider physical-device or screen-reader acceptance |
| Cross-client use | Selected saved records, care updates and reminder preferences exercised between browser and Android | Evidence for those journeys, not every possible account or device state |
| Current presentation | Light/Graphite themes, brand artwork, responsive timeline enlargement, Next actions and optional guidance checked in both languages | The latest browser-only enlarged default does not change native Android's initial layout |
| Showcase images | Current browser interface with fictional demonstration records | Visual examples, separate from backend, notification or native acceptance |

## Recent checks

**Showcase refresh, 8 October.** A fresh browser production build passed. Eight screenshots were captured from that interface using isolated fictional records, with no external requests, record writes or browser-script errors. Each image was visually reviewed. These checks validate the portfolio captures, not the complete application.

**Timeline and next actions.** Recorded checks exercise shared filtering, planned and overdue ordering, dense event groups, birthdays, date focus, completion and returning from an editor. Resize, pan and enlargement checks preserve selected dates and details. Browser coverage includes narrow screens, enlarged text and keyboard interactions.

**Light and Graphite.** Theme checks cover forms, calendars, dialogs, navigation, account pages and the timeline. They include retaining unsaved drafts, remembered appearance, Greek/English text and responsive brand artwork. Android presentation was inspected in the emulator. These checks include contrast and layout measurements but do not establish comprehensive accessibility conformance.

**Introduction and Help.** Checks exercise actual saved-record progression, interrupted-save recovery, Skip, dismissal and replay. View-only shared care receives relevant help. Selected browser and native application journeys confirmed the new guidance and shared records; broader device acceptance remains separate.

**Shared care and calendars.** Recorded tests cover viewing/editing rights, leaving a shared pet, repeated submissions, concurrent changes and document access. Calendar tests include month ends, daylight-saving changes, completion-based recurrence and deliberately saved reminder preferences. Selected email and Android notification interactions were tested during earlier development; that does not establish continuous delivery or an active production notification service.

**Provider discovery.** Checks cover nearest-first results, pagination, place lookup, map refresh, selected businesses and source-preserving duplicate grouping. Some browser checks substitute external map responses, so those results do not prove map-provider availability.

## Remaining acceptance

Managed hosting, public release and broader operational readiness remain ahead. Further acceptance includes physical gestures and camera behavior, screen readers and larger text settings, interrupted journeys, release installation/update flows and notification behavior under restrictive device power settings. The latest presentation pass did not repeat every earlier account or delivery check.

The showcase uses fictional pets, care events and account details. It publishes a summary of evidence, not private logs, user records or operational configuration. The separate [completion-recurrence example](https://github.com/RagDel/completion-recurrence) can be run and tested publicly; its results apply to that sample.

[Product walkthrough](WALKTHROUGH.md) · [Architecture and decisions](ARCHITECTURE.md) · [Agent-assisted development](AGENT_WORKFLOW.md)

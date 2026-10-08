# Pet Easy

**Your pet’s care, simply organised.**

A web and native Android app for keeping pet profiles, care events and shared responsibilities in one place. Greek-first, with an English switch and light or Graphite appearance.

A product and engineering showcase by **Tilemachos Tragakis**, built with Codex-assisted development.

![Pet Easy timeline and next actions with fictional pets](assets/timeline.jpg)

[Visual walkthrough](WALKTHROUGH.md) · [Technical overview](ARCHITECTURE.md) · [Development workflow](AGENT_WORKFLOW.md) · [Verification summary](VERIFICATION.md)

**Updated 8 October 2026.** The app is in active development and selected-user testing. Managed cloud deployment and a broader public release are future milestones. This repository contains curated product previews and a high-level case study; application source remains private.

## What the app brings together

| Capability | Experience |
|---|---|
| **Timeline + next actions** | See selected pets on one date axis, explore grouped events, and follow a list of upcoming or overdue care. Switch between Day, Week, Month and Year, or return to Today. |
| **Personal pet profiles** | Cropped photos, birthdays, age, weight and individual gradient colors make each pet easy to recognize. |
| **Care planning** | Keep notes, documents and provider details with an event. Choose reminder preferences and optional repeats that count from completion. |
| **Shared care** | Invite a caregiver with viewing or editing access. Owners manage sharing, while a shared history helps everyone follow changes. |
| **Nearby services** | Explore vets, groomers, pet shops and related care through map/list discovery, place search and distance-based results. The initial directory covers Greece using attributed open data. |
| **Account and record controls** | Manage profile details, export data, review sessions and use separate pet-profile and account-deletion flows. |

Medical schedules are chosen by the owner from veterinary instructions; the app does not prescribe treatment or universal repeat intervals.

## The latest experience

- **Light and Graphite themes:** coordinated appearance across the website, account screens and Android, with the approved English brand artwork.
- **More room for the timeline:** the browser opens it enlarged, with next actions below and controls to collapse or enlarge it again.
- **Simpler planning controls:** month calendars, smooth time wheels and reminder choices remembered for matching care details.
- **Optional guidance:** a short introduction and contextual Help support the first pet and event without interrupting regular use.
- **Native navigation:** Android returns to the timeline before exit and asks before discarding an edited form.

![Pet Easy shared timeline in the Graphite theme](assets/timeline-dark.jpg)

Screenshots use the current browser interface and fictional demonstration records. Phone-width previews are labelled **responsive web**, separately from the native Android app.

## Built across two clients

**React / TypeScript · Kotlin / Jetpack Compose · Django · PostgreSQL · Docker**

The website and Android app share product behavior and data through one backend. Engineering work covers consistent dates and permissions, reliable handling of repeated actions, shared-care edits, and coordinated appearance across two distinct interfaces.

The [technical overview](ARCHITECTURE.md) explains these responsibilities at a high level. A separate [runnable Python recurrence example](https://github.com/RagDel/completion-recurrence) demonstrates one focused scheduling problem with tests.

## My role and development process

I set the product direction, choose user-facing behavior and technical priorities, and review the experience. I use Codex agents for scoped implementation, research, debugging and verification, supported by reusable project skills and recorded decisions. [How the workflow fits together](AGENT_WORKFLOW.md).

Recorded checks include database-backed behavior, responsive Greek/English browser journeys, Android builds and selected cross-client/device flows. The [verification summary](VERIFICATION.md) distinguishes those checks from screenshots and remaining acceptance work.

Next work includes broader device and accessibility testing, delivery reliability, release distribution and managed hosting. Professional workflows remain exploratory; booking, payments and wider commercial features are future scope.

Published for portfolio review. No open-source reuse license has been selected for these case-study materials, branding or the private application.

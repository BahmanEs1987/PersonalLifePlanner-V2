# Personal Life Planner — UI Revision 2

Local-first PWA for GitHub Pages.

## This revision
- Minimal header icon; no visible app title or lock button.
- Search field uses a magnifier and English `Search`.
- Today summary has no private-note card and no quick-add panel.
- Today summary cards open the relevant details.
- Timeline, Finance transactions, Habits, Events and private-journal list use iOS-style swipe actions: swipe left for Delete, right for Edit.
- Habits use a compact completion checkbox.
- Calendar is a real Jalali/Persian month view with Jalali year/month header, navigation, and date selection.
- Selecting a calendar date opens that date's transactions, completed habits, events and private journal entries, including dates from previous years.

## Data
Daily data stays in IndexedDB on the device. No analytics, tracking or automatic cloud sync is implemented.

## GitHub Pages
Publish the repository from `main` / root. Do not put personal data, passwords, or exported backups in the public repository.

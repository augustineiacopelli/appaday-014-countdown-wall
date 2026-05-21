# 014 · Countdown Wall

A personal countdown tracker built for your phone's home screen. Add named events, assign a color, and see every upcoming date displayed as a big, beautiful day count. Cards sort automatically — soonest first, past events last.

## How to Use

1. Tap **+** to add a countdown
2. Enter the event name, target date, and pick one of 12 colors
3. Tap **Add Countdown** — your card appears instantly
4. Tap **✕** on any card to remove it
5. Data persists across sessions via localStorage

## Add to iPhone / iPad Home Screen

Open the app in Safari → tap the Share icon → **Add to Home Screen**. It launches fullscreen with no browser chrome, just like a native app.

## Technical Notes

- Vanilla HTML, CSS, JavaScript — zero dependencies, zero frameworks
- localStorage for persistence
- Cards auto-sort: upcoming events by soonest first, past events at the bottom
- Safe area insets respected for notched devices
- `apple-mobile-web-app-capable` meta tag enables fullscreen home screen mode
- Day math uses local midnight-to-midnight comparison to avoid timezone drift
- Auto-refreshes every minute so counts stay accurate

## Definition of Complete

- [x] Add countdowns with name, date, and color
- [x] Delete countdowns
- [x] Days remaining displayed in large type
- [x] Cards sort by proximity to today
- [x] Today state and past state handled distinctly
- [x] 12 color options
- [x] Data persists via localStorage
- [x] Mobile-friendly, tap targets sized correctly
- [x] iPhone Add to Home Screen ready (fullscreen, safe area insets)
- [x] Published to GitHub Pages

## Category

**P · Productivity & Life** — AppADay 014

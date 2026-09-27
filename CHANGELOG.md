# Wick's Forms and Things - Changelog

## Unreleased

- The resource bars are coloured by their resource again: blue for
  mana, yellow for energy, red for rage, from the client's own power
  colours where it has them. They were palette tokens, decided when a
  blue mana bar on a green UI looked wrong, and per-class themes ended
  that: on a druid the accent is orange, so the top bar was orange for
  rage and orange for the theme with no way to tell which, and the one
  underneath was a brown smear. The chrome around them is still brand;
  it is the fill that has a job.

## 0.9.0

One version across the suite for the Forever beta. Every addon carried a
number of its own that said nothing about how finished it was, so they are
aligned here and the suite goes to 1.0.0 together at launch.

## 1.0.0 - 2026-09-17 (Forever)

### First release, grown from Wick's Travel Form

- Requires WickCore. Interface 16001.
- Travel Form's smart shapeshift keybind carries over intact. Forever has no
  flying, so the flight clause never fires there.
- Resource bar rebuilt on StatusBars so secret power values display without
  arithmetic.
- Settings move into a WickCore profile; export and import as strings.
- Talents: export, import, save, apply, through Blizzard's own parser.
- Pre-pull checklist and racials in the kit panel (/wft kit).
- Options page under Options, Wick's Mods; minimap launcher.

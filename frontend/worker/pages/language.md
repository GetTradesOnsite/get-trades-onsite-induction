# Worker – Language Selection Screen (MVP)

## Purpose

Allow the worker to choose their preferred language before entering the live induction session.

This ensures:
- All slides are translated correctly
- Content is understandable
- No confusion during the live session

---

## Screen Behaviour

### On Load
- Display available languages
- No session manipulation allowed
- Worker must select one language to continue

---

## UI Elements

### Header
- Title: "Select Your Language"

### Language List
- Large, tappable buttons
- Each language shown in:
  - Native language name
  - English translation in brackets

Example:
- English
- Polski (Polish)
- Română (Romanian)
- Español (Spanish)

### Primary Action
- Button: "Continue"
- Disabled until language selected

---

## Validation

- Worker cannot proceed without selecting a language
- Selection stored for this session only

---

## Accessibility

- Large tap targets
- High contrast
- Mobile-first layout
- Simple wording

---

## MVP Constraints

- No auto-detect
- No profile saving
- No login
- No offline mode

---

## Next Screen

- Live Induction Screen (live.md)

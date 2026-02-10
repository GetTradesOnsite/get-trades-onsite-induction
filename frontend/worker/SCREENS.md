# Worker View – Screens (MVP)

## Overview
The Worker View is a smartphone-first, no-login experience.
Workers join an induction by scanning a QR code, selecting a language, and following live induction content in sync with the presenter.

Design priorities:
- Speed
- Clarity
- Zero friction
- Legal defensibility

No accounts. No passwords. No setup.

---

## Screen 1: QR Join / Session Entry

### Purpose
Allow a worker to instantly join an active induction session.

### Behaviour
- Worker scans a QR code displayed by the presenter
- QR opens a unique session URL in the phone browser
- If session is active → proceed automatically
- If session is inactive → show “Session not active” message

### UI Elements
- App / product name
- Loading indicator
- Status message:
  - “Joining induction session…”

---

## Screen 2: Language Selection

### Purpose
Allow the worker to choose their preferred language before viewing content.

### Behaviour
- Language list displayed immediately after session join
- Languages configurable per site (default: English + top site languages)
- Once selected, language is locked for the session

### UI Elements
- Header: “Select your language”
- Large language buttons (flag + text)
- Confirmation tap selects language and continues

---

## Screen 3: Induction Content View (Live)

### Purpose
Display induction content in sync with the presenter.

### Behaviour
- Content updates live as presenter advances slides
- Worker cannot navigate forward/backward manually
- Text-only content for MVP (no audio)
- Content displayed in the selected language

### UI Elements
- Slide title
- Slide body text
- Progress indicator (e.g. Slide 3 of 10)
- Waiting state if presenter pauses

---

## Screen 4: Understanding Confirmation

### Purpose
Capture worker acknowledgement for compliance.

### Behaviour
- At defined checkpoints or end of induction:
  - Worker is prompted to confirm understanding
- Confirmation required to proceed
- Confirmation recorded per section or final step

### UI Elements
- Prompt text:
  - “I confirm that I understand the information presented”
- Checkbox or button:
  - “I Understand”
- Disabled until user actively confirms

---

## Screen 5: Completion

### Purpose
Confirm successful completion of induction.

### Behaviour
- Displayed after final confirmation
- Session marked as completed
- No further interaction required

### UI Elements
- Success message:
  - “Induction completed successfully”
- Optional reference ID
- Instruction:
  - “You may now close this page”

---

## Compliance Data Captured (MVP)

For each worker session:
- Session ID
- Selected language
- Timestamp (join, confirm, complete)
- Confirmation status
- Device type (basic)
- IP address (for audit)

No personal account or profile data stored.

---

## MVP Constraints
- No login
- No offline mode
- No worker profiles
- Smartphone browsers only
- Focus on speed, clarity, and compliance

---

## Future Enhancements (Not MVP)
- Audio narration
- Offline mode
- Worker profiles
- Induction history
- Digital signature
- Identity verification

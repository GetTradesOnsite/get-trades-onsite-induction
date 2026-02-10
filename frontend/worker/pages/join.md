# Worker Join Screen (QR Entry)

## Purpose
This screen is the entry point for workers joining a live induction session.
It must be extremely simple, fast, and reliable on smartphones.

Workers reach this screen by scanning a QR code displayed by the presenter.

No login.  
No account creation.  
No typing where possible.

---

## URL / Access
- Accessed via QR code
- Example: `/join/{sessionCode}`
- Session code is embedded in the QR URL
- Worker is auto-associated with the live session

---

## Screen Behaviour

### On Load
- Validate session code
- If session is valid and live:
  - Proceed to language selection
- If session is invalid or closed:
  - Show clear error message
  - Example: “This induction session is not active”

---

## UI Elements

### Header
- Company / Site name (if available)
- Title: **“Site Induction”**

### Main Content
- Clear message:
  > “You are joining a live site induction”

- Status indicator:
  - “Session active”
  - Or error state if not active

### Primary Action
- Button:
  **“Continue”**

(If language selection is the next screen, Continue moves forward)

---

## Error States

### Invalid Session
- Message:
  > “This induction session cannot be found”
- Guidance:
  > “Please scan the QR code again or speak to the site supervisor”

### Session Ended
- Message:
  > “This induction session has ended”
- No further action allowed

---

## Accessibility & UX Notes
- Large text
- High contrast
- One primary action only
- Designed for use in noisy, outdoor environments
- Must load quickly on poor connections

---

## MVP Constraints
- No login
- No offline mode
- No personal data entry
- Smartphone-first only

---

## Next Screen
- Language Selection Screen

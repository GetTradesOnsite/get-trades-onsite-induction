# Presenter View – First Draft

## Purpose

The Presenter View is the control interface for supervisors, site managers, or safety officers delivering an induction.

The presenter controls:
- Session start and end
- Slide progression
- Live synchronisation with all connected workers
- Compliance completion

The presenter view is designed for tablet or laptop use.

---

## Access

- Presenter logs in (simple login for MVP)
- Presenter selects site and induction content
- Presenter starts a new induction session
- System generates a unique session ID and QR code

---

## Session Setup

Before workers join, the presenter can:
- Upload or select induction slides (PDF / PPT converted to text)
- Confirm site name and induction version
- Review safety glossary (locked terms)

Once ready:
- Presenter clicks **Start Induction**
- QR code is displayed on screen for workers to scan

---

## Live Induction Control

During the induction:
- Presenter sees the current slide
- Presenter clicks Next / Previous
- All connected workers’ screens update instantly
- Presenter can see:
  - Number of connected workers
  - Languages selected
  - Completion status

Workers cannot advance independently.

---

## Understanding Confirmation

At defined points or at the end:
- Presenter triggers confirmation
- Workers tap **I understand**
- Presenter sees live confirmation count
- Session cannot complete until confirmations are received

---

## Session Completion

- Presenter ends the session
- Session is locked
- Compliance record is finalised
- Presenter can export attendance (CSV / PDF)

---

## Compliance Record

Each session stores:
- Session ID
- Site
- Induction version
- Presenter ID
- Worker count
- Languages used
- Timestamps
- Confirmation status

---

## MVP Constraints

- Simple presenter login
- Manual session control
- No advanced roles
- Focus on audit defensibility

---

## Future Enhancements (Not MVP)

- Presenter announcements
- Quizzes
- Offline mode
- Session replay
- Toolbox talks

# Charlie — Language, themes, layout and input

Target: v105 Pilot. Read the master prerequisites, shared smoke checklist and cleanup rules first. S = SUPERVISED: staff approval required. No experiment activation is assigned.

## CHARLIE-001 — English

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Select English and open every allowed module/help window in your assigned sections.
- **Expected:** Application wording is English apart from user names, Windows text and raw evidence.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## CHARLIE-002 — Swedish

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Repeat the same route in Swedish, including status and confirmation dialogs.
- **Expected:** Application wording is Swedish; record any exact mixed-language string and its location.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## CHARLIE-003 — Built-in themes

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Cycle the built-in dark and light themes and reopen module windows.
- **Expected:** Backgrounds, borders, text and active accents follow the selected palette.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## CHARLIE-004 — System theme

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Select System first in the list; compare with Windows light/dark preference where permitted.
- **Expected:** The chosen system palette is used; report unsupported or inconsistent windows.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## CHARLIE-005 — Custom preview

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Open Custom Theme, change six distinct valid role colours, then Cancel.
- **Expected:** Preview responds but cancelling leaves the saved application theme unchanged.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## CHARLIE-006 — Custom save

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Repeat with valid distinct #RRGGBB values and Save theme, then reopen the saved profile.
- **Expected:** The saved custom theme applies and persists for that profile.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## CHARLIE-007 — Custom validation

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Enter malformed hex or duplicate role colours and read the validation message.
- **Expected:** Invalid/ambiguous role input cannot be saved; valid distinct values re-enable Save.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## CHARLIE-008 — Theme isolation

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Give two profiles different custom palettes and switch/restart.
- **Expected:** Each palette persists independently; built-in theme selection still works.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## CHARLIE-009 — Window sizes

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Resize the main window and module popups to supported minimum and larger sizes.
- **Expected:** Labels and action buttons remain usable; report clipping with size/DPI details.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## CHARLIE-010 — Mouse and trackpad

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Scroll theme list, Available, Profile order, long helpers and audit with both available input types.
- **Expected:** Scrolling advances predictably, scrollbars remain usable and no row disappears during dragging.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## CHARLIE-011 — Helpers and focus

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Toggle Hide helpers, navigate with Tab/Shift+Tab and use Escape in dialogs.
- **Expected:** Helper visibility is consistent, focus is visible and Escape cancels rather than applies.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## CHARLIE-012 — Animation preference

- [ ] **SELF** · Result: NOT RUN
- **Steps:** With confirmed baseline drift toggle Animate alerts off/on; compare reduced-motion mode if permitted.
- **Expected:** Off/reduced motion keeps a steady warning; enabled animation pulses without flashing the whole window.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.


# Bravo — Privacy profiles and run/restore flow

Target: v105 Pilot. Read the master prerequisites, shared smoke checklist and cleanup rules first. S = SUPERVISED: staff approval required. No experiment activation is assigned.

## BRAVO-001 — New profile

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Add several available modules, enter a unique pilot name and Save.
- **Expected:** A saved profile appears with the chosen ordered module list; no action runs.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## BRAVO-002 — Two profiles

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Save a second profile with a different module list, theme and language; switch repeatedly.
- **Expected:** Each saved profile restores its own list/order, theme and language.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## BRAVO-003 — Rename/copy

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Change a saved profile name and Save, then inspect both entries.
- **Expected:** The existing behaviour creates a separate named profile; the original remains.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## BRAVO-004 — Save existing

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Change module order without renaming and Save twice.
- **Expected:** The same profile is updated without additional duplicate entries.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## BRAVO-005 — Delete

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Delete only a disposable pilot profile after reading confirmation.
- **Expected:** That saved selection is removed; Windows settings and recovery records are not changed.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## BRAVO-006 — Drag add

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Drag an available module into Profile order and also into the module area.
- **Expected:** It is inserted once at the indicated location and does not execute.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## BRAVO-007 — Drag remove

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Drag a selected module back to Available; repeat with Remove.
- **Expected:** Only the draft selection changes; saving persists the removal.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## BRAVO-008 — Reorder

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Move modules using drag/drop and Up/Down at the first, middle and final positions.
- **Expected:** Order is stable after saving/reopening; invalid drops do not duplicate modules.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## BRAVO-009 — Unsaved draft

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Edit a profile and attempt another selection or New; exercise both discard choices.
- **Expected:** The prompt protects or discards the draft as selected; no baseline is silently rerecorded.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## BRAVO-010 — Run cancellation

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Open Run profile review and cancel before confirming any action.
- **Expected:** No module activates and no Windows setting changes.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## BRAVO-011 — Allowed sequence

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Use a clean test profile with only authorised low-impact modules; confirm each review.
- **Expected:** Execution follows displayed order; cancelled/failed actions do not imply overall success.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## BRAVO-012 — Experimental preflight

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Put Keep awake before either pilot-locked USB module and choose Run profile.
- **Expected:** The sequence is refused before any module starts; the locked module is identifiable.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.


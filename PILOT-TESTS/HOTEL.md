# Hotel — Offline, keep-awake and recovery audit

Target: v105 Pilot. Read the master prerequisites, shared smoke checklist and cleanup rules first. S = SUPERVISED: staff approval required. No experiment activation is assigned.

## HOTEL-001 — Keep-awake start

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Record normal power preference, start Keep awake, then lock the screen briefly.
- **Expected:** A Windows request is shown while lock remains available; saved power plan is unchanged.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## HOTEL-002 — Keep-awake stop

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Stop Keep awake and close/reopen the app.
- **Expected:** The request is released and is not silently restarted; shutdown is not blocked.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## HOTEL-003 — Audit order

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Add multiple modules and open Device and Recovery Audit/Expand overview.
- **Expected:** Profile ordering, active/outside-profile actions and observations are understandable.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## HOTEL-004 — Audit refresh/close

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Use manual Refresh, toggle Auto update, scroll details and close via its button/Escape.
- **Expected:** Controls work; paused auto-update stops repeated redraw; Close releases the window.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## HOTEL-005 — Offline prerequisites

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** With staff use a local test machine, local login and a tested recovery path; save all work.
- **Expected:** No remote-only test or critical connectivity dependency is used; unsupported conditions can be declined.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## HOTEL-006 — Offline cancel

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Cancel Offline review/elevation and inspect connectivity/state.
- **Expected:** Network/Bluetooth originals are unchanged; no false Offline confirmation appears.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## HOTEL-007 — Offline apply

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Record available adapters/radios; confirm Offline in the authorised environment.
- **Expected:** Reviewed paths disable or are reported partial/unverified; radio invisibility is not promised.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## HOTEL-008 — Offline restore

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Use each offered approved restore entry point on separate clean runs.
- **Expected:** Recorded originals return or remain explicitly pending; pre-disabled devices are preserved.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## HOTEL-009 — Quick-close state

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** During supervised Offline tests close the control popup quickly, reopen and inspect the module.
- **Expected:** Displayed activation/recovery state follows actual evidence; report any stale activation label.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## HOTEL-010 — Recovery continuity

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** After a recorded supervised change switch profiles/reopen before restoring.
- **Expected:** Recovery tracks real changes independently of profile baselines; a profile switch does not discard originals.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## HOTEL-011 — Recovery failure

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Only with staff on a recoverable test machine, inspect denied/missing device outcomes.
- **Expected:** Pending/partial states remain visible; never clear or delete a recovery record to make the warning disappear.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## HOTEL-012 — Crash/restart

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Defer abrupt termination/reboot scenarios to an isolated staff test environment with a recovery plan.
- **Expected:** Mark NOT RUN if unavailable; independently check actual restored networking/input afterwards.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.


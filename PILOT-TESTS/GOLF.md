# Golf — Privacy Insights/DLP and local review

Target: v105 Pilot. Read the master prerequisites, shared smoke checklist and cleanup rules first. S = SUPERVISED: staff approval required. No experiment activation is assigned.

## GOLF-001 — Coverage and simple view

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Open DLP help and the normal process/endpoint view; inspect unknown entries.
- **Expected:** DLP meaning, observed evidence and coverage limits are readable; a connection is not proof of data leakage.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## GOLF-002 — Advanced detail

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Select an observed process and enable advanced detail, then resize/scroll.
- **Expected:** Details remain associated with the selected process; refreshing does not continually reset the view.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## GOLF-003 — Endpoint watch

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Start Watch new endpoints, perform ordinary browsing, pause and resume.
- **Expected:** Start/pause accent reflects state and newly observed endpoints appear with observation times.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## GOLF-004 — Activity watch

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Start Activity and watches and perform ordinary allowed app activity.
- **Expected:** Observations appear within the available scope; short-lived or unobserved processes are not promised complete coverage.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## GOLF-005 — Background continuity

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Close the DLP window while watching, reopen it, then use Restore previous states to stop the watch.
- **Expected:** The app background watch remains consistent with its displayed state; stopping releases it.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## GOLF-006 — Review filter

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Toggle Needs review only before and after new observations and compare with all entries.
- **Expected:** The filter reflects current review state without needing a redundant off/on cycle.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## GOLF-007 — Investigation memory

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Mark a synthetic/disposable observation to investigate; reopen/restart and locate it again.
- **Expected:** The saved investigation mark is recognisable; record its matching limits and scope.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## GOLF-008 — Process/path actions

- [ ] **SELF** · Result: NOT RUN
- **Steps:** For a known disposable process open its file location and process details.
- **Expected:** The path belongs to the selected process; absent/exited/denied cases are reported clearly.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## GOLF-009 — Privacy capabilities

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Inspect microphone/camera/location/keyboard/screen indicators for an observed process.
- **Expected:** Observed use, permission/capability and unknown are distinguished; no hidden capture proof is invented.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## GOLF-010 — Hosts/DNS

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Open hosts contents and DNS observations without editing system files.
- **Expected:** Readable contents/sources are shown; deviations are review clues rather than a poisoning diagnosis.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## GOLF-011 — Masking

- [ ] **SELF** · Result: NOT RUN
- **Steps:** With only synthetic sample strings toggle masking and inspect local details.
- **Expected:** Masking follows the user choice and does not submit any data.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## GOLF-012 — Local content/exit

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Scan only a disposable file containing a fake token-like string; then stop watches and exit the app.
- **Expected:** Pattern findings are explained without claiming transmission; collectors stop on app exit.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.


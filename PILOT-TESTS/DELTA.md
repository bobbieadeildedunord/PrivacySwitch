# Delta — Microphone, camera and device evidence

Target: v105 Pilot. Read the master prerequisites, shared smoke checklist and cleanup rules first. S = SUPERVISED: staff approval required. No experiment activation is assigned.

## DELTA-001 — Initial evidence

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Before activation inspect microphone/camera state and Devices/Audio endpoints in the audit.
- **Expected:** Current observations and unknown/unsupported states are readable and distinguished from recorded actions.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## DELTA-002 — Review/cancel

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Open microphone/camera action review and cancel any UAC or final confirmation.
- **Expected:** No mute/disable is performed and no false Active state appears.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## DELTA-003 — Apply on test devices

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Close calls/recording apps; record original mic/camera state; confirm the action.
- **Expected:** Supported hardware microphone mute and camera disable are reported individually.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## DELTA-004 — Microphone observation

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Use an authorised disposable local recording test while microphone protection is applied.
- **Expected:** Report whether capture is actually silent; driver Enabled is not proof that mute failed.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## DELTA-005 — Camera observation

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Try an authorised local camera preview after camera disable.
- **Expected:** Supported camera is unavailable; record unsupported/access failures honestly.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## DELTA-006 — Recorded markers

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Inspect Devices/drivers and Audio endpoints after an authorised action.
- **Expected:** Markers identify recorded mic/camera changes separately from the observed current state.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## DELTA-007 — Restore originals

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Use Restore previous states and check both devices against the recorded initial state.
- **Expected:** Only recorded changes are restored; original mute/disabled preferences are preserved.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## DELTA-008 — Already restricted

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Start with microphone muted or camera disabled, then review/apply/restore.
- **Expected:** Pre-existing restrictions are preserved rather than blindly enabling everything.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## DELTA-009 — Partial support

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** On available unsupported hardware review the per-device outcomes.
- **Expected:** Partial/unknown is visible; one successful device does not imply all input is blocked.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## DELTA-010 — Hotplug observation

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** With staff approval attach a spare mic/camera during a test and inspect again.
- **Expected:** Coverage of the new device is explicit; never infer all newly attached hardware is protected.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## DELTA-011 — External change

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Use authorised Windows controls to change a tested device state; refresh audit.
- **Expected:** The external observed state is shown separately from the app recovery record.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## DELTA-012 — Recovery continuity

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** After a recorded test change close/reopen and switch profiles before restoring.
- **Expected:** The genuine recovery record remains available across profile selection and is not overwritten.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.


# Alpha — Package, launch and own-app startup

Target: v105 Pilot. Read the master prerequisites, shared smoke checklist and cleanup rules first. S = SUPERVISED: staff approval required. No experiment activation is assigned.

## ALPHA-001 — Unpack

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Extract the entire pilot ZIP to a local folder; compare its manifest and version with the invitation.
- **Expected:** PrivacySwitch.exe and all test documents are present; version is v105 Pilot.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ALPHA-002 — First launch

- [ ] **SELF** · Result: NOT RUN
- **Steps:** On a fresh test account launch the executable; read the agreement before proceeding.
- **Expected:** Personal pilot terms appear before the main window; nothing activates automatically.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ALPHA-003 — Decline

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Decline the first-run agreement or close its window, then relaunch.
- **Expected:** The app exits without modules running and asks again on relaunch.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ALPHA-004 — Accept

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Tick consent and accept; close and relaunch normally.
- **Expected:** Acceptance stays local and normal launch opens the app without running a profile.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ALPHA-005 — Portable path

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Place the app in a folder with spaces and non-ASCII characters; launch it.
- **Expected:** The app opens and identifies its version; report any path errors.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ALPHA-006 — Second instance

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Launch the same build twice in the same account/session.
- **Expected:** The existing main instance is reused; there are no duplicate key hooks or collectors.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ALPHA-007 — Copyright and links

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Read the footer/version and manually open manual, feedback and provider links.
- **Expected:** Copyright identifies Bobbie á Deild; bobbie.se and its contact page open only on explicit action.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ALPHA-008 — Sign-in registration

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** On an authorised account enable Start at sign-in, reading its path review.
- **Expected:** One current-user registration points to this executable; no task, service or elevated startup is created.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ALPHA-009 — Relocation review

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** With sign-in enabled close PrivacySwitch, then open another copy from a different folder; cancel the relocation review first.
- **Expected:** Old registration is retained; opening a new copy alone is not a startup-command change.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ALPHA-010 — Accept relocation

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Approve the reviewed sign-in relocation, then inspect Windows Startup apps and the inventory.
- **Expected:** The same registration is updated to the new path; a tracked baseline detects the command difference.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ALPHA-011 — Remove sign-in

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Disable Start at sign-in and inspect the registration again.
- **Expected:** Only PrivacySwitch own recognised registration is removed; other startup entries are preserved.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ALPHA-012 — Exit and relaunch

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Close all ordinary app windows; relaunch from the pilot folder.
- **Expected:** No modules silently reactivate; pending genuine recovery notices are distinguished from activation.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.


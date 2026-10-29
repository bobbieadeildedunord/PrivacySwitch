# PrivacySwitch v105 Pilot — master test catalogue

This catalogue covers the current released surface, not future implementations. It contains 120 assigned cases in ten sections plus a shared smoke checklist. Nothing here has been marked passed on behalf of students. A test section may be assigned to more than one tester; everyone can also explore other allowed sections.

## Preconditions and reporting

- Use only the supplied v105 Pilot build on your own/authorised local Windows computer. Close older app versions. Record Windows edition/build, account privilege, hardware, language, theme, DPI and input device. Unavailable configurations are NOT RUN, not passed.
- **SELF** cases are ordinary inspection/disposable-file/UI tests. **SUPERVISED** cases require staff approval, saved work, noncritical hardware/connectivity and a recovery route. Do not run them merely because they are listed. Offline, app/service closing, device changes, sign-in changes and abrupt-exit tests are not a first-time self-service classroom assignment.
- Start changing tests from a clean known state. If recovery is already pending, ask staff before continuing. Use disposable profiles/files/passwords and approved Windows-setting changes. Never use the only input device, remote-only access, irreplaceable data or unsaved work as a fixture.
- **Cleanup for every case:** undo only the changes from that case. Use the relevant recorded restore for app module changes; restore Windows preferences/startup toggles manually to your documented originals; stop watchers/Keep awake; disable only your own test sign-in registration; retain unrelated data. Mark unresolved recovery BLOCKED and ask staff. Do not delete journals or take a new baseline to hide a difference.
- Evidence: case ID, tester alias/track, version, environment, exact actions, expected/actual result, result (NOT RUN / PASS / FAIL / BLOCKED / NOT APPLICABLE) and cleanup. Review screenshots for names, paths, tokens and device IDs. Use https://bobbie.se/contact.html; submission is voluntary and manual. Reconnect first after authorised Offline tests.
- Repeat relevant cases in EN/SV, dark/light/system/custom themes, supported small/large windows, keyboard/mouse/trackpad and available DPI/account environments. Use the coverage matrix to record variants rather than assuming untested combinations passed.

## Shared smoke checklist (everyone)

- [ ] Package/version matches; read personal agreement and choose deliberately.
- [ ] Main window opens without running modules; no unexpected elevation.
- [ ] Language/theme selectable; resize/scroll and helpers usable.
- [ ] Create/save/reopen a disposable profile without activation.
- [ ] Open help, manual and pilot/feedback information; no automatic submission.
- [ ] USB Break and device-install restriction visibly pilot locked.
- [ ] Read current device/recovery overview; identify any existing pending record.
- [ ] Perform one assigned SELF case and record actual/expected result.
- [ ] Leave unapproved SUPERVISED cases NOT RUN.
- [ ] Restore only authorised test changes and stop any test watches.
- [ ] Record bugs/confusing wording/free exploration, including language/version.
- [ ] Close the app and record any unresolved state before leaving.


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


# Echo — Copilot and ChatGPT/Codex controls

Target: v105 Pilot. Read the master prerequisites, shared smoke checklist and cleanup rules first. S = SUPERVISED: staff approval required. No experiment activation is assigned.

## ECHO-001 — Help and scope

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Read each AI module help and its option descriptions before any activation.
- **Expected:** One-time app close, key filter, monitoring and policy/service scope are distinguished.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ECHO-002 — Button layout

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Resize the Copilot card at normal and narrow supported sizes.
- **Expected:** Block key + close and its switch retain capped widths and remain inside the card.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ECHO-003 — Disposable app close

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Save work, open only a disposable Copilot session, activate key + close.
- **Expected:** Verified Copilot targets close or an explicit access/identity failure is reported.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ECHO-004 — Physical key

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** After activation press the physical Copilot key once and inspect counters.
- **Expected:** Observed F23/block counters reflect the test; zero events is explicitly inconclusive.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ECHO-005 — Relaunch watch

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Choose Watch + policies, review effects, activate and attempt a disposable Copilot relaunch.
- **Expected:** Supported app relaunch is observed/closed within the stated monitoring interval; scope remains partial.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ECHO-006 — Microsoft 365 scope

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** With authorisation test the dedicated M365 Copilot app alongside saved Word/Excel work.
- **Expected:** Verified Copilot app targets are handled; unrelated Office applications remain usable.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ECHO-007 — Policy review

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Inspect eligible policy requests and cancel if organisational approval is absent.
- **Expected:** Existing policy values are preserved; unsupported editions are skipped with reasons.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ECHO-008 — Copilot restore

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Stop filtering/monitoring and restore recorded policy originals.
- **Expected:** Session hook/watch stops and reviewed originals restore; closed work is not claimed recoverable.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ECHO-009 — ChatGPT/Codex close

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Save all work, use a disposable app session and confirm the close review.
- **Expected:** Verified app/descendant outcomes are reported individually without a blanket success claim.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ECHO-010 — Sandbox service

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Review the sandbox option and cancel elevation, then test with staff only if authorised.
- **Expected:** Cancelled elevation leaves the service unchanged; stop outcomes are explicit when authorised.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ECHO-011 — Identity boundaries

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Read Inspect results and compare any unverified candidates with their listed paths.
- **Expected:** Unknown candidates are not labelled verified or safe; do not manually kill unrelated processes.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## ECHO-012 — Session exit

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Close PrivacySwitch after an authorised filter/watch test; relaunch without Run profile.
- **Expected:** Hooks/watch do not silently reactivate; actual pending policy recovery remains visible.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.


# Foxtrot — Privacy and startup baselines

Target: v105 Pilot. Read the master prerequisites, shared smoke checklist and cleanup rules first. S = SUPERVISED: staff approval required. No experiment activation is assigned.

## FOXTROT-001 — Privacy readout

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Open Windows privacy baseline in a saved pilot profile and inspect every grouped category.
- **Expected:** Stored preferences/policies, unknowns and actual-enforcement limits are clear.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## FOXTROT-002 — Settings links

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Open each category settings link and the diagnostic-deletion guide without changing settings.
- **Expected:** Links reach the appropriate Windows page; deletion completion is not claimed by PrivacySwitch.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## FOXTROT-003 — Privacy save/change

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Save a named test baseline; change one approved Windows preference; choose Refresh.
- **Expected:** Changed stored evidence is marked; Refresh compares without accepting it as the baseline.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## FOXTROT-004 — Privacy match

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Return that preference manually to its original Windows setting; Refresh.
- **Expected:** Observed differences clear when readable stored values match; effective-setting limits remain.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## FOXTROT-005 — Named history

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Save two named disposable baselines and select each from history; exercise Use for startup reviews.
- **Expected:** Selected comparison and the baseline chosen for startup remain understandable; cancel does not change selection.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## FOXTROT-006 — Startup inventory

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Open Startup inventory and inspect enabled, disabled and unknown examples where available.
- **Expected:** Counts match listed recognised states; unsupported approval formats remain unverified.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## FOXTROT-007 — Startup selection

- [ ] **SELF** · Result: NOT RUN
- **Steps:** In a test profile review default selection, Select all, Clear selection and Track selected.
- **Expected:** Zero-entry new saves are refused; star marks selection for the next save, not enabled status.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## FOXTROT-008 — Startup save/change

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Save a selected approved startup item; toggle its startup permission in Windows without resaving.
- **Expected:** Automatic comparison detects the saved-evidence difference; the module/button warning responds.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## FOXTROT-009 — Manual/auto summary

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Keep inventory open during that change; compare automatic updates with manual Refresh.
- **Expected:** Counts, check time and rows agree with completed observations; the short arrow explanation stays under the title.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## FOXTROT-010 — Pause/resume

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Pause tracking, change the approved item, then resume without saving a new baseline.
- **Expected:** The original comparison point is retained and changes made while paused are detected after resumption.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## FOXTROT-011 — Profile/legacy import

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Use two disposable saved profiles; import previous shared baselines only when authorised, then save different baselines.
- **Expected:** Profile baselines are independent; import does not overwrite existing profile baselines or shared originals.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## FOXTROT-012 — Restart persistence

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Restore the test startup item manually, close/reopen the app and revisit the same profile.
- **Expected:** Baseline and monitoring choice persist; no automatic Windows restoration or startup prevention is claimed.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.


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


# India — Encrypted files with 7-Zip

Target: v105 Pilot. Read the master prerequisites, shared smoke checklist and cleanup rules first. S = SUPERVISED: staff approval required. No experiment activation is assigned.

## INDIA-001 — Engine absent

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Open the tool on a test machine without a detected supported 7-Zip engine.
- **Expected:** A clear prerequisite message appears; no engine is silently downloaded.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## INDIA-002 — Engine discovery

- [ ] **SELF** · Result: NOT RUN
- **Steps:** With an approved installed supported engine open the tool.
- **Expected:** The selected engine is identified and availability is distinguished from operation success.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## INDIA-003 — Encrypt copy

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Use a tiny disposable text-file copy and a disposable password; create an encrypted archive.
- **Expected:** Output is created and original input is preserved.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## INDIA-004 — Unlock copy

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Unlock that archive to a new empty test folder.
- **Expected:** Recovered file content matches the original fixture.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## INDIA-005 — Wrong password

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Attempt unlock using an intentionally wrong disposable password.
- **Expected:** Failure is explicit and output is not mislabelled successful.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## INDIA-006 — Cancel before start

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Select disposable inputs, then cancel the review before starting.
- **Expected:** No job runs or archive output is created.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## INDIA-007 — Cancel running job

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Use a sufficiently large disposable fixture and cancel an active job.
- **Expected:** Cancellation is reported; incomplete output handling is clear and originals remain.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## INDIA-008 — Name/path coverage

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Repeat with spaces, Unicode names and a nested local fixture folder.
- **Expected:** Supported paths work or produce a clear actionable error.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## INDIA-009 — Output collision

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Choose an already existing disposable output path and decline any replacement.
- **Expected:** Existing data is preserved unless explicitly reviewed and authorised.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## INDIA-010 — Bad input

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Try an absent input and an unreadable test location where safely available.
- **Expected:** Validation/access failures are explicit and do not claim completed encryption.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## INDIA-011 — Empty/multiple files

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Test an empty disposable file and multiple fixtures, then unlock to separate folders.
- **Expected:** Supported cases round-trip correctly; unsupported cases are explained.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## INDIA-012 — Operation boundaries

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Close/reopen the tool and inspect profile switching during completed idle jobs.
- **Expected:** No operation silently reruns; do not put real passwords or archive contents in feedback.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.


# Juliet — Release gates, boundaries and final coverage

Target: v105 Pilot. Read the master prerequisites, shared smoke checklist and cleanup rules first. S = SUPERVISED: staff approval required. No experiment activation is assigned.

## JULIET-001 — USB card lock

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Add USB Break to a test profile and inspect its card and help.
- **Expected:** It says experimental/pilot locked; activation is disabled and help remains available.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## JULIET-002 — Install-policy card lock

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Repeat for Device installation restriction.
- **Expected:** Activation is disabled; existing recovery remains distinct from activation.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## JULIET-003 — Profile lock preflight

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Run a profile with a harmless module before each locked experimental module.
- **Expected:** The entire sequence is refused before earlier actions run.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## JULIET-004 — Direct gate

- [ ] **SUPERVISED** · Result: NOT RUN
- **Steps:** Staff only: execute this verified pilot binary with --usb-break and --usb-install-apply separately.
- **Expected:** Each exits with code 5 before UAC/device changes; never run an older unrestricted build for this test.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## JULIET-005 — Recovery access

- [ ] **SELF** · Result: NOT RUN
- **Steps:** With no pending record inspect recovery help; staff may use an existing legitimate recorded recovery only.
- **Expected:** Recovery commands are not blocked by the pilot gate; do not manufacture a record or disable devices to test it.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## JULIET-006 — Baseline scope

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Read PROFILE-SETTINGS-MATRIX and compare what the UI promises with actual saved profile contents.
- **Expected:** Module membership and baseline/theme bindings are distinguished from separate Power User/DLP/session state.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## JULIET-007 — Future modules

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Inspect roadmap/help for active viewer, Utilities overlay, anti-bloatware, Update inspector and ad filtering.
- **Expected:** Unreleased features are labelled planned and receive NOT APPLICABLE rather than execution assignments.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## JULIET-008 — Donation/feedback

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Read school-pilot info; open feedback and optionally PayPal, then close PayPal without paying.
- **Expected:** Donation is optional 0–10 SEK; PayPal opens only on click, currency/amount require review, and no payment or report is automatic.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## JULIET-009 — Agreement access

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Reopen the personal pilot terms from the pilot window and read distribution instructions.
- **Expected:** Terms identify personal invited testing and permission before redistribution.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## JULIET-010 — Locality review

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Inspect optional links, local state descriptions and report preview before sharing.
- **Expected:** External navigation requires a user action; this checklist is not proof of absence of all network activity.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## JULIET-011 — Matrix gaps

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Review OS/edition/admin/DPI/input/language/theme rows in the coverage matrix.
- **Expected:** Unavailable environments remain NOT RUN; one laptop is not treated as coverage of every Windows machine.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.

## JULIET-012 — Free exploration and closeout

- [ ] **SELF** · Result: NOT RUN
- **Steps:** Explore allowed features outside your assignment; report exact steps/version and restore only your test changes.
- **Expected:** Every extra finding has an ID; cleanup is recorded and unresolved recovery goes to staff before ending.
- **Cleanup:** apply the master per-case cleanup rules; record actual restore result or BLOCKED.


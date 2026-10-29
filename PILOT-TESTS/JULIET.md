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


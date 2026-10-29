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


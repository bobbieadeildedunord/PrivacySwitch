# Antivirus information

## Historical v103 result

The creator supplied a VirusTotal engine list for SHA-256:

`74d0001f47af3d22a5ec4930bfa6a063781a05027240b791210411afc510faff`

This hash was checked locally against the v103 executable and the executable inside its school pilot ZIP. It is **not a scan result for v105**.

| Result in the supplied list | Engines |
| --- | ---: |
| Detection | 6 |
| Undetected | 65 |
| Unable to process this file type | 3 |
| Total listed | 74 |

The six detections were Bkav Pro, Elastic, Malwarebytes, MaxSecure, McAfee Scanner and SecureAge. The three engines unable to process the file type were Avast-Mobile, BitDefenderFalx and Symantec Mobile Insight; these are not clean verdicts.

The creator also reports no local antivirus alerts during testing on a Windows 11 school computer and Windows Server 2025. These observations and the majority of undetected results provide context, but do not establish that every detection is incorrect. The detections are considered suspected false positives by the creator; vendor confirmation is pending. The supplied report was not independently refreshed live.

[Historical report](https://www.virustotal.com/gui/file/74d0001f47af3d22a5ec4930bfa6a063781a05027240b791210411afc510faff)

## Current draft

v105 is unsigned and has no new VirusTotal result recorded here. Synthetic functional tests do not certify the absence of malware or vulnerabilities. Each published package must have its own version and checksum. Do not use an older report as verification of a different executable.

Report an alert with the exact version, checksum, antivirus product and detection name. Keep normal antivirus protections enabled.

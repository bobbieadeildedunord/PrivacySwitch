# Known issues and coverage

- Windows privacy monitoring covers a fixed set of stored preferences and policy observations. Improve Start and search results is not covered by the existing baseline. Modern Windows offers/settings mappings require further validation.
- Startup inventory distinguishes stored launch commands from observed approval evidence. Unknown approval formats and actual successful startup remain unverified. Only tracked entries participate in the saved startup comparison.
- On a Server 2025 RDP pilot, no audio endpoints were listed despite playback working. The current microphone inventory reads capture endpoints; playback inventory and RDP microphone configuration require investigation.
- An 80s Retro rendering issue was reported through RDP but could not be confirmed from the screenshot. Low priority pending reproduction.
- Privacy Insights does not inspect the contents of encrypted network traffic. A process connection alone does not prove a data leak. Export of the full retained activity/watch inventory is planned, not implemented.
- Copilot/browser/Office coverage is partial and varies by version, supported policy and user/session. App closing and key blocking do not prove all telemetry has stopped.
- USB experiments are pilot locked. Offline can disconnect remote access and Bluetooth input; review its recovery guidance before use.
- Profile storage does not include every runtime choice. See PROFILE-SETTINGS-MATRIX.md. Recovery records deliberately remain available across profile changes.
- v105 remote view has synthetic test coverage; real-device, accessibility and layout validation remain ongoing. The wider Windows 10/11 VM matrix has not been completed.

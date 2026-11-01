# Rookline Drive Releases

Public Windows installer releases for **Rookline Drive** — live telemetry and a VR HUD for Le Mans Ultimate.

This repository hosts installer downloads only. Product source code, ZIP packages and development artifacts remain private.

## Download

[Download Drive 0.6.33](https://github.com/convexrook2/Rookline-Drive-Releases/releases/download/v0.6.33/Rookline-Drive-Setup.exe)

**0.6.33 is a VR test prerelease.** It adds offline HUD layout setup, selectable
player markers, brief information toasts, current track condition, dashboard Exit
Drive and optional minimize to the notification area. It also includes the
Follow/head-up map and rain-artwork corrections. Interpolation remains off.

Headset acceptance of the new Exit/tray controls, bindings/markers, exact local-yellow
timing/coverage and sustained Follow-map smoothness remains open. Current-user installation and installed startup were verified with saved layout
and settings preserved; upgrade and headset acceptance remain open. On-screen Save placement remains the
accepted editing workflow; physical controller A saving is a secondary known issue.

Choose **Settings > About > Application > Minimize to notification area** and
**Save preferences** to enable tray minimization. Start minimized is separate.

See [Releases](https://github.com/convexrook2/Rookline-Drive-Releases/releases) for
the candidate notes, checksum and earlier versions. Existing0.6.32 test and0.6.27
stable releases are retained; the failed0.6.30 installer should not be used.

Windows x64. The installer includes the .NET runtime; WebView2 and SteamVR are required for VR mode. The installer is unsigned.

# Rookline Drive Releases

Public Windows installer releases for **Rookline Drive** — live telemetry and a VR HUD for Le Mans Ultimate.

This repository hosts installer downloads only. Product source code, ZIP packages and development artifacts remain private.

## Download

[Download Drive 0.6.32](https://github.com/convexrook2/Rookline-Drive-Releases/releases/download/v0.6.32/Rookline-Drive-Setup.exe)

**0.6.32 keeps accepted HUD panels visible across head movement, view cycling and Garage returns.** The exact published installer passed an actual upgrade from 0.6.31 before publication, preserving saved HUD layouts, settings and startup preferences. It also retains the installer-startup correction introduced in 0.6.31; the failed 0.6.30 installer should not be used.

This is a **VR test pre-release** with eight configurable HUD views, Previous/Next cycling and locked first-use panel defaults. In-headset acceptance of this visibility correction remains pending. The separate whole-cockpit tracking jump and cancellation exception are not claimed fixed. Choose cycle membership and panel contents in **Settings → HUD views**, then click **Save views**. Windows/minimized startup and verified manual updates remain available.

See [Releases](https://github.com/convexrook2/Rookline-Drive-Releases/releases) for evidence and earlier versions.

Windows x64. The installer includes the .NET runtime; WebView2 and SteamVR are required for VR mode. The installer is unsigned.

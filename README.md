# OpenRTC Proxy desktop downloads

Get Proxy at https://proxy.openrtc.app/ or select an installer from [Releases](https://github.com/bluestarburst/proxy-releases/releases).

Proxy shares groups of developer services and LAN game servers through OpenRTC tickets from a compact tray menu. Install the app on the host and guest computers. Choose detected services or custom IP addresses/ports, create a group, and share its ticket.

## Install

- **macOS:** choose Apple Silicon or Intel DMG, then drag Proxy to Applications. macOS releases require Developer ID signing and notarization.
- **Windows:** use the x64 setup executable or MSI. These installers are not Authenticode signed; Windows may show a SmartScreen prompt.
- **Linux:** use the x64 AppImage or Debian/Ubuntu package. Automatic process discovery requires `lsof`.

Proxy currently asks for your Proxy-owned OpenRTC public API key in Settings. Configure it on each computer before sharing or joining a ticket. App groups and settings persist locally; starting a saved group after restart creates a new ticket.

This public repository contains distribution artifacts and release notes. Application source is maintained in a separate private repository. The signed `latest.json` catalog is published with each complete release; the current app uses installer downloads and does not run an automatic updater.

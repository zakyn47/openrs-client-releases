# openrs client downloads

Get the latest version from **Releases** (right side of this page).

## Windows
- `openrs-setup-<version>.exe` — installer (Start menu shortcut, uninstaller).
- `openrs-<version>-windows.zip` — portable; unzip and run `openrs/openrs.exe`.

Windows SmartScreen may say "Windows protected your PC" because the installer is not code-signed. Click **More info → Run anyway**.

## Linux (x86_64)
- `openrs-<version>-x86_64.AppImage`: `chmod +x openrs-*.AppImage && ./openrs-*.AppImage`
- Without FUSE: `./openrs-*.AppImage --appimage-extract-and-run`

## Verify the download
`sha256sum -c SHA256SUMS --ignore-missing` (Linux) or `Get-FileHash <file>` (PowerShell) and compare with `SHA256SUMS`.

Your settings live in `~/.openrs` (Windows: `%USERPROFILE%\.openrs`); a normal RuneLite install is not touched.

openrs is based on RuneLite (BSD-2-Clause) and bundles 117 HD (BSD-2-Clause); see THIRD_PARTY_NOTICES in each release.

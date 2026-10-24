# Danho

Your study space for past papers, a personal notebook and virtual laboratories.

## Install

Download the installer for your computer from the [official releases](https://github.com/giftman0/danho/releases). Version 1.0.0 is being prepared. A download is available only when its release assets have been published and verified.

| Computer                 | Installer                       |
| ------------------------ | ------------------------------- |
| Windows 64-bit           | `Danho-VERSION-windows-x64.exe` |
| Mac with Apple Silicon   | `Danho-VERSION-mac-arm64.dmg`   |
| Mac with Intel processor | `Danho-VERSION-mac-x64.dmg`     |

On Windows, open the installer and follow its steps. The first Windows release is unsigned, so Windows may display an unknown-publisher warning. Continue only after confirming the file came from this official repository and its checksum matches the release.

To check your Mac, open the Apple menu and choose About This Mac. A Chip field identifies Apple Silicon; an Intel Processor field identifies an Intel Mac.

On macOS, open the matching DMG and drag Danho into Applications. Release builds require Developer ID signing and Apple notarization. If macOS reports a damaged or unverified application, download the official matching installer again and report the problem. Do not disable Gatekeeper.

Start Danho and follow the account activation steps. Enter your email address in the browser, then enter the email code to approve this computer. The first account approval starts a 45-day trial. The trial belongs to the account, and reinstalling Danho does not restart or extend it. Previously issued trial expiry dates remain unchanged. Your learning content and access status are managed separately from application updates.

## Updates and saved work

Danho checks for newer application versions when it starts. Open Settings, then the account and updates section, to check manually, read release notes and choose Download and install. Downloads are verified with Danho's updater signing key. Danho saves open paper, practical and notebook work before installation and restart. If saving fails, the update stops and your work stays open.

## Verify a download

Download `SHA256SUMS` alongside the installer. Compare the matching filename and SHA256 value before opening it. On Windows, use `Get-FileHash PATH -Algorithm SHA256` in PowerShell. On macOS, use `shasum -a 256 PATH` in Terminal. Replace PATH with the downloaded file's path.

Each complete release contains the three installers, both macOS updater archives, updater signatures, `latest.json`, `downloads.json` and `SHA256SUMS`. Application source and build credentials are private. For a failed installation or update, include the Danho version, operating system, processor type and exact error text in a report. Do not include account codes, credentials or student work.

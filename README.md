# Workify — downloads

Field service software for HVAC and electrical contractors: customers, scheduling, jobs, estimates
and invoices. Runs entirely on your own computer — no account, no internet needed, nothing uploaded.

## Get the latest version

**[Download the newest Workify release →](../../releases/latest)**

| Your computer | File to download |
| --- | --- |
| Mac with Apple Silicon (M1 / M2 / M3 / M4) | `Workify-<version>-arm64.dmg` |
| Windows 10 or 11, 64-bit | `Workify Setup <version>.exe` |

Intel Mac? Ask for an Intel build — the default Mac build is Apple Silicon only.

## Install

**Mac**

1. Open the `.dmg`, drag **Workify** into Applications.
2. Do not double-click the first time: **right-click Workify → Open → Open**.
   macOS warns about unidentified developers; the build is not notarised yet.
3. If macOS claims the app is damaged, run once in Terminal:
   `xattr -dr com.apple.quarantine /Applications/Workify.app`

**Windows**

1. Run the `.exe`.
2. SmartScreen says "Windows protected your PC" → **More info → Run anyway**.
3. Installs per-user: no administrator password, you choose the folder.

## Activate

Every install starts with a **14-day trial** — no key required.

When you have a key: open Workify → **Settings → License** → paste the key → **Activate this
computer**. If the trial already expired, the app opens on the activation screen instead.

Keys are signed and work offline forever. A key binds to the first computer that activates it.

## Your data

- Mac: `~/Library/Application Support/Workify/workify.db`
- Windows: `%APPDATA%\Workify\workify.db`

One database file per computer. Copy it to back up. Nothing is ever uploaded.

## Support

Reply to the email that came with your license key.

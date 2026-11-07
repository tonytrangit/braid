<p align="center"><img src="brand/braid-icon.svg" width="160" alt="Braid"></p>

# Braid

**Safe backups for photographers.** Braid copies a Capture One session (or any folder) to every backup drive and proves each copy is complete. You see every change before anything is written, and replaced or removed files go to an Archive inside a `_Braid` folder, so nothing is lost by accident.

- **One-Way Backup** to as many drives as you like
- **Backup Check:** a full plan of what will be copied, updated and removed on every drive, before you start
- **Checksums:** every file is verified with xxHash64, with ASC MHL records on each drive and a PDF/CSV transfer report
- **Verify Drive:** re-reads a backup and proves it is intact
- **Honest results:** a drive is only reported identical when it really matches the master; unplugged drives catch up next time
- **Capture One aware:** open sessions are backed up as consistent snapshots, and sessions can be renamed safely

Multi-Way Sync is paused in this version while it gets another full review. If you already have a Multi-Way task, it's kept exactly as it is and shown as paused; a later version will bring it back.

## Download

Braid is in beta. **[Download the Braid installer (0.0.9)](https://github.com/tonytrangit/braid/raw/main/downloads/Braid-0.0.9.dmg)**, or find every version on [Releases](https://github.com/tonytrangit/braid/releases).

Braid isn't on the App Store yet, so macOS asks you to allow it **twice**: once for the installer and once for the app.

1. **Allow the installer.** Double-click the downloaded `Braid-0.0.9.dmg`. If macOS says it can't be opened, open **System Settings → Privacy & Security**, scroll down to the message about Braid, and click **Open Anyway**. Then open the installer again.
2. Drag **Braid** onto **Applications**.
3. **Allow the app.** Open Braid from Applications. If macOS says it can't be opened (or that it's "damaged"), go back to **System Settings → Privacy & Security** and click **Open Anyway** again, this time for the app. Then open Braid again.

You only need to do this once. After that, Braid updates itself.

Requires macOS 14 Sonoma or later.

---

Made by [Tony Tran](https://tonytran.co.uk).

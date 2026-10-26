<p align="center"><img src="brand/braid-icon.svg" width="160" alt="Braid"></p>

# Braid

**Multi-Way Sync for photographers.** Braid keeps a Capture One session (or any folder) and every backup drive identical, whichever one you worked on last. You see every change before anything is written, and replaced files go to an Archive inside a `_Braid` folder, so nothing is lost by accident.

- **Multi-Way Sync** and **One-Way Backup**
- **Sync Check:** a full plan of what will be copied, updated and removed on every drive, before you start
- **Checksums:** every file is verified with xxHash64, with ASC MHL records on each drive and a PDF/CSV transfer report
- **Verify Drive:** re-reads a backup and proves it is intact
- **Built for shooting days:** files that arrive mid-sync are picked up, and unplugged drives catch up next time
- **Capture One aware:** open, rename and back up sessions safely

## Download

Braid is in beta. **[Download the Braid installer (0.0.5)](https://github.com/tonytrangit/braid/raw/main/downloads/Braid-0.0.5.dmg)**, or find every version on [Releases](https://github.com/tonytrangit/braid/releases).

1. Open the installer and drag **Braid** onto **Applications**.
2. Double-click **Finish Installing**. Braid isn't on the App Store yet, so macOS may otherwise say it's "damaged". It isn't: this tells macOS you trust it, then opens Braid.
3. If Finish Installing is blocked too, open **System Settings → Privacy & Security** and click **Open Anyway**, or paste this into Terminal:

   ```
   xattr -dr com.apple.quarantine /Applications/Braid.app
   ```

You only need to do this once. After that, Braid updates itself.

Requires macOS 14 Sonoma or later.

---

Made by [Tony Tran](https://tonytran.co.uk).

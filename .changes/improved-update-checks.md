---
"tauri": patch
---

Updater, with `dialog: true`, doesn't check for updates if it cannot install them (currently applies to linux/deb). In dev mode, update checks are turned on by default, but installation fails without touching any files.

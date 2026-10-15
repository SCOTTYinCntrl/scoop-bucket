# Scottimizer Scoop bucket

[Scoop](https://scoop.sh) manifests for **Scottimizer** — a free, open-source
Windows gaming, privacy and security tuner.

- **App source:** https://github.com/SCOTTYinCntrl/Scottimizer
- **Website:** https://scottyincntrl.github.io/Scottimizer/
- **License:** MIT (free; donations optional)

## Install

```powershell
scoop bucket add scottimizer https://github.com/SCOTTYinCntrl/scoop-bucket
scoop install scottimizer/scottimizer
```

## Update

```powershell
scoop update scottimizer
```

## Notes

- Scottimizer needs **Administrator** rights for most tweaks and will ask for
  elevation when it launches. Scoop installs the app; it does not run it.
- The `.exe` is unsigned, so SmartScreen may warn on first launch
  (*More info → Run anyway*). Running `Scottimizer.bat` from the install folder
  avoids the prompt.
- Manifests are refreshed automatically by the **Excavator** workflow
  (`.github/workflows/excavator.yml`), which reads the `checkver`/`autoupdate`
  block in `bucket/scottimizer.json`.

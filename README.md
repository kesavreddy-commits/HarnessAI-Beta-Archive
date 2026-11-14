# HarnessAI Beta archive

Each zip here is encrypted with AES-256, including the names of the files inside it. The
password is provided separately.

| Archive | What it holds | SHA-256 |
| --- | --- | --- |
| `HarnessAI-Beta-source-2f38f3b.zip` | the source release, as `source.zip` | `2e3e755211a81738ba096bb312ba6f67624c8707f259043eef6884d906136245` |
| `HarnessAI-Beta-windows-x86_64-202611140317.zip` | the compiled build for Windows (x86_64), as `windows-x86_64.zip` | `fa5ab27d184934543dc2370a4d9ce3552446935de64281e361f1275c00d678b5` |

## Opening one

Each opens in two steps: the password unlocks the zip inside, which then opens like any zip.

- **Windows:** open it with 7-Zip, then open the zip inside normally.
- **macOS:** in Terminal, run `tar -xf <archive>.zip`, enter the password when it asks, then
  double-click the zip it leaves. Keka or The Unarchiver also work.
- **Linux:** `7z x <archive>.zip` (p7zip) or `bsdtar -xf`, then `unzip` the zip inside.

Some built-in unzip tools, including Windows Explorer's, can't open AES-encrypted zips. Use one
of the tools above.

The Windows build unzips to `app\`, `README.md` and `LICENSE`. Put that folder at
`%USERPROFILE%\HarnessAI-Beta` and follow its README from step 3.

## License

All rights reserved. This repository grants no rights. Use of the software is governed
by the LICENSE file inside each archive.

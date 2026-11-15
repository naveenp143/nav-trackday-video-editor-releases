# NAV Track Day Video Editor

Turns an Insta360 track-day recording and its RaceBox data into a finished video on your own
computer: lap times, speed, lean and a track map on the picture, and a coach who reviews every turn
against your own best run. Nothing is uploaded and there is no account.

## Download

Get the latest version from **[Releases](../../releases/latest)**:
`NAV-Track-Day-Video-Editor-Windows-Locked.zip` (Windows 10 or 11, 64-bit, about 350 MB).

- [Instruction manual (PDF, 2 pages)](NAV%20Track%20Day%20Video%20Editor%20-%20Instruction%20Manual.pdf)
- [Release notes](CHANGELOG.md)

## Install on Windows

1. Extract the whole zip: right-click it > Extract All.
2. In the extracted folder, double-click `Install on Windows.cmd`.
   If Windows says "Windows protected your PC": More info > Run anyway.
3. Open it from the Start menu or the Desktop: **NAV Track Day Video Editor**.

Nothing else has to be installed and no internet is needed: the package carries its own Python and
ffmpeg. It installs for you only, with no administrator rights (about 850 MB). To remove it:
Settings > Apps > Installed apps > NAV Track Day Video Editor > Uninstall.

An NVIDIA graphics card makes the video fastest. Any other PC works too; it just takes longer.

## Updating

Download the newest zip from Releases and run `Install on Windows.cmd` again. Your videos and saved
settings are left alone.

## What to give it

- The Insta360 recording (`VID_....insv`). Keep the `LRV_....lrv` file the camera wrote beside it.
- A RaceBox export (`.csv` or `.vbo`) for the session, in the same folder as the recording. Without
  one the edit still works; speed is then an estimate.

## If something goes wrong

The notes at the bottom of the window say what the program was doing when it stopped. Copy them and
open an [issue](../../issues) here.

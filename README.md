# SoundBrowse — Downloads

Release downloads for **SoundBrowse**, a minimal Ableton-style sound file
browser for macOS. This repo hosts builds only; the source is private.

## Install

**Download via Terminal** (avoids macOS Gatekeeper quarantine):

```sh
curl -L -o ~/Downloads/SoundBrowse-mac.zip https://github.com/soundbrowse/soundbrowse-releases/releases/latest/download/SoundBrowse-mac.zip
```

Then double-click the zip in your Downloads folder and drag **SoundBrowse** to
Applications. Updating? Replace the old app — your places and settings are kept.

Note: the app is unsigned. If you download it with a web browser instead of the
command above, macOS will refuse to open it ("damaged and can't be opened")
until you clear the quarantine flag with `xattr -cr /path/to/SoundBrowse.app`.

Requires an Apple Silicon (M1 or later) Mac.
Also on the web: https://soundbrowse.app

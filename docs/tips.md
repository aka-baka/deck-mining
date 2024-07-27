# Tips
## Misc tips
- Adjust zoom factor of Yomitan and your texthook page. I like to use between 125 - 150%.
- There are times (especially when setting up) where it'll be much easier if you have a keyboard and mouse. A few options:
  - Use bluetooth kb+m
  - Get a usb-c dock and connect your kb+m
  - Remote desktop (either through Steam remote play or other software)
- window mode for games are more stable than fullscreen since we have to alt+tab often. Use frameless window option if the game supports it.
- back buttons are good candidates to map for our window switching, OCR, and mining actions
- map single click and moving the cursor to separate trackpads for easier click and drag (if you're attempting OCR where you have to drag a region)
- you can map double click by using extra command of type "start press" and put a delay
- disable mouse in the game if supported to avoid camera moving around or accidentally advancing text when grabbing a screenshot for OCR. Eg. Senpatcher for Sen no Kiseki can disable mouse in-game

## Transferring files
Options:
- SFTP (eg, WinSCP or FileZilla on Windows) - recommended as it was the easiest for me.
- KDE Connect (only for small files, it fails for files larger than a couple of GB for me)
- Warpinator (failed a few times on me)
Others I know of but didn't use:
- Syncthing
- sshfs
- deckMTP
- cloud services (eg, Google Drive, Dropbox, etc)
- USB drives or SD cards (note: some filesystem formats may not be recognized by Linux, or Windows)

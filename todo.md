### Partial and evolving, unordered, TODO list

#### Features :
 - ~~Implement capture editing window~~
 - ~~Implement arrow overlay~~
 - ~~Implement rectangular overlays~~
 - ~~Implement Text overlay~~
 - ~~Implement overlay resize and move~~
 - ~~Double-clicking one an overlay brings it to front ENHANCEMENT~~
 - ~~Draw pretty overlay handles~~
 - ~~Implement color chooser~~
 - ~~Add key shortcuts (e.g. DEL to remove overlay, CTRL-Z for undo and CTRL-Y / CTRL-SHIFT-Z for redo)~~
 - ~~Implement "exports"~~
 - ~~Implement disk export~~
 - ~~Implement "share" export~~
 - ~~Exports should be made in a separate Dialog (with progress + and notification when done), with return to the main window in case of error~~
 - ~~Upon export completion, the notification window should allow "auto hide" checkbox + Close button~~
 - ~~Implement preferences~~
 - ~~Implement history~~
 - ~~Implement edit from history window~~
 - Finalize history window
 - Persist StarWindow position, and position ExportProgressFrame and ExportCompletionFrame right next to it
 - Implement video using ffmpeg & Jaffree
 - Implement generic preference editor
 - Typing in a Text Overlay should make the overlay grow wider
 - Add Google Drive exporter
 - Add Youtube exporter
 - Implement tray icon
 - Implement global shortcut
 - Implement Windows detection using JNA
 - Close most frames with ESC (ex: History)
 - Implement fixed ratio to 16:9 (shift-drag) or 4:3 (ctrl-drag) + snap to resp 640x360,800x450,960x540,1280x720 or 320x240,400x300,640x480,800x600,1024x768 / ENHANCEMENT: in 4:3 1280x960
 - ? Should undo/redo change selection inside the Action methods (e.g change color, resize) ? - or completely deselect component after operation
 - Ahem, try on Mac and/or Linux

#### UI:
 - ~~Make yellowish icons for disabled buttons~~
 - ~~Look and feel of OK button in dialogs~~
 - ~~Paint title bar~~
 - ~~Radion buttons look and feel (used in Color chooser)~~
 - ~~Cursor look and feel (used in Color chooser)~~
 - Finalize Look and feel (File chooser (save as), Tables)
 - Fix scrollbar corner + thumb icon + colors + gap
 - Switch from "close" to "fade out effect" in export completion window
 - Upscale sun and sun-rays so that runtime downscale provides an anti-aliasing, or better yet draw it by code (gradients etc)
 - Build 3 main buttons at runtime based on a circle + icons (downscale provides an anti-aliasing)

#### Cleanup:
 - Remove EASynth resource dir
 - Remove useless EASynth classes, if any
 - Remove useless icons ?

#### Options ENHANCEMENT:
 - Remember previously used custom colors
 - Add optional "Speech Balloon" overlay
 - Add optional "Line" overlay (with CTRL to constrain)
 - Shift should constrain handle move horizontally/vertically, Ctrl should resize symmetrically
 - Add overlays on video

panda3d-macos-tahoe-audio-issue

Panda3D's musicbox example with openclose.ogg replaced with GUI_rollover.wav which results in no sound on MacOS Tahoe while running on ARM64

GUI_rollover.wav was also converted to an .ogg using Audacity with the following settings: Mono channel 22050 Hz Sample Rate

Using Panda3D installed via pip: pip install -U --pre --extra-index-url https://archive.panda3d.org/ panda3d

Confirmed not working with panda3d-1.11.0.dev3794

Additionally, confirmed to not work with panda3d-1.10.15
# Usage
1. Download the latest release from https://github.com/axstian/multijoiner/releases
2. Extract multijoiner-x64.zip into a folder
3. Run multijoiner.exe before or after starting Roblox
4. Enjoy those beautiful frames 👌
# Submitting An Issue
NOTICE: Issues are currently closed due to spam and the number of non-issues or low quality submissions. They will be reopened once I have the time and capacity to moderate them. Sorry!

Before submitting an issue, please:

Make sure you submit an issue or suggestion
Make sure your question or problem cannot be answered in the FAQ below
Please read previous issues to make sure your question was not asked before
Be as informative as possible: issues with ambiguous titles and missing/low-quality descriptions will be deleted
Include a copy of RFU's console (tray icon->Toggle Console). You can censor any personal information (file paths and so on)
Include steps on how to reproduce the issue, if possible
Include on what platform(s) the issue occurs (normal client, Windows 10 Roblox app, Roblox Studio)
If relevant, include system specifications (e.g. GPU model) and monitor refresh rates

Issues submitted not attempting to follow these guidelines will be closed or deleted.
# FAQ
1. Roblox is force-closing, files are being deleted, and/or my anti-virus is detecting rbxfpsunlocker as malware. What do I do?
All detections are false positives. Internally, RFU "tampers" with running Roblox processes in order to uncap framerate and can appear as suspicious to an anti-virus. For reasons unbeknownst to me, 32-bit builds of RFU garner many more false positive detections than 64-bit builds and are no longer included in new releases. If you don't trust me, feel free to download the repository, review the source code, and compile the project yourself with Visual Studio 2019. Otherwise, add an exception to your anti-virus for rbxfpsunlocker.exe (or the folder it is in).

2. How can I see my FPS?
Press Shift+F5 in-game to view your FPS. In Roblox Studio, go to View->Stats->Summary.

3. How do I resolve choppiness and input lag at high framerates?
Try entering fullscreen using Alt+Enter.

4. I used this program and my framerate is below 60. Why?
To take advantage of RFU, a computer powerful enough to run Roblox at more than 60 FPS is required.

This being said, if you know your computer is powerful enough but still aren't seeing higher framerates with the unlocker, feel free to submit an issue.

5. Can I set a custom framerate cap?
You can create your own list of FPS cap values by editing the FPSCapValues array inside the settings file located in the same folder as rbxfpsunlocker.exe.

6. Why do I get a "Failed to connect to Github" error?
This error means Roblox FPS Unlocker could not connect to the Internet to check for updates. This may be due to your anti-virus, computer firewall, network firewall, or etc. blocking the request. The error can be safely ignored by pressing "Ok".

7. How do I uninstall Roblox FPS Unlocker?
RFU does not install itself anywhere. It can be deleted by simply exiting the program if it is open (tray icon->Exit) and deleting multijoiner.exe.

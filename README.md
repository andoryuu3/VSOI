# VSOI-PSTV
VitaShell One-click Installer for Parental Controls
This fork of VSOI is intended to be Compatible with PSTV/VitaTV consoles-- they do not have the Near app, thus making VSOI incompatible as-is.

Uses VitaRW, mounts vs0, replaces Parental Controls' eboot with VitaShell's, deletes app.db and reboots, forcing a db rebuild. Run a second time to restore icon layout.

Meant to make a permanent copy of VitaShell that can be used even after a system format, to avoid issues like being in 3.65 without VitaShell and a VitaShell backup.

Just inject VitaShell to Parental Controls before formatting and keep it there. If you ever format and need it, it'll be there.

# A Friendly Warning
Using Parental Controls as the system app VitaShell is installed to means VitaShell can and WILL be locked behind a four digit passcode. This has a clear advantage (can keep children and the tech illiterate out of VitaShell) as well as a disadvantage...

KEEP THE PASSCODE SIMPLE.

Sony's official statement (via PSVita user's manual) about forgotten passcodes is this: "If you forget your passcode, you must restore your system."

REMEMBER, if you are on 3.65 Enso, restoring your system is NOT an option if you want to keep HENkaku.

Even so, not all is lost if you forget your passcode. All that means is you will be unable to launch VitaShell from Parental Controls. It does NOT mean you cannot launch VitaShell anymore.

If you ever find yourself in a tough spot where you have formatted your memory card and forgotten your passcode, you can use psvimgtools-frontend by SilicaAndPina to install VitaShell (as its own bubble) via a CMA/QCMA backup.

From there, you can use VitaShell (the new one you just installed) to install ParentalControlBypass, which, ironically, is also by SilicaAndPina. This homebrew app will allow you to reset the Parental Controls passcode to something that (hopefully) this time you will remember. It does not require knowledge of the original passcode.

# Possible ToDo's
* Make a version that installs to Calendar or Email instead
* Make a version that automatically installs to Parental Controls, or to Calendar or Email while a button is held after application loads
* Optionally replace Parental Controls' graphics with VitaShell's

# Credits
Because it's ALWAYS important to give credit where due...
* MajorTomSec for VitaRW (which VSOI and VSOI-PSTV are based on)
* gnmmarechal for VSOI (which I have forked from; I give myself zero credit except for the idea to create a PSTV friendly alternative)

Without these two individuals, VSOI-PSTV would NOT exist.
Thank you both for your efforts.

# VSOI-PSTV

VitaShell One-click Installer for Parental Controls
This fork of VSOI is intended to be Compatible with PSTV/VitaTV consoles-- they do not have the Near app, thus making VSOI incompatible as-is.

Uses VitaRW, mounts vs0, replaces Parental Controls' eboot with VitaShell's, deletes app.db and reboots, forcing a db rebuild.

Meant to make a permanent copy of VitaShell that can be used even after a system format, to avoid issues like being in 3.65 without VitaShell and a VitaShell backup.

Just inject VitaShell to Parental Controls before formatting and keep it there. If you ever format and need it, it'll be there.

# Possible ToDo's
* Make a version that installs to Calendar or Email instead
* Make a version that automatically installs to Parental Controls, or to Calendar or Email while a button is held after application loads
* Optionally replace Parental Controls' graphics with VitaShell's

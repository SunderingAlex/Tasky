# Tasky

Tasky is a personal task manager for Windows. Organize tasks, recurring routines
and deadlines in a compact sidebar or an expanded workspace, with desktop reminders
to help you keep track of what's due.

Optional add-ons include Notes, Focus Timer, Bookmarks, Subscriptions and Weight
Tracker. Your tasks and settings stay on your computer; no account is required
for the task workflow. A fresh installation starts with an empty task list.

## Download and install

1. Open the [latest Tasky release](https://github.com/SunderingAlex/Tasky/releases/latest).
2. Under **Assets**, download the **Windows installer**, the file ending in
   **`Setup-x64.exe`**. You only need the `.exe`; the other files support updates
   and download verification.
3. Run the installer, then open **Tasky** from the Windows Start menu.

The installer is for **Windows x64**. Releases are currently unsigned, so Windows
may display an unknown-publisher or SmartScreen warning. HTTPS and checksums verify
download integrity; they do not establish verified publisher identity.

## Updates and existing data

After installing once, use **Settings** to check for and download updates, then
choose **Restart to update**. Release notes explain what changed in each version.
If you installed 1.12.0, install 1.12.1 manually once to correct its update address.

Moving from a portable copy? Save your work, export a backup and quit the old app
before running the installer. Existing data stays in `%APPDATA%\Tasky`; the
installer does not include anyone else's tasks or personal settings.

Tasky enables reminders, run in tray and Windows startup on first launch; each is
adjustable in Settings. Closing the window keeps Tasky in the tray. Choose
**Quit Tasky** to stop it completely.

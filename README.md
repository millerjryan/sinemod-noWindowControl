# No Window Controls

A CSS-only [Sine](https://github.com/CosmoCreeper/Sine) mod for Zen Browser
that hides the minimize, maximize/restore, and close buttons, including
their container and adjacent button spacers.

## Install with Sine

1. Install Sine in Zen Browser if it is not already installed.
2. Open Zen's Settings and select **Sine Mods**.
3. In the custom repository installation field, enter
   `millerjryan/sinemod-noWindowControl` and click **Install**.
4. Restart Zen if the controls do not disappear immediately.

The mod files must be published to this repository's default branch before
Sine can install them using the repository name above.

## Behavior and limitations

- Hides browser-drawn window controls on Windows, Linux, and macOS.
- Applies only to the main browser window, not web pages, dialogs, or
  picture-in-picture windows.
- Does not change keyboard shortcuts, window-manager actions, or dragging
  behavior in the remaining draggable areas.
- Cannot hide an operating-system-drawn title bar. If one is enabled, use
  Zen's title-bar setting or your window manager to disable it first.

Use keyboard shortcuts or your window manager to close, minimize, or
maximize windows after hiding the buttons. For example, **Alt+F4** closes
the window on Windows and most Linux desktops; **Cmd+Shift+W** closes it
on macOS.

To restore the controls, disable or uninstall **No Window Controls** in
Sine Mods, then restart Zen if needed.

## Manual installation

If you do not use Sine, add the contents of `userChrome.css` to your
profile's `chrome/userChrome.css` file, enable
`toolkit.legacyUserProfileCustomizations.stylesheets` in `about:config`,
and restart Zen. Find the profile folder through `about:support`.
Remove the added CSS and restart to undo a manual installation.
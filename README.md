# Arch Linux updates checker

It automatically check updates in the background.  And popup a notification if new updates available.

## Usage

Download the [cu-notify](https://github.com/timxx/cu-notify/raw/master/cu-notify)  script, and give it execution permission.
Make it autostart. (Otherwise you have to run it every reboot)

If  new updates available, you will see a tray icon on the panel,
with a popup notification.

You can right click on the tray icon, a popup menu will be shown:

- **Got it**  - clear the state and restart the checker

- **Settings** - popup a dialog, you can change your preferences.

- **Quit** - quit the script

In the preferences dialog, you can change:

- **Show tray always** - default is checked, if you want it show with updates available only, uncheck this one.

- **Check interval** - default is check by every two hours


## Lazy man

Install [cu-notify-git](https://aur.archlinux.org/packages/cu-notify-git) package from AUR :)

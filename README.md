# moonraker-telegram

A Script/Programm to send the printer State before, during and after a print via Telegram Messenger. But its only Working with moonraker

---

## switching to virtualenv

i am switch python to virtualenv (for better support at moonraker update manager) so you have to adjust now once the moonraker updatet manager because something has changed

https://github.com/Raabi91/moonraker-telegram/blob/master/docs/FAQ.md#how-to-set-up-updatet-manager-from-moonraker

and you have to run the install.sh script once or do an update via ssh.

https://github.com/Raabi91/moonraker-telegram/blob/master/docs/FAQ.md#how-upgrade-the-script-in-ssh

---

## [Changelog](https://github.com/Raabi91/moonraker-telegram/blob/main/docs/changelog.md)

---

### if you have a problem to edit your config do an upgrade

## until now we supported:

- Print start
- Print Complete
- Print Paused
- Print Failed
- Send State timed
- First Commands avaible (/state, /pause, /resume, /cancel, /help, /print)
- You can deactivate the messages by not entering any text at the config
- send own messages (with a picture) via klipper shell plugin an gcode macros (see [FAQ](https://github.com/Raabi91/moonraker-telegram/blob/main/docs/FAQ.md))
- multiple bots for multiple moonraker setups (see [FAQ](https://github.com/Raabi91/moonraker-telegram/blob/main/docs/FAQ.md))

for the placeholders in the messages look at https://github.com/Raabi91/moonraker-telegram/blob/master/docs/Variables.md

## Info / Contact / Help

If you want to talk to other users of this plugin and maybe have some influence in the development of this plugin, you can join the [Moonraker-Telegram-Group](https://t.me/joinchat/HEI8MD3rG1qhl7tg)

## [Installation](https://github.com/Raabi91/moonraker-telegram/blob/main/docs/Installation.md)

For installation lock at [Installation.md](https://github.com/Raabi91/moonraker-telegram/blob/main/docs/Installation.md) in the docs folder

thanks to sugar0 for a link to an italian install quide: https://klipper-italia.xyz/extra/installazione-moonraker-telegram/

## [FAQ](https://github.com/Raabi91/moonraker-telegram/blob/main/docs/FAQ.md)

Do you have more Question look at the [FAQ](https://github.com/Raabi91/moonraker-telegram/blob/main/docs/FAQ.md)

---

**Klipper** by [KevinOConnor](https://github.com/KevinOConnor) :

https://github.com/KevinOConnor/klipper

---

**Moonraker** by [Arksine](https://github.com/Arksine) :

https://github.com/Arksine/moonraker

---

**Mainsail Webinterface** by [meteyou](https://github.com/meteyou) :

https://github.com/meteyou/mainsail

---

**Fluidd Webinterface** by [cadriel](https://github.com/cadriel) :

https://github.com/cadriel/fluidd

---

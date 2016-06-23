# Apparmor profile for slack-desktop app

## Install instructions

- Install slack-desktop client.
- Download file `usr.lib.slack.slack` and place it in `/etc/apparmor.d/` directory.
- Enable profile by command: `aa-enforce /etc/apparmor.d/usr.lib.slack.slack`
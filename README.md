# polkit-rules

disable password for specific/all applications if user is in the wheel group

## folder of polkit actions that can be disabled

- /usr/share/polkit-1/actions

## installation

- cp 99-nopasswd.rules /etc/polkit-1/rules.d/99-nopasswd.rules

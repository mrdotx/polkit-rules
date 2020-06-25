# polkit-rules

disable password for specific applications if user is in wheel group

## folder of polkit actions that can be disabled

- /usr/share/polkit-1/actions

## installation

- copy file 99-nopasswd.rules to /etc/polkit-1/rules.d

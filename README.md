# plane-tracker-systemd
add this line to the `/etc/sudoers` file:

`%LimitedAdmins ALL=NOPASSWD /bin/systemctl start plane-tracker-service.service`

Copy the service file to `/etc/systemd/system`

run `systemctl daemon-reload`

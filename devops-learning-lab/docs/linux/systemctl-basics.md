# systemctl Basics

## What is systemctl
`systemctl` is used to manage services in Linux systems that use systemd.

## Common commands
- `systemctl status nginx`
- `systemctl start nginx`
- `systemctl stop nginx`
- `systemctl restart nginx`
- `systemctl enable nginx`
- `systemctl disable nginx`

## What each command does
- status = check service state
- start = start service
- stop = stop service
- restart = restart service
- enable = start on boot
- disable = do not start on boot

## Why it matters
Service management is part of daily Linux and DevOps work.

## My notes
If a site is down, checking service status is one of the first actions.
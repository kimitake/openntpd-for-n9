NTP, the Network Time Protocol, is used to keep the computers clock
synchronize.  It provides the ability to sync the local clock to remote
NTP servers and can act as NTP server itself, redistributing the local
clock.

This is an alternative implementation of the NTP software made by the
OpenBSD project.

It only implements a subset of the NTP protocol and does not adjust the
rate of the clock.  Alternatives packages are ntp and chrony.
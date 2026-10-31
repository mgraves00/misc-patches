# misc-patches
miscellaneous patches
### obsd72-ports/graphics_libvips.diff
  patch for OpenBSD 7.2 port of libvips 8.9.2 to 8.13.0

### obsd79/syslogd-explicit-forward.patch
  updates how the !!prog and !**prog behave. The default behavior is that any
logs that get trapped by the !!prog command will only match one command within
that list.  So if you want to log locally and remotely, that is not possible.
This patch allows that.
See https://marc.info/?l=openbsd-bugs&m=176807926301784&w=2 for more info.


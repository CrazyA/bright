bright - a simple brightness-change-script that doesn't require much
================================
Needed something for my HP dm1 because brightness keys didn't work out of the box

Add this to your /etc/rc.local so we can actually write here as a regular user
chmod go+w /sys/class/backlight/acpi_video0/brightness

Bind 'bright -' and 'bright +' to some keyboard shortcuts and enjoy


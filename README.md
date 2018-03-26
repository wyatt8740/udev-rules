# My udev rules

These are just some udev rules that I use which actually work on my system.
udev is by far one of the most opaque non-systemd components of Debian, and it
sometimes takes so long to write a valid, working udev rule that I never want
to have to do so again. That's where this repository comes in.

I made it after trying for about 45 minutes to write a valid udev rule for my
(official Nintendo-branded) Wii U Gamecube controller adapter. Even now, it
works, but I'm not sure exactly why (i.e., which of the three rules that I
ended up with was the one that actually made it work without me having to run
my programs as root). I __think__ that it was the last rule in the file, but
at this point I don't care enough to figure out for sure on a personal system.
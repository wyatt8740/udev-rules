# My udev rules

These are just some udev rules that I use which actually work on my system.
udev is by far one of the most opaque non-systemd components of Debian, and it
sometimes takes so long to write a valid, working udev rule that I never want
to have to do so again. That's where this repository comes in.

I made it after trying for about 45 minutes to write a valid udev rule for using
my (official Nintendo-branded) Wii U Gamecube controller adapter with
[this excellent little program](https://github.com/ToadKing/wii-u-gc-adapter.git).
Even in Dolphin, I need to use this program, because I have to use Dolphin 3.5
to get any hardware accelerated video on my laptop's GPU, and 3.5 did not yet
support the controller adapter natively.

Even now, the rule works, but I'm not sure exactly why (i.e., which of the
three rules it was that actually made it work without me having to run my
programs as root). I __think__ that it was the last rule in the file, but at
this point I don't care enough to figure out for sure on a personal system.

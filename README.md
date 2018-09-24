# Globally disable GNOME's Trash

GNOME's built-in Trash has one particularly annoying feature: every time one
deletes a file on a mounted drive, a ".Trash-<UID>" folder is created. This
happens regardless of whether the storage device in question is formatted with
a Linux filesystem, or not (e.g. USB flash drives or Windows shared folders).

If you are like me and want the Trash gone for good, the accompanying tutorial

[Globally disable GNOME's Trash in Debian-based distributions](https://github.com/Cordic77/libgio-disable-trash/blob/master/Globally%20disable%20GNOME's%20Trash%20in%20Debian-based%20distributions.htm)

describes a solution that will disable this "feature" globally, system-wide
for everyone 🙂

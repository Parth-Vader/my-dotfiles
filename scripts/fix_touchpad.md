Replace with this

`GRUB_CMDLINE_LINUX_DEFAULT="quiet splash psmouse.proto=bare"`

in `\etc\default\grub`

Then,

```
sudo update-grub
```

and Reboot!
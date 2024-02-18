
Burning ISO from arch to USB.

Use - not USB 3.0

```
sudo dd if=/dev/zero of=/dev/sda1
sudo dd if=Downloads/nixos-gnome-23.11.4463.84d981bae8b5-x86_64-linux.iso of=/dev/sda1 bs=4M status=progress conv=fdatasync
```

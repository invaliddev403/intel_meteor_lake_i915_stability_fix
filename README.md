Intel Meteor Lake (MTL) i915 Stability Fix

1. Edit GRUB: sudo nano /etc/default/grub
2. Add to GRUB_CMDLINE_LINUX_DEFAULT: i915.enable\_psr=0 i915.enable\_dc=0
3. Apply: sudo update-grub
4. Recovery flag: nomodeset

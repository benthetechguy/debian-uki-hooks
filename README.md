## Installation
* Place the `kernel` and `initramfs` folders in `/etc`
  - make sure the `zz-efistub` and `efistub` files have executable permissions
* Install the `sbsigntool` and `binutils` packages
* Put your kernel parameters in `/etc/cmdline`
* Put your EFI Secure Boot keys in the `/etc/efi-keys` directory
  - Default is to use `db.key` and `db.crt`, you can edit these to your liking or remove them if secure boot is not needed
* Replace `/dev/null` with the path to your splash image (optional)

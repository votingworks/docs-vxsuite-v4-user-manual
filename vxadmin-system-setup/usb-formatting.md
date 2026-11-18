# Format USB Drives

{% hint style="info" %}
These steps must be completed by a system administrator.
{% endhint %}

A USB drive with a single FAT32 or exFAT partition works without reformatting. If VxSuite reports that a drive can't be used, format it from VxAdmin.

VxAdmin formats USB drives with the exFAT filesystem, which can be read on Windows and macOS and has no limit on the size of individual files. A drive that isn't formatted as FAT32 or exFAT is not recognized until it is formatted.

* [ ] Select `Settings` from the side menu
* [ ] Select `Format USB Drive`

<figure><img src="../.gitbook/assets/vxadmin-format-usb-drive-button.png" alt="VxAdmin Settings screen with the Format USB Drive button highlighted." width="375"><figcaption></figcaption></figure>

{% hint style="warning" %}
Formatting the USB drive deletes all files on the USB drive.
{% endhint %}

* [ ] Select `Format USB Drive` to confirm

<figure><img src="../.gitbook/assets/vxadmin-confirm-format-usb-drive-modal.png" alt="VxAdmin Format USB Drive confirmation dialog." width="375"><figcaption></figcaption></figure>

VxAdmin then confirms your USB drive is ready for use. Repeat these steps for all other USB drives.

<figure><img src="../.gitbook/assets/vxadmin-usb-drive-formatted.png" alt="VxAdmin USB Drive Formatted dialog confirming the drive can now be used with VotingWorks components" width="375"><figcaption></figcaption></figure>

{% hint style="info" %}
Backup drives are not formatted at VxAdmin. See [Back Up and Restore](backup-and-restore.md "mention").
{% endhint %}

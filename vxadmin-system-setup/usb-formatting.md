# USB Formatting

{% hint style="info" %}
The following steps must be completed by a system administrator.
{% endhint %}

A USB drive with a single FAT32 or exFAT partition works without reformatting. If VxSuite reports that a drive can't be used, format it from VxAdmin.

VxAdmin formats USB drives with the exFAT filesystem, which can be read on Windows and macOS and has no limit on the size of individual files. A drive that isn't formatted as FAT32 or exFAT is not recognized until it is formatted.

In VxAdmin, select `Settings` from the side menu and select `Format USB Drive`.

<figure><img src="../.gitbook/assets/vxadmin-format-usb-drive-button.png" alt="VxAdmin Settings screen with the Format USB Drive button highlighted." width="375"><figcaption></figcaption></figure>

Confirm you want to format the USB drive by selecting `Format USB Drive`. **Formatting the USB drive will delete all files on the USB drive.**

<figure><img src="../.gitbook/assets/vxadmin-confirm-format-usb-drive-button.png" alt="VxAdmin Format USB Drive confirmation dialog with the Format USB Drive button highlighted." width="375"><figcaption></figcaption></figure>

VxAdmin will then confirm your USB drive is ready for use. Repeat this step for all other USB drives.

{% hint style="info" %}
Backup drives are not formatted at VxAdmin. See [backup-and-restore.md](backup-and-restore.md "mention").
{% endhint %}

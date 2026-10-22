# USB Formatting

{% hint style="info" %}
The following steps must be completed by a system administrator.
{% endhint %}

Before using a USB drive, whether it's brand new or has been used in a previous election, it should be formatted.

VxAdmin formats USB drives with the exFAT filesystem, which can be read on Windows and macOS and has no limit on the size of individual files. A USB drive that is already formatted as FAT32 or exFAT can be used without reformatting; a drive in any other format will not be recognized until it is formatted at VxAdmin.

In VxAdmin, select `Settings` from the side menu and select `Format USB Drive.`

<figure><img src="../.gitbook/assets/image (5).png" alt="" width="375"><figcaption></figcaption></figure>

Confirm you want to format the USB drive by selecting `Format USB Drive`. **Formatting the USB drive will delete all files on the USB drive.**

<figure><img src="../.gitbook/assets/image (4).png" alt="" width="375"><figcaption></figcaption></figure>

VxAdmin will then confirm your USB drive is ready for use. Repeat this step for all other USB drives.

{% hint style="info" %}
Backup drives are not formatted at VxAdmin. See [backup-and-restore.md](backup-and-restore.md "mention").
{% endhint %}

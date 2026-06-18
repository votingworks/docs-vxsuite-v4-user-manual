# Configure VxScan

{% hint style="info" %}
The following steps must be completed by an election manager.
{% endhint %}

Before you configure VxScan, set up the machine with the [vxscan-setup.md](../election-day-guides/vxscan-setup.md "mention") guide.

To configure **VxScan**, you must do two things in **VxAdmin**:

1. [Save the election package](../vxadmin-system-setup/save-election-package.md "mention") to a USB drive
2. [Create an election manager card](../vxadmin-system-setup/programming-cards.md "mention")

## Loading The Election Package

An unconfigured machine will prompt you to insert an election manager card to log in and then insert a USB drive with the election package saved from VxAdmin.

<div><figure><img src="../.gitbook/assets/vxscan-insert-card.png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxscan-insert-usb-drive.png" alt="" width="375"><figcaption></figcaption></figure></div>

{% hint style="warning" %}
Only one USB drive should be plugged into VxScan at a time. The other USB port is designed as a backup in the event of a failure.
{% endhint %}

After you insert the USB drive, VxScan will automatically begin loading all ballot styles for the election. After the election package is done loading, the election manager menu will be displayed and VxScan will be in test ballot mode.

<figure><img src="../.gitbook/assets/configuration-002-em-election-manager-menu.png" alt="" width="563"><figcaption></figcaption></figure>

To finish configuring VxScan, you must select a polling place. Jurisdictions with only one polling place will skip this step.

## Setting Ballot Mode

Use the toggle button to switch between `Test Ballot Mode` and `Official Ballot Mode`. The machine must be in official ballot mode on election day. Review the [l-and-a-overview.md](../logic-and-accuracy-pre-election-testing/l-and-a-overview.md "mention") instructions to understand which mode to use during L\&A testing.

<figure><img src="../.gitbook/assets/configuration-004-em-official-ballot-mode-button.png" alt="" width="563"><figcaption></figcaption></figure>

## Removing Election Configuration

There are two ways to remove the election configuration and all scanned ballot data.

**Removing Election Configuration - Election Manager**

* [ ] Insert an election manager card
* [ ] Select `Unconfigure Machine`
* [ ] Confirm by selecting `Delete All Election Data`

<div><figure><img src="../.gitbook/assets/configuration-006-em-unconfigure-machine-button.png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/configuration-007-em-unconfigure-machine-modal.png" alt="" width="375"><figcaption></figcaption></figure></div>

You can now configure VxScan with a different election package.

**Removing Election Configuration - System Administrator**

* [ ] Insert a system administrator card
* [ ] Select `Unconfigure Machine`
* [ ] Confirm by selecting `Delete All Election Data`

<figure><img src="../.gitbook/assets/vxscan-sys-admin-unconfigure-machine.png" alt="" width="375"><figcaption></figcaption></figure>

You can now configure VxScan with a different election package.

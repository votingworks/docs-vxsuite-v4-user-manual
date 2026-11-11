# Configure VxMark

{% hint style="info" %}
The following steps must be completed by an election manager.
{% endhint %}

Before you configure VxMark, you must set up the machine. Follow the [VxMark Hardware Setup](vxmark-hardware-setup.md) steps.

To configure **VxMark**, you must do two things in **VxAdmin**:

1. [save-election-package.md](../vxadmin-system-setup/save-election-package.md "mention") to a USB drive.
2. [programming-cards.md](../vxadmin-system-setup/programming-cards.md "mention").

## Inserting Smart Cards & USB Drives

The smart card reader is to the right in the back of the case. Insert smart cards with the chip facing toward you. The USB port is located directly in front of the smart card reader.

<figure><img src="../.gitbook/assets/photo-vxmark-insert-smart-card.jpg" alt="Poll Worker smart card inserted into the card reader at the back of the VxMark case, next to the USB port." width="375"><figcaption></figcaption></figure>

## Loading The Election Package

An unconfigured machine will prompt you to insert an election manager card to log in and then insert a USB drive with the election package saved from VxAdmin.

After the USB drive is inserted, VxMark will automatically begin loading all ballot styles for the election. After the election package is done loading, the election manager screen will appear and VxMark will be in test ballot mode.

<div><figure><img src="../.gitbook/assets/vxmark-unconfigured-screen.png" alt="Unconfigured screen asking to insert an election manager card to configure VxMark" width="188"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmark-em-insert-usb.png" alt="Prompt to insert a USB drive containing an election package" width="188"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmark-em-menu-no-polling-place.png" alt="Election Manager Menu with no polling place selected and Test Ballot Mode active" width="188"><figcaption></figcaption></figure></div>

## Select a Polling Place

Use the `Select a polling place...` dropdown to choose a polling place. Only ballot styles for the selected polling place will be options for voting.

<figure><img src="../.gitbook/assets/vxmark-em-menu-official-ballot-mode-highlighted.png" alt="Election Manager Menu with the Official Ballot Mode button highlighted" width="188"><figcaption></figcaption></figure>

{% hint style="info" %}
If your election package defines only one polling place, there is no need to select one and the `Select a polling place...` dropdown will not be visible.
{% endhint %}

## Setting Ballot Mode

Use the toggle button to switch between `Test Ballot Mode` and `Official Ballot Mode`. The machine must be in official ballot mode on election day.

<div><figure><img src="../.gitbook/assets/vxmark-em-menu-official-ballot-mode-highlighted.png" alt="Election Manager Menu with the Official Ballot Mode button highlighted" width="188"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmark-em-menu-test-ballot-mode-highlighted.png" alt="Election Manager Menu with the Test Ballot Mode button highlighted" width="188"><figcaption></figcaption></figure></div>

## Removing Configuration & Election Data

To remove election configuration (and all data) from VxMark:

* [ ] Log in with an election manager card
* [ ] Select `Unconfigure Machine`
* [ ] Confirm by selecting `Delete All Election Data`

<div><figure><img src="../.gitbook/assets/vxmark-em-menu-unconfigure-highlighted.png" alt="Election Manager Menu with the Unconfigure Machine button highlighted" width="188"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmark-em-unconfigure-modal.png" alt="VxMark election manager menu with the Unconfigure Machine confirmation dialog and Delete All Election Data button." width="188"><figcaption></figcaption></figure></div>

You can now re-configure VxMark with a different election package.

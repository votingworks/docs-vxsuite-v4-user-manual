# Configure VxMark

{% hint style="info" %}
These steps must be completed by an election manager.
{% endhint %}

Before you configure VxMark, you must set up the machine. Follow the steps in [VxMark Hardware Setup](vxmark-hardware-setup.md "mention").

To configure VxMark, you must do two things in VxAdmin:

* [ ] Save the configuration package to a USB drive (see [Save the Configuration Package](../vxadmin-system-setup/save-election-package.md "mention"))
* [ ] Create an election manager card (see [Smart Cards and User Roles](../vxadmin-system-setup/programming-cards.md "mention"))

## Insert Smart Cards and USB Drives

The smart card reader is to the right in the back of the case. Insert smart cards with the chip facing toward you. The USB port is located directly in front of the smart card reader.

<figure><img src="../.gitbook/assets/photo-vxmark-insert-smart-card.jpg" alt="Poll Worker smart card inserted into the card reader at the back of the VxMark case, next to the USB port." width="375"><figcaption></figcaption></figure>

## Load the Configuration Package

An unconfigured machine prompts you to insert an election manager card to log in and then insert a USB drive with the configuration package saved from VxAdmin.

* [ ] Insert an election manager card
* [ ] Insert a USB drive with the configuration package saved from VxAdmin

After the USB drive is inserted, VxMark automatically begins loading all ballot styles for the election. After the configuration package is done loading, the election manager menu appears and VxMark is in test ballot mode.

<div><figure><img src="../.gitbook/assets/vxmark-unconfigured-screen.png" alt="Unconfigured screen asking to insert an election manager card to configure VxMark" width="188"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmark-em-insert-usb.png" alt="Prompt to insert a USB drive containing a configuration package" width="188"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmark-em-menu-no-polling-place.png" alt="Election Manager Menu with no polling place selected and Test Ballot Mode active" width="188"><figcaption></figcaption></figure></div>

## Select a Polling Place

Use the `Select a polling place...` dropdown to choose a polling place. Only ballot styles for the selected polling place are options for voting.

<figure><img src="../.gitbook/assets/vxmark-em-menu-no-polling-place-highlighted.png" alt="VxMark election manager menu with the Select a polling place dropdown highlighted" width="188"><figcaption></figcaption></figure>

{% hint style="info" %}
If your election package defines only one polling place, there is no need to select one and the `Select a polling place...` dropdown isn't visible.
{% endhint %}

## Set the Ballot Mode

Use the toggle button to switch between `Test Ballot Mode` and `Official Ballot Mode`. The machine must be in official ballot mode on election day. Review the [L\&A Overview](../logic-and-accuracy-pre-election-testing/l-and-a-overview.md "mention") instructions to understand which mode to use during logic and accuracy (L&A) testing.

<div><figure><img src="../.gitbook/assets/vxmark-em-menu-official-ballot-mode-highlighted.png" alt="Election Manager Menu with the Official Ballot Mode button highlighted" width="188"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmark-em-menu-test-ballot-mode-highlighted.png" alt="Election Manager Menu with the Test Ballot Mode button highlighted" width="188"><figcaption></figcaption></figure></div>

## Remove Configuration and Election Data

To remove the election configuration and all election data from VxMark:

* [ ] Insert an election manager card
* [ ] Select `Unconfigure Machine`
* [ ] Confirm by selecting `Delete All Election Data`

<div><figure><img src="../.gitbook/assets/vxmark-em-menu-unconfigure-highlighted.png" alt="Election Manager Menu with the Unconfigure Machine button highlighted" width="188"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmark-em-unconfigure-modal.png" alt="VxMark election manager menu with the Unconfigure Machine confirmation dialog and Delete All Election Data button." width="188"><figcaption></figcaption></figure></div>

You can now configure VxMark with a different election package.

{% hint style="info" %}
The system administrator card can also be used to unconfigure the machine, which may be useful if the election manager card for a previous election is no longer available.
{% endhint %}

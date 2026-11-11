# Configure VxMarkScan

{% hint style="info" %}
The following steps must be completed by an election manager.
{% endhint %}

Before you configure VxMarkScan, you must set up the machine. Follow [VxMarkScan Hardware Setup](vxmarkscan-hardware-setup.md) steps.

To configure **VxMarkScan**, you must do two things in **VxAdmin**:

1. [Save the election package](../vxadmin-system-setup/save-election-package.md "mention") to a USB drive.
2. [Create an election manager card](../vxadmin-system-setup/programming-cards.md "mention").

## Inserting Smart Cards & USB Drives

The smart card reader is beneath the accessible controller. The USB port is accessible at the ballot box attachment point. The ballot box must be removed to insert a USB drive. Seal and document the ballot box as required.

<div><figure><img src="../.gitbook/assets/photo-vxmarkscan-smart-card-reader.jpg" alt="Smart card reader slot (yellow) in the recess beside the headphones on VxMarkScan." width="375"><figcaption><p>Smart card reader under accessible controller</p></figcaption></figure> <figure><img src="../.gitbook/assets/photo-vxmarkscan-usb-port.jpg" alt="Arrow pointing to the USB port under the VxMarkScan unit, next to a blue port lock." width="563"><figcaption><p>USB port hidden by the ballot box</p></figcaption></figure></div>

## Loading The Election Package

An unconfigured machine will prompt you to insert an election manager card to log in and then a USB drive with the election package saved from VxAdmin to configure.

After the USB drive is inserted, VxMarkScan will automatically begin loading all ballot styles for the election. After the election package is done loading, the election manager menu screen will appear and VxMarkScan will be in test ballot mode.

<div><figure><img src="../.gitbook/assets/vxmarkscan-unconfigured-screen.png" alt="Unconfigured VxMarkScan prompting to insert an election manager card" width="188"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmark-em-insert-usb.png" alt="Prompt to insert a USB drive containing an election package" width="188"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmarkscan-em-menu-no-polling-place.png" alt="Election Manager Menu with no polling place selected and Test Ballot Mode active" width="188"><figcaption></figcaption></figure></div>

## Select a Polling Place

Use the `Select a polling place...` dropdown to choose a polling place. Only ballot styles for the selected polling place will be options for voting.

{% hint style="info" %}
If your election package defines only one polling place, there is no need to select one and the `Select a polling place...` dropdown will not be visible.
{% endhint %}

## Setting Ballot Mode

Use the toggle button to switch between `Test Ballot Mode` and `Official Ballot Mode`. The machine must be in official ballot mode on election day. Review the [l-and-a-overview.md](../logic-and-accuracy-pre-election-testing/l-and-a-overview.md "mention") instructions to understand which mode to use during logic and accuracy testing.

<div><figure><img src="../.gitbook/assets/vxmarkscan-em-menu-official-ballot-mode-highlighted.png" alt="Election Manager Menu with the Official Ballot Mode button highlighted" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmarkscan-em-menu-test-ballot-mode-highlighted.png" alt="VxMarkScan election manager menu with the Test Ballot Mode button highlighted" width="375"><figcaption></figcaption></figure></div>

## Remove Election Data & Configuration

To remove election configuration (and all data) from VxMarkScan:

* [ ] Log in with an election manager card
* [ ] Select `Unconfigure Machine`
* [ ] Confirm by selecting `Delete All Election Data`&#x20;

<div><figure><img src="../.gitbook/assets/vxmarkscan-em-menu-unconfigure-highlighted.png" alt="VxMarkScan election manager menu with the Unconfigure Machine button highlighted" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmarkscan-em-unconfigure-modal.png" alt="VxMarkScan election manager menu with the Unconfigure Machine confirmation dialog and Delete All Election Data button." width="375"><figcaption></figcaption></figure></div>

You can now re-configure VxMarkScan with a different election package.

# Configure VxScan

{% hint style="info" %}
These steps must be completed by an election manager.
{% endhint %}

Before you configure VxScan, you must set up the machine. Follow the steps in [Set Up VxScan](../election-day-guides/vxscan-setup.md "mention").

To configure VxScan, you must do two things in VxAdmin:

* [ ] Save the configuration package to a USB drive (see [Save the Configuration Package](../vxadmin-system-setup/save-election-package.md "mention"))
* [ ] Create an election manager card (see [Smart Cards and User Roles](../vxadmin-system-setup/programming-cards.md "mention"))

## Load the Configuration Package

An unconfigured machine prompts you to insert an election manager card to log in and then insert a USB drive with the configuration package saved from VxAdmin.

* [ ] Insert an election manager card
* [ ] Insert a USB drive with the configuration package saved from VxAdmin

<div><figure><img src="../.gitbook/assets/vxscan-unconfigured-screen.png" alt="VxScan unconfigured screen prompting to insert an election manager card to configure VxScan" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxscan-em-insert-usb.png" alt="VxScan screen prompting to insert a USB drive containing a configuration package" width="375"><figcaption></figcaption></figure></div>

{% hint style="info" %}
Only one USB drive should be plugged into VxScan at a time. The other USB port is designed as a backup in the event of a failure.
{% endhint %}

After the USB drive is inserted, VxScan automatically begins loading all ballot styles for the election. After the configuration package is done loading, the election manager menu appears and VxScan is in test ballot mode.

<figure><img src="../.gitbook/assets/vxscan-em-election-manager-menu.png" alt="VxScan election manager Configuration tab after loading the configuration package" width="375"><figcaption></figcaption></figure>

## Select a Polling Place

Use the `Select a polling place...` dropdown to choose a polling place.

<figure><img src="../.gitbook/assets/vxscan-em-polling-place-not-selected-highlighted.png" alt="VxScan election manager Configuration tab with the Select a polling place dropdown highlighted" width="375"><figcaption></figcaption></figure>

{% hint style="info" %}
If your election package defines only one polling place, there is no need to select one and the `Select a polling place...` dropdown isn't visible.
{% endhint %}

## Set the Ballot Mode

Use the toggle button to switch between `Test Ballot Mode` and `Official Ballot Mode`. The machine must be in official ballot mode on election day. Review the [L\&A Overview](../logic-and-accuracy-pre-election-testing/l-and-a-overview.md "mention") instructions to understand which mode to use during logic and accuracy (L&A) testing.

<figure><img src="../.gitbook/assets/vxscan-em-official-ballot-mode-button.png" alt="VxScan election manager Configuration tab with the Official Ballot Mode button highlighted" width="375"><figcaption></figcaption></figure>

## Remove Configuration and Election Data

There are two ways to remove the election configuration and all election data from VxScan.

### Remove as an Election Manager

* [ ] Insert an election manager card
* [ ] Select `Unconfigure Machine`
* [ ] Confirm by selecting `Delete All Election Data`

<div><figure><img src="../.gitbook/assets/vxscan-em-unconfigure-machine-button.png" alt="VxScan election manager Configuration tab with the Unconfigure Machine button highlighted" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxscan-em-unconfigure-machine-modal.png" alt="VxScan election manager Unconfigure Machine dialog with Cancel and Delete All Election Data" width="375"><figcaption></figcaption></figure></div>

You can now configure VxScan with a different election package.

### Remove as a System Administrator

* [ ] Insert a system administrator card
* [ ] Select `Unconfigure Machine`
* [ ] Confirm by selecting `Delete All Election Data`

<div><figure><img src="../.gitbook/assets/vxscan-sa-unconfigure-machine-button.png" alt="VxScan System Administrator Menu with the Unconfigure Machine button highlighted" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxscan-sa-unconfigure-machine-modal.png" alt="VxScan system administrator Unconfigure Machine dialog with Cancel and Delete All Election Data" width="375"><figcaption></figcaption></figure></div>

You can now configure VxScan with a different election package.

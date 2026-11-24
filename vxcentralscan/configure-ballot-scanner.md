# Configure VxCentralScan

{% hint style="info" %}
These steps must be completed by an election manager.
{% endhint %}

Before you configure VxCentralScan, you must set up the machine. Follow the steps in [VxCentralScan Hardware Setup](vxcentralscan-hardware-setup.md "mention").

To configure VxCentralScan, you must do two things in VxAdmin:

* [ ] Save the configuration package to a USB drive (see [Save the Configuration Package](../vxadmin-system-setup/save-election-package.md "mention"))
* [ ] Create an election manager card (see [Smart Cards and User Roles](../vxadmin-system-setup/programming-cards.md "mention"))

## Load the Configuration Package

Once the configuration package is saved to a USB drive, you can load the file to VxCentralScan.

* [ ] Set up the VxCentralScan hardware
* [ ] Turn on the VxCentralScan laptop
* [ ] Insert an election manager card to unlock the machine

<div><figure><img src="../.gitbook/assets/vxcentralscan-unconfigured-screen.png" alt="Unconfigured screen asking to insert an election manager card to configure VxCentralScan" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/photo-laptop-insert-smart-card.jpg" alt="Hand inserting a System Administrator smart card, chip first, into the laptop card reader." width="375"><figcaption></figcaption></figure></div>

* [ ] Insert a USB drive with the configuration package saved from VxAdmin

The configuration package loads automatically.

<figure><img src="../.gitbook/assets/vxcentralscan-em-insert-usb.png" alt="Election manager prompt to insert a USB drive containing a configuration package" width="375"><figcaption></figcaption></figure>

VxCentralScan is now configured and in test ballot mode. The election summary information (name, date, jurisdiction, etc.) is shown in the bottom left corner of the screen.

* [ ] Confirm that the election summary information is correct

<figure><img src="../.gitbook/assets/vxcentralscan-scan-ballots-test-mode-election-info-highlight.png" alt="VxCentralScan Scan Ballots screen in test ballot mode with the election summary information in the bottom left corner highlighted" width="375"><figcaption></figcaption></figure>

## Select a Polling Place

There's usually no need to set the polling place on VxCentralScan. For most jurisdictions, it defaults to an absentee polling place like "Central Scanning" or "Absentee Voting" that covers all precincts in the jurisdiction. If VxCentralScan must be limited to certain precincts, select a different polling place from the dropdown. If ballots outside the selected polling place are scanned, VxCentralScan stops on those ballots and doesn't allow tabulating them. The polling place cannot be changed once ballots have been scanned.

## Set the Ballot Mode

When testing is complete, switch VxCentralScan to official ballot mode on the `Settings` screen:

<figure><img src="../.gitbook/assets/vxcentralscan-em-settings-official-ballot-mode-button.png" alt="VxCentralScan Settings screen in test ballot mode with the Official Ballot Mode toggle highlighted." width="375"><figcaption></figcaption></figure>

The `Scan Ballots` page should show zeroes for "Total Batches" and "Total Sheets," and there should also be no test ballot mode banner. VxCentralScan is now ready for the election.

<figure><img src="../.gitbook/assets/vxcentralscan-scan-ballots-empty-batch-stats-highlight.png" alt="Scan Ballots screen ready to scan with the Total Batches and Total Sheets counters highlighted" width="375"><figcaption></figcaption></figure>

## Remove Configuration and Election Data

To remove the election configuration and all election data from VxCentralScan:

* [ ] Insert an election manager card
* [ ] Select `Settings` from the side menu
* [ ] Select `Unconfigure Machine`
* [ ] Confirm by selecting `Delete All Election Data`

<div><figure><img src="../.gitbook/assets/vxcentralscan-em-settings-unconfigure-machine-button.png" alt="VxCentralScan Settings screen with the Unconfigure Machine button highlighted." width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxcentralscan-em-settings-confirm-unconfigure-modal.png" alt="Unconfigure Machine dialog" width="375"><figcaption></figcaption></figure></div>

You can now configure VxCentralScan with a different election package.

{% hint style="info" %}
The system administrator card can also be used to unconfigure the machine, which may be useful if the election manager card for a previous election is no longer available.
{% endhint %}

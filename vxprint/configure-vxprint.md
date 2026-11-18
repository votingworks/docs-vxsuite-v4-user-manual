# Configure VxPrint

{% hint style="info" %}
These steps must be completed by an election manager.
{% endhint %}

You can configure VxPrint without the printer unpacked and set up.

To configure VxPrint, you must do two things in VxAdmin:

* [ ] Save the election package to a USB drive (see [Save the Election Package](../vxadmin-system-setup/save-election-package.md "mention"))
* [ ] Create an election manager card (see [Smart Cards and User Roles](../vxadmin-system-setup/programming-cards.md "mention"))

## Insert Smart Cards

The smart card reader is located on the side of the laptop to the left of the trackpad. Insert a smart card with the chip facing up.

<figure><img src="../.gitbook/assets/photo-vxprint-insert-smart-card.jpg" alt="Hand inserting a system administrator smart card chip-up into the laptop card reader, with arrows" width="375"><figcaption></figcaption></figure>

The picture above shows someone inserting a system administrator card into the laptop. To configure VxPrint, you need to insert an election manager card.

## Load the Election Package

An unconfigured machine prompts you to insert an election manager card to log in and then insert a USB drive with the election package saved from VxAdmin.

* [ ] Insert an election manager card
* [ ] Insert a USB drive with the election package saved from VxAdmin

After the USB drive is inserted, VxPrint automatically begins loading all ballot styles for the election. After the election package is done loading, the election information appears.

<div><figure><img src="../.gitbook/assets/vxprint-locked-unconfigured.png" alt="Locked VxPrint screen asking to insert an election manager card to configure VxPrint" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxprint-em-insert-usb.png" alt="Unconfigured VxPrint prompting to insert a USB drive containing an election package" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxprint-em-election-screen.png" alt="VxPrint Election screen after loading a package, with the polling place dropdown still unselected" width="375"><figcaption></figcaption></figure></div>

## Select a Polling Place

If the election has more than one polling place, an election manager must select one before VxPrint can print ballots. Until a polling place is selected, VxPrint prompts you to insert an election manager card to select a polling place. From the `Election` screen, use the `Select a polling place...` dropdown to choose the polling place for the device.

The selected polling place limits which ballot styles poll workers can print. Election managers can always print any ballot style.

<figure><img src="../.gitbook/assets/vxprint-em-polling-place-dropdown.png" alt="VxPrint Election screen with the polling place dropdown open listing precincts" width="375"><figcaption></figcaption></figure>

{% hint style="info" %}
If your election package defines only one polling place, it is selected automatically and the `Select a polling place...` dropdown isn't visible.
{% endhint %}

## Set the Ballot Mode

By default, VxPrint is in official ballot mode and all ballots printed are official ballots. If you intend to use VxPrint for testing with the rest of the voting system, navigate to the `Settings` page and use the toggle button to switch to `Test Ballot Mode`. In test ballot mode, all ballots printed are test ballots and a "Test Ballot Mode" banner displays in the top bar at all times.

<div><figure><img src="../.gitbook/assets/vxprint-em-settings-ballot-mode-test-highlighted.png" alt="VxPrint Settings in official ballot mode with the Test Ballot Mode toggle highlighted" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxprint-em-settings-ballot-mode-official-highlighted.png" alt="VxPrint Settings in test ballot mode with the Official Ballot Mode toggle highlighted" width="375"><figcaption></figcaption></figure></div>

Switching ballot modes clears the ballot printed counts.

{% hint style="warning" %}
Remember to switch VxPrint back to official ballot mode after logic and accuracy testing is complete.
{% endhint %}

## Remove Configuration and Election Data

To remove the election configuration and all election data from VxPrint:

* [ ] Insert an election manager card
* [ ] Select `Unconfigure Machine`
* [ ] Confirm by selecting `Delete All Election Data`

<div><figure><img src="../.gitbook/assets/vxprint-em-election-unconfigure-highlighted.png" alt="VxPrint Election screen with the Unconfigure Machine button highlighted" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxprint-em-unconfigure-modal.png" alt="VxPrint Unconfigure Machine dialog" width="375"><figcaption></figcaption></figure></div>

You can now configure VxPrint with a different election package.

{% hint style="info" %}
The system administrator card can also be used to unconfigure the machine, which may be useful if the election manager card for a previous election is no longer available.
{% endhint %}

## System Administrator Settings <a href="#system-administrator-settings" id="system-administrator-settings"></a>

The system administrator can always access the `Settings` page, regardless of the election that VxPrint is configured for or whether VxPrint is configured at all. The system administrator has the same `Settings` functionality as the election manager: saving logs, setting the date and time, and verifying the integrity of the software via `Signed Hash Validation`. The system administrator can always unconfigure the election. This is especially useful in the case where VxPrint is configured for a previous election but election manager cards programmed for the previous election are no longer available.

<figure><img src="../.gitbook/assets/vxprint-sa-settings.png" alt="VxPrint system administrator Settings screen with Unconfigure Machine, Save Logs, date and time, and security" width="375"><figcaption></figcaption></figure>

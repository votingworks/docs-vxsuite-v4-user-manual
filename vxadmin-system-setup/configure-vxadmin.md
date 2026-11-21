# Configure VxAdmin

{% hint style="info" %}
These steps must be completed by a system administrator.
{% endhint %}

For each election, you configure VxAdmin in one of two ways: create the election on VxAdmin (see [Create an Election](create-an-election/README.md)), or load an election package provided by VotingWorks or downloaded from VxHub, as described on this page. The [full election package specifications](https://app.gitbook.com/s/Z4bC0rbmogHEUUuMLAUa/system-overview/election-package) can be found in the technical data package.

## Load the Election Package

When VxAdmin is not configured, the screen prompts you to insert a USB drive containing an election package.

* [ ] Insert a USB drive containing the election package

VxAdmin automatically lists the election package(s) available on the USB drive.

* [ ] Select the file name of the correct election package
* [ ] If the file is not automatically listed, select `Select Other File...`
* [ ] If you selected `Select Other File...`, select the file from the USB drive

Once configured, the election screen displays the title and date of your election as well as the date and time VxAdmin was configured.

<div><figure><img src="../.gitbook/assets/vxadmin-election-screen-unconfigured.png" alt="VxAdmin unconfigured Election screen prompting to insert a USB drive containing an election package." width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxadmin-election-screen-select-election-package.png" alt="VxAdmin Election screen listing an election package file on the USB drive to select for configuration." width="375"><figcaption></figcaption></figure></div>

<figure><img src="../.gitbook/assets/vxadmin-election-screen-configured.png" alt="VxAdmin Election screen showing the configured election with Save Election Package and Unconfigure Machine buttons." width="375"><figcaption></figcaption></figure>

## Remove the Election

If you need to change an election package or reset VxAdmin for the next election, you must unconfigure the machine.

* [ ] Select `Election` from the side menu
* [ ] Select `Unconfigure Machine`
* [ ] Select `Delete All Election Data` to confirm

<div><figure><img src="../.gitbook/assets/vxadmin-unconfigure-button.png" alt="VxAdmin Election screen as system administrator with the Unconfigure Machine button highlighted." width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxadmin-confirm-unconfigure-modal.png" alt="VxAdmin Unconfigure Machine confirmation dialog." width="375"><figcaption></figcaption></figure></div>

VxAdmin returns to the initial `Election` screen. VxAdmin can be reconfigured by loading a new election package by repeating the steps above.

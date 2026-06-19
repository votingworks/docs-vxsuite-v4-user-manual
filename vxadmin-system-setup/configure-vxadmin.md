# Configure VxAdmin

For each election, you will configure VxAdmin by loading an election package provided by VotingWorks or downloaded from VxDesign. The [full election package specifications](https://app.gitbook.com/s/Z4bC0rbmogHEUUuMLAUa/system-overview/election-package) can be found in the technical data package.

{% hint style="info" %}
The following steps must be completed by a system administrator.
{% endhint %}

## Load Election Package

When VxAdmin is not configured, the screen will prompt you to insert a USB drive containing an election package. After inserting the USB drive, VxAdmin will automatically list the election package(s) available. Select the file name of the correct election package to configure VxAdmin. If the file is not automatically listed, select `Select Other File...` and manually select the file from the USB drive.

Once configured, the election screen will display the title and date of your election as well as the date and time VxAdmin was configured.

<div><figure><img src="../.gitbook/assets/system-administrator-003-election-screen-unconfigured.png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/system-administrator-004-election-screen-select-election-package.png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/system-administrator-005-election-screen-configured.png" alt="" width="375"><figcaption></figcaption></figure></div>

## Remove Election

If you need to change an election package or reset VxAdmin for the next election, you must unconfigure the machine.

Select `Election` from the side menu and select `Unconfigure Machine`.

<div><figure><img src="../.gitbook/assets/image.png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/system-administrator-008-confirm-unconfigure-button.png" alt="" width="375"><figcaption></figcaption></figure></div>

After confirming by selecting `Delete All Election Data` , you will return to the initial VxAdmin `Election` screen. VxAdmin can be reconfigured by loading a new election package by repeating the steps above.

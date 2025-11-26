# Configure VxAdmin

For each election, you will configure VxAdmin by loading an election package provided by VotingWorks or downloaded from VxDesign. The [full election package specifications](https://app.gitbook.com/s/Z4bC0rbmogHEUUuMLAUa/system-overview/election-package) can be found in the technical data package.

{% hint style="info" %}
The following steps must be completed by a system administrator.
{% endhint %}

## Load Election Package

When VxAdmin is not configured, the screen will prompt you to _Insert a USB drive containing an election package_**.** After inserting the USB drive, VxAdmin will automatically list the election package(s) available. Select the file name of the correct election package to configure VxAdmin. If the file is not automatically listed, select _`Select Other File...`_ and manually select the file from the USB drive.&#x20;

Once configured, the election screen will display the title and date of your election as well as the date and time VxAdmin was configured.

<div><figure><img src="../.gitbook/assets/election-screen-unconfigured (2).png" alt=""><figcaption><p>System administrator election screen before configuring</p></figcaption></figure> <figure><img src="../.gitbook/assets/election-screen-select-election-package (1).png" alt=""><figcaption><p>System administrator election screen listing available election packages</p></figcaption></figure> <figure><img src="../.gitbook/assets/election-screen-configured (2).png" alt=""><figcaption><p>System administrator election screen once configured</p></figcaption></figure></div>

## Remove Election

If you need to change an election package or reset VxAdmin for the next election, you must unconfigure the machine.

Select _`Election`_ from the side menu and select _`Unconfigure Machine`_.

<figure><img src="../.gitbook/assets/election-screen-configured-highlighted (2).png" alt="" width="375"><figcaption><p>Unconfiguring VxAdmin</p></figcaption></figure>

After confirming by selecting _`Delete All Election Data`_ , you will return to the initial VxAdmin Election screen. VxAdmin can be reconfigured by loading a new election package by repeating the steps above.

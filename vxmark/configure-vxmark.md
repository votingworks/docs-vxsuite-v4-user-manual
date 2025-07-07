# Configure VxMark

{% hint style="info" %}
The following steps must be completed by an election manager.
{% endhint %}

Before you configure VxMark, you must set up the machine. Follow [VxMark Hardware Setup](vxmark-hardware-setup.md) steps.

To configure **VxMark**, you must do two things in **VxAdmin**:

1. [Save the election package](../vxadmin-system-setup/save-election-package.md) to a USB drive.
2. [Create an election manager card](../vxadmin-system-setup/programming-cards.md).

## Inserting Smart Cards & USB Drives

The smart card reader is beneath the accessible controller. The USB port is accessible at the ballot box attachment point. The ballot box must be removed to insert a USB drive. Seal and document the ballot box as required.

<div><figure><img src="../.gitbook/assets/PXL_20241119_204113175.jpg" alt="" width="375"><figcaption><p>Smart card reader under accessible controller</p></figcaption></figure> <figure><img src="../.gitbook/assets/PXL_20241125_222936358.jpg" alt="" width="563"><figcaption><p>USB port hidden by the ballot box</p></figcaption></figure></div>

## Loading The Election Package

An unconfigured machine will prompt you to insert an election manager card to log in and then a USB drive with the election package saved from VxAdmin to configure.&#x20;

After the USB drive is inserted, VxMark will automatically begin loading all ballot styles for the election. After the election package is done loading, the election manager menu screen will appear and VxMark will be in test ballot mode.

<div><figure><img src="../.gitbook/assets/mk-insert-card-to-configure.png" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/mk-insert-usb.png" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmark-config (1).png" alt=""><figcaption></figcaption></figure></div>

## Setting Ballot Mode

Use the toggle button to switch between _`Test Ballot Mode`_ and _`Official Ballot Mode`_. The machine must be in official ballot mode on election day.  Review the [l-and-a-overview.md](../logic-and-accuracy-pre-election-testing/l-and-a-overview.md "mention") instructions to understand which mode to use during logic and accuracy testing.

<figure><img src="../.gitbook/assets/vxmark-config (1).png" alt="" width="188"><figcaption></figcaption></figure>

## Remove Election Data & Configuration

To remove election configuration (and all data) from VxMark:

* [ ] Log in with an election manager card
* [ ] Select _`Unconfigure Machine`_

<figure><img src="../.gitbook/assets/vxmark-config-done.png" alt="" width="188"><figcaption></figcaption></figure>

* [ ] Confirm by selecting _`Delete All Election Data`_

You can now re-configure VxMark with a different election package.

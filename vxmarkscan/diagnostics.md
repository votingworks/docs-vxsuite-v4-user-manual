# VxMarkScan Diagnostics

In preparation for an election or in response to issues, the diagnostics interface can help verify VxMarkScan is functioning as expected or pinpoint problems that do arise. Both election managers and system administrators can access the diagnostic interface.

<div><figure><img src="../.gitbook/assets/vxmarkscan-em-menu-diagnostics-highlighted.png" alt="Election Manager Menu with the Diagnostics button highlighted" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmarkscan-sa-menu-diagnostics-highlighted.png" alt="VxMarkScan system administrator menu with the Diagnostics button highlighted" width="375"><figcaption></figcaption></figure></div>

The diagnostics screen shows information about how the machine is configured, how much storage is left on the device, and the current status of the hardware. There are tests for the accessible controller, front headphone input, PAT device input, uninterruptible power supply, and printer-scanner.

<figure><img src="../.gitbook/assets/vxmarkscan-em-diagnostics-full.png" alt="VxMarkScan Diagnostics screen with configuration, storage and hardware component test sections" width="188"><figcaption></figcaption></figure>

For each component test, simply select `Test [Component]` and follow the instructions on the screen. The results of the most recent test are displayed on the diagnostics screen.

{% hint style="warning" %}
If the headphone or PAT test fails, try to unplug and replug the device and try again. If any test continues to fail, restart VxMarkScan and try again.
{% endhint %}

### Readiness Report

The readiness report can be used as a record of system diagnostic verification. Select `Save Readiness Report` to save a copy to a USB drive.

<figure><img src="../.gitbook/assets/vxmarkscan-readiness-report.png" alt="VxMarkScan readiness report listing configuration, storage, and hardware status" width="375"><figcaption><p>Example VxMarkScan Readiness Report</p></figcaption></figure>

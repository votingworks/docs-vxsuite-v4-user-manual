# Setting Date & Time

{% hint style="info" %}
These steps must be completed by a system administrator or an election manager.
{% endhint %}

Because VotingWorks machines do not connect to an external network, the internal clocks may drift slightly. Over time, this can lead to report timestamps being out of date or authentication failures. As a result, a system administrator or election manager should check the date and time of each machine during pre-election setup or logic and accuracy testing and update the time if necessary.

{% hint style="info" %}
The time is automatically updated for daylight saving time.
{% endhint %}

The `Set Date and Time` button is in the `Settings` menu on VxAdmin, VxCentralScan, and VxPrint. On VxScan, VxMark, and VxMarkScan, it's on the election manager and system administrator menus. Within the VxScan election manager menu, the button is in the `More` tab.

* [ ] Select `Set Date and Time`
* [ ] Update the date and time
* [ ] Select `Save`

<figure><img src="../.gitbook/assets/vxadmin-set-date-and-time.png" alt="Set Date and Time dialog with date, time and time zone dropdowns and Cancel and Save buttons." width="375"><figcaption></figcaption></figure>

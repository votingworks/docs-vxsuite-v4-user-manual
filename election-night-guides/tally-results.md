# Tally Results

{% hint style="info" %}
The following steps must be completed by the election manager.
{% endhint %}

Navigate to the tally screen by selecting `Tally` from the side menu. You will see the list of polling places in your election. After loading all cast vote records, there should typically be results loaded for every single polling place. You may use the progress bar under "Locations" and the summary statistics next to "Scanners" and "CVRs" to monitor your progress.

Select `Load` to begin loading cast vote records. One at a time, insert each USB drive containing CVR exports from VxScan or VxCentralScan. The screen will display the list of all CVR exports on the USB drive. Often there will be only one export. If there are multiple, identify the correct export(s) by polling place, timestamp, or CVR count. Click the CVR export(s) you want to load.

<div><figure><img src="../.gitbook/assets/vxadmin-tally-screen-empty.png" alt="VxAdmin Tally screen on the Cast Vote Records tab with no CVRs loaded for any location." width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxadmin-load-cvrs.png" alt="Load CVRs screen listing a CVR export found on the USB drive with a Load button" width="375"><figcaption></figcaption></figure></div>

The selected CVR export should show as "Loaded". At this point, you may eject the USB drive and insert the next USB drive or, if you are done loading CVRs for now, select `Done`. Back on the list of polling places, confirm that each polling place shows as loaded with the expected number of CVRs. You may search the list of polling places by typing in the "Search Locations" bar. You may also filter the list of polling places to only those that have already been loaded by selecting `Loaded` or only those that have not been loaded by selecting `Pending`.

<div><figure><img src="../.gitbook/assets/vxadmin-cvrs-loaded.png" alt="Tally screen after loading, with the CVR export marked Loaded and a Done button" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxadmin-tally-screen-with-cvrs.png" alt="Tally screen listing polling places with CVRs loaded for North Lincoln" width="375"><figcaption></figcaption></figure></div>

Click on a polling place to view all of its associated CVR exports. For each CVR export, the list shows the number of CVRs, the loading time, and the ID of the scanner. Click the trash can icon next to an export to remove it from VxAdmin.

<figure><img src="../.gitbook/assets/vxadmin-tally-screen-location-cvrs-panel-remove-highlighted.png" alt="Tally screen with North Lincoln selected and the CVR export's trash icon highlighted" width="375"><figcaption></figcaption></figure>

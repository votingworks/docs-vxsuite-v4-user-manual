# Retaining & Removing Election Files

### Retaining Election Files

After certification of an election and before configuring a new election, all election files and data should be saved and election package removed from the previous election.

VotingWorks recommends retaining the following files after each election:

* [ ] VxAdmin results file
* [ ] VxAdmin tally reports
* [ ] VxAdmin log file
* [ ] VxScan CVRs
* [ ] VxScan log file
* [ ] VxCentralScan backup (if applicable - see [Retaining and Removing files - VxCS](../vxcentralscan/retaining-and-removing-files-vxcs.md))
* [ ] VxCentralScan log file (if applicable - see [Retaining and Removing files - VxCS](../vxcentralscan/retaining-and-removing-files-vxcs.md))

{% hint style="warning" %}
**Note**: Ballots should have been secured post-tabulation. Follow state guidelines to ensure proper retention.
{% endhint %}

### VxAdmin&#x20;

To save the recommended VxAdmin files, follow these steps when logged in as an Election Manager:

1. Select Reports from the side menu, select _`Full Election Tally Report`_, select _`Export Report PDF.`_
2. Then select _`Export Report CSV`_.

<div>

<figure><img src="../.gitbook/assets/image (165).png" alt="" width="375"><figcaption></figcaption></figure>

 

<figure><img src="../.gitbook/assets/image (166).png" alt="" width="375"><figcaption></figcaption></figure>

</div>

Next lock the machine and log in as a System Administrator. Select Settings from the side menu and _`Save Log File`_. Machine log files are saved in the /logs folder on the USB drive.

<figure><img src="../.gitbook/assets/image (4).png" alt="" width="266"><figcaption></figcaption></figure>

### VxScan CVR Files

VxScan CVRs include the VxScan's CVRs and ballot images. The log file contains the logs. To save the VxScan files, [setup the VxScan](../election-day-guides/vxscan-setup.md) without the ballot box and follow the following steps:

1. Insert Election Manager Card
2. Select CVRs and Logs from the side menu
3. Insert a USB drive
4. Select _`Save CVRs`_
5. Select_`Save Log File`_

<figure><img src="../.gitbook/assets/image (3).png" alt="" width="265"><figcaption></figcaption></figure>

{% hint style="info" %}
**Log files** contain records of user interactions with the machine (e.g., election officials and poll workers unlocking the machine, voters casting ballots, etc.) as well as internal system information (e.g., the status of paper running through the scanner, errors, etc.). [A detailed description for each event in the log can be found in Github](https://github.com/votingworks/vxsuite/blob/main/libs/logging/VotingWorksLoggingDocumentation.md).
{% endhint %}

### Removing Election Files

In VxAdmin, log in with a System Administrator Card, select Definition from the side menu and select _`Unconfigure Machine`_.

<figure><img src="../.gitbook/assets/image.png" alt="" width="267"><figcaption></figcaption></figure>

In VxScan, insert an Election Manager Card and select _`Unconfigure Machine`_.

<figure><img src="../.gitbook/assets/image (2).png" alt="" width="268"><figcaption></figcaption></figure>


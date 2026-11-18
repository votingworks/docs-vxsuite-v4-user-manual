# Central Scanning

VxCentralScan is a central scanner that allows you to quickly scan large batches of ballots. VxCentralScan is often used to scan absentee and provisional ballots, but can be used to scan any ballot. VxCentralScan can also be used to quickly verify a test deck or re-tabulate an out-of-balance precinct.

Follow the [VxCentralScan Hardware Setup](vxcentralscan-hardware-setup.md "mention") instructions to prepare the system for use.

## Scan Ballot Batches

Before scanning the first batch of ballots:

* [ ] Confirm that VxCentralScan does not have a yellow test ballot mode banner at the top and displays zeroes under "Total Batches" and "Total Sheets"
* [ ] If the test ballot mode banner is present, go to `Settings` to switch to official ballot mode
* [ ] If the counts are not zero, you may go to `Batch History` and select `Delete All Batches`

<figure><img src="../.gitbook/assets/vxcentralscan-scan-ballots-empty.png" alt="Scan Ballots screen in official ballot mode with zeroes for Total Batches and Total Sheets" width="375"><figcaption></figcaption></figure>

* [ ] Load a stack of ballots into the feeder tray of the scanner

VotingWorks recommends the following batch sizes for typical, thick ballot paper:

* Ricoh fi-8170 - maximum 30 ballot sheets at a time
* Ricoh fi-7600 - maximum 100 ballot sheets at a time
* Ricoh fi-8950 - maximum 250 ballot sheets at a time

The ballots need to be in a neat stack, unfolded and lying flat, but ballots can be in any orientation (e.g., upside down or backwards is fine).

* [ ] Select `Start Scanning`

The "Sheets" count goes up as the scanner processes each ballot.

<figure><img src="../.gitbook/assets/vxcentralscan-scan-ballots-scanning.png" alt="Scan Ballots screen actively scanning a batch with a Pause Scanning button" width="375"><figcaption></figcaption></figure>

Once the input tray is empty, you have the option to save the batch, discard the batch, or continue scanning:

* `Save Batch` - Finalizes the batch and its cast vote records (CVRs). This is the most common choice.
* `Continue Scanning` - Continues scanning with any ballots added to the input tray. This is typically used when a batch is too large to fit in the input tray and must be split into multiple loads.
* `Discard Batch` - Erases all data related to the batch. Use this if the batch needs to be rescanned or was scanned accidentally.

<figure><img src="../.gitbook/assets/vxcentralscan-scan-ballots-batch-complete.png" alt="Scan Ballots screen paused with input tray empty and Save Batch, Continue Scanning, Discard Batch" width="375"><figcaption></figcaption></figure>

After saving a batch:

* [ ] Remove the batch from the output tray on the scanner
* [ ] Place the next stack of ballots in the input tray
* [ ] Repeat the scanning process until all ballots are scanned

{% hint style="info" %}
If you find an issue with a batch after it has been saved, it can be deleted from the `Batch History` page by an election manager.
{% endhint %}

## Handle Ballots Needing Attention

VxCentralScan stops scanning and presents a review screen if a ballot needs attention. The review screen displays an image of the scanned ballot sheet and the reason why scanning was stopped, and confirms that this ballot sheet has not been tabulated yet. There are two reasons VxCentralScan might stop on a ballot: the ballot needs adjudication or the ballot could not be accepted.

### Ballots Needing Adjudication

VxCentralScan may be configured to stop on ballots requiring adjudication for any combination of these reasons: overvotes, blank ballots, undervotes, or marginal marks.

When the scanner stops:

* [ ] Remove the last ballot sheet scanned from the scanner output tray
* [ ] Confirm it matches the ballot sheet displayed on screen
* [ ] Follow your jurisdiction's review requirements

If the ballot needs to be reviewed by someone not operating the scanner or needs to be duplicated to be tabulated properly, select `Confirm Ballot Removed`. If the ballot should be tabulated as-is, meaning that overvoted contests and marginal marks are ignored but any other valid votes are counted, select `Tabulate Ballot`.

<div><figure><img src="../.gitbook/assets/vxcentralscan-adjudication-overvote.png" alt="Ballot Not Counted screen for an overvote with the Mayor contest highlighted on the ballot" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxcentralscan-adjudication-blank-ballot.png" alt="Ballot Not Counted screen for a blank ballot with Confirm Ballot Removed and Tabulate Ballot" width="375"><figcaption></figcaption></figure></div>

After you accept or remove the ballot, the batch is paused. You can choose to continue scanning the rest of the ballots in the input tray or to discard the batch.

<figure><img src="../.gitbook/assets/vxcentralscan-scan-ballots-paused.png" alt="Scan Ballots screen paused because a ballot required review, with Continue Scanning and Discard Batch" width="375"><figcaption></figcaption></figure>

{% hint style="info" %}
The scanner only presents one adjudication reason at a time. For example if the scanner is configured to stop on overvotes and undervotes and a ballot has both, the scanner displays the overvote notification. The order of priority is overvotes, blank ballot, undervotes, and then marginal marks.
{% endhint %}

### Unreadable and Rejected Ballots

VxCentralScan shows an "Unreadable" ballot screen if it's unable to interpret the ballot due to page skew, dust, or damage. When a ballot sheet is shown as unreadable, you can safely remove the ballot and re-scan the ballot sheet. If the ballot is unreadable on a second scan, remove the ballot for duplication.

<figure><img src="../.gitbook/assets/vxcentralscan-adjudication-unreadable.png" alt="Ballot Not Counted screen for an unreadable ballot with Confirm Ballot Removed" width="375"><figcaption></figcaption></figure>

The ballot also might be rejected because it doesn't match how the scanner is configured. For example, the ballot may be from the wrong election, may be in the wrong mode (test vs. official), or may be from a precinct that VxCentralScan is not configured to accept.

<div><figure><img src="../.gitbook/assets/vxcentralscan-adjudication-wrong-election.png" alt="Ballot Not Counted screen for a ballot from the wrong election with Confirm Ballot Removed" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxcentralscan-adjudication-wrong-precinct.png" alt="Ballot Not Counted screen for a ballot from a precinct outside the selected polling place with Confirm Ballot Removed" width="375"><figcaption></figcaption></figure></div>

## Imprinting

Imprinters are an optional add-on for VxCentralScan's commercial off-the-shelf (COTS) scanners - see [VxCentralScan Hardware Setup > Imprinting](vxcentralscan-hardware-setup.md#imprinting) for additional details. If an imprinter is installed, an audit ID is printed on the edge of each ballot sheet. The audit ID is a shortened version of the batch ID plus the number of the ballot within the batch.

Before scanning ballots, ideally during logic and accuracy testing, ensure the imprinter is properly aligned such that it prints on the edge of the ballot by scanning a test sheet.

If an imprinter is installed, imprinting is enabled by default. In order to skip imprinting for an election or for a batch, an election manager may go to `Settings` and toggle to `Imprinting Disabled`. This setting resets to `Imprinting Enabled` for each election.

<figure><img src="../.gitbook/assets/vxcentralscan-em-settings-imprinting-disabled-button.png" alt="VxCentralScan Settings screen with the Imprinting Disabled toggle highlighted." width="375"><figcaption></figcaption></figure>

## Batch History and Cast Vote Records (CVRs)

Navigate to the `Batch History` page to see the list of scanned batches. For each batch, the list shows the batch name (e.g., "Batch 4"), the number of ballot sheets in that batch, and the time at which the batch was saved.

<figure><img src="../.gitbook/assets/vxcentralscan-batch-history.png" alt="Batch History screen listing scanned batches with Save CVRs and Delete buttons" width="375"><figcaption></figcaption></figure>

If a batch was scanned incorrectly or accidentally, an election manager may use the `Delete` or `Delete All Batches` button.

To export CVRs for loading into VxAdmin for further adjudication and reporting:

* [ ] Select the `Save CVRs` button in the top right
* [ ] When prompted, insert a USB drive
* [ ] Once the USB drive is recognized, select `Save`
* [ ] Select `Eject USB`
* [ ] Once the USB drive is ejected, remove it
* [ ] If using multiple VxCentralScan stations, repeat saving CVRs for each one

<figure><img src="../.gitbook/assets/vxcentralscan-save-cvrs-modal-usb-inserted.png" alt="VxCentralScan Save CVRs dialog with a USB drive inserted and the Save button" width="375"><figcaption></figcaption></figure>

{% hint style="warning" %}
Seal tabulated ballots into a secure container after tabulation and record the seal number as required. Follow state guidelines to ensure proper retention.
{% endhint %}

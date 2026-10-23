# Supply List

The specifications and supply lists below define all the materials to run an election in addition to the machines and smart cards.

## Ballots

Ballots must be printed according to [paper ballot specifications](https://app.gitbook.com/s/Z4bC0rbmogHEUUuMLAUa/system-performance-and-specifications/paper-ballot-specifications "mention").

### Marking Utensils

The marking utensil for hand marked ballots should be a black or blue ink pen that dries quickly. Never use markers or highlighters.

## USB Drives

VotingWorks recommends the 64GB SanDisk Ultra Flair USB 3.0 drive (SDCZ73-064G-G46) as a cost-effective general purpose USB drive, but any USB drive meeting the specifications below can be used.

| Attribute  | Requirement                              |
| ---------- | ---------------------------------------- |
| Protocol   | 3.0 minimum                              |
| Capacity   | 64GB minimum                             |
| Length     | 55mm maximum, measured from inserted tip |
| Read Speed | 60 Mbps minimum                          |

A faster drive may be necessary when exporting large volumes of ballots from VxCentralScan, for which the 128GB SanDisk Extreme PRO USB 3.2 drive (SDCZ880-128G-G46) is recommended.

VotingWorks recommends using a new USB drive for each election and each voting device as well as separate USBs for L\&A testing.

## Backup Drives

VxAdmin saves election backups to a dedicated backup drive rather than a general purpose USB drive; see [backup-and-restore.md](../vxadmin-system-setup/backup-and-restore.md "mention"). VotingWorks recommends the Western Digital 8TB Elements Desktop external hard drive (WDBWLG0080HBK), but any drive meeting the specifications below can be used. A backup drive must be prepared by VotingWorks before it can be used, whether it is purchased from VotingWorks or elsewhere.

| Attribute   | Requirement              |
| ----------- | ------------------------ |
| Interface   | USB 3.0 (5 Gbps) minimum |
| Read Speed  | 100 MB/s minimum         |
| Write Speed | 100 MB/s minimum         |

No minimum capacity is specified. A backup drive holds one backup per election, and the size of each backup depends on the number of ballots cast, the ballot size and number of sheets per ballot, the tabulator used (VxScan or VxCentralScan), the configured ballot image bit depth, and other factors that determine CVR and ballot image sizes. As a point of reference, for a jurisdiction with a turnout of 250,000 voters per election, single-sheet ballots, and standard system settings, a 1TB drive should hold at least 10 elections. Jurisdictions can extrapolate from this figure or ask VotingWorks for a recommendation.

## Seals

Cases should be secured with single use tamper evident numbered seals, such as heavy-duty pull-tight seals. You may use different seals as preferred by your jurisdiction and may choose to use different types of seals, or even locks, if you confirm they fit through the seal points and properly secure the seal point. Lock shackles must be less than 5mm (3/16") in size to fit in all seal points.

## Scanner Cleaning Supplies

The scanners for VxScan, VxCentralScan, and VxMarkScan can be cleaned with scanner-specific cleaning fluid, such as Ricoh Cleaner F1 (PA03950-0352) or isopropyl alcohol with a concentration of 70% or higher. The fluid should be applied to a microfiber or lint-free cloth. The recommended cleaning SKU can clean a scanner 100 times.

## VxAdmin Supply List

<table><thead><tr><th width="171">Item</th><th width="303">Recommendation</th><th>Supplier</th></tr></thead><tbody><tr><td>Printer Paper</td><td>HP Premium 32, or equivalent</td><td>Various</td></tr><tr><td>Printer Toner</td><td>HP 148A or HP 148X Black Toner</td><td>Various</td></tr></tbody></table>

VotingWorks recommends having a backup toner cartridge and extra reams of paper on hand for all elections. HP 148A is rated for 2,900 printed pages and HP 148X is rated for 9,500 printed pages.

## VxScan Supply List

| Item                      | Recommendation                           | Supplier    |
| ------------------------- | ---------------------------------------- | ----------- |
| Thermal Paper Rolls       | VotingWorks Provided                     | VotingWorks |
| Headphone Ear Covers      | BBTO headphone ear covers, or equivalent | Various     |
| Scanner Cleaning Supplies | See above                                | Various     |

VotingWorks recommends cleaning the scanner and replacing the thermal paper roll for each VxScan for each election. VotingWorks also recommends keeping scanner cleaning supplies and extra thermal paper rolls readily available on election day.

## VxCentralScan Supply List

| Item                      | Recommendation | Supplier |
| ------------------------- | -------------- | -------- |
| Scanner Cleaning Supplies | See above      | Various  |

VotingWorks recommends cleaning the scanner for each election. VotingWorks also recommends keeping scanner cleaning supplies readily available on election day. Occasionally, the rollers will need to be replaced [as detailed in the scanner's documentation.](https://github.com/votingworks/docs-vxsuite-v4/tree/main/hardware-assets/cots-documentation/central-system/ricoh-fi-8170).

## VxMarkScan Supply List

| Item                      | Recommendation                           | Supplier    |
| ------------------------- | ---------------------------------------- | ----------- |
| Thermal Ballot Paper      | VotingWorks Provided                     | VotingWorks |
| Headphone Ear Covers      | BBTO headphone ear covers, or equivalent | Various     |
| Scanner Cleaning Supplies | See above                                | Various     |

VotingWorks recommends cleaning the scanner for each election. VotingWorks also recommends keeping scanner cleaning supplies readily available on election day. Headphone ear covers are single use and should be disposed after each use.

## VxMark Supply List

| Item                 | Recommendation                           | Supplier |
| -------------------- | ---------------------------------------- | -------- |
| Printer Paper        | HP Premium 32, or equivalent             | Various  |
| Printer Toner        | HP 148A or HP 148X Black Toner           | Various  |
| Headphone Ear Covers | BBTO headphone ear covers, or equivalent | Various  |

## VxPrint Supply List

| Item          | Recommendation                 | Supplier |
| ------------- | ------------------------------ | -------- |
| Printer Paper | HP Premium 32, or equivalent   | Various  |
| Printer Toner | HP 148A or HP 148X Black Toner | Various  |

## Additional Information

For part numbers not listed above or details on long-term maintenance, consult the System Maintenance section, in particular the [approved-parts-list.md](../system-maintenance/approved-parts-list.md "mention").

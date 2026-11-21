---
description: Open-source software, rugged hardware, and paper ballots.
---

# VotingWorks Overview

This guide walks you through the complete process to set up, test, and operate the voting system. If you have questions, please don't hesitate to reach out to the VotingWorks team by emailing [help@vx.support](mailto:help@vx.support) or calling **(510) 426-9991**.

## System Overview

VxSuite consists of two subsystems:

1. **Central System:** all equipment necessary for election programming, central batch ballot scanning, results aggregation, adjudication, and reporting.
2. **Precinct System:** all equipment necessary for use at the precinct to scan hand-marked paper ballots and provide an accessible ballot-marking device (BMD) for voters who need or prefer assistance marking a ballot.

### Central System

VotingWorks Central System includes three components:

1. VxAdmin: the main tool for local election administrators, which creates or loads elections, produces ballots, and tabulates and reports results on election night.
2. VxCentralScan (optional): a central scanner used for rapidly scanning absentee or vote by mail ballots.
3. VxPrint (optional): an on-demand ballot printer, which lets election workers print unfilled or blank ballots.

### Precinct System

VotingWorks Precinct System consists of three portable, self-contained products:

1. VxScan: a voter-facing precinct scanner that scans paper ballots and notifies voters of ballot issues for second-chance voting.
2. VxMark: a tabletop accessible ballot-marking device with a printer that produces a voter-verifiable paper ballot.
3. VxMarkScan: a free-standing accessible ballot-marking device with a printer that produces a voter-verifiable paper ballot.

<div><figure><img src=".gitbook/assets/photo-vxscan-full-setup.png" alt="VxScan case open on top of the expanded ballot box, screen off, poll worker door and ballot box door closed" width="375"><figcaption><p>VxScan</p></figcaption></figure> <figure><img src=".gitbook/assets/photo-vxmarkscan-full-setup.png" alt="VxMarkScan assembled in its privacy booth with the controller, headphones, touchscreen, and printer-scanner tray" width="375"><figcaption><p>VxMarkScan</p></figcaption></figure></div>

<figure><img src=".gitbook/assets/photo-vxmark-full-setup.jpg" alt="VxMark in its open case beside an HP LaserJet printer and headphones, screen asking for an election manager card" width="375"><figcaption><p>VxMark</p></figcaption></figure>

Voters at the precinct vote on hand-marked paper ballots (bubble ballots) and cast their ballot into VxScan. If requested, voters can instead mark their ballot on VxMark, which prints a ballot the voter then casts, or vote and cast their ballot on VxMarkScan.

## Paper Ballots

All votes cast using VotingWorks equipment are on paper ballots for security and post-election auditing. There are two types of VotingWorks paper ballots:

*   **Hand-marked paper ballot (bubble ballot)**

    * All absentee voters receive a hand-marked paper ballot (bubble ballot) that is printed by either a third-party print vendor, from ballot files saved at VxAdmin or VxHub, or an on-demand printer (VxPrint). Absentee ballots are scanned by election administrators using a high-speed central scanner (VxCentralScan) or the precinct scanner (VxScan).
    * Most in-precinct voters receive a hand-marked paper ballot (bubble ballot) that is printed by either a third-party printer or an on-demand printer (VxPrint) to hand mark. Precinct ballots are scanned by voters using a precinct scanner (VxScan).

    <figure><img src=".gitbook/assets/diagram-hmpb-test-ballot-page-1.png" alt="Page 1 of a hand-marked paper test ballot with fill-in ovals, timing marks, and instructions" width="375"><figcaption><p>Example hand-marked paper ballot</p></figcaption></figure>
* **Machine-marked paper ballot (summary ballot)** (via ballot-marking device)
  * In-precinct voters may request to use the tabletop accessible ballot-marking device (VxMark), or the free-standing accessible ballot-marking device (VxMarkScan), both of which print a voter verifiable paper ballot. A ballot printed by VxMark is then cast by the voter, either in the precinct scanner (VxScan) or by being scanned later at a high-speed central scanner (VxCentralScan). VxMarkScan prints the ballot, lets the voter verify it, and casts it into its attached ballot box.

<figure><img src=".gitbook/assets/vxmark-printed-ballot.png" alt="Printed BMD summary ballot listing each contest and the voter's selection in three columns" width="375"><figcaption><p>Example machine-marked paper ballot (summary ballot)</p></figcaption></figure>



{% hint style="info" %}
VotingWorks provides technical support through the email and phone number listed at the top of the page. Upgrades and defect correction are defined in the customer's contract and scheduled through VotingWorks support system.
{% endhint %}

{% hint style="info" %}
All functions in this user manual can be performed by one individual unless otherwise stated.
{% endhint %}

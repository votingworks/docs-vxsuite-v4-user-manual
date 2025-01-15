---
description: Open-source software, rugged hardware, and paper ballots.
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# VotingWorks Overview

This guide walks you through the complete process to set up, test, and operate the voting system. If you have questions, please don't hesitate to reach out to the VotingWorks team by emailing [help@vx.support](mailto:help@vx.support) or calling **(510) 426-9991**.

## System Overview

VotingWorks consists of two subsystems:

1. **Central System:** all equipment necessary for election programming, central batch ballot scanning, results aggregation, write-in adjudication, and reporting.
2. **Precinct System:** all equipment necessary for use at the precinct to scan hand-marked ballots and provide an accessible ballot marking device for voters who need or prefer assistance marking a ballot.

### Central System

VotingWorks Central System includes two components:

1. **VxAdmin**: the main tool for local election administrators, which programs elections, tabulates and reports results on election night.
2. **VxCentralScan** (optional): a central scanner used for rapidly scanning absentee or vote by mail ballots.

<figure><img src=".gitbook/assets/PXL_20241119_221005359.jpg" alt="" width="375"><figcaption><p>VxAdmin</p></figcaption></figure>

<figure><img src=".gitbook/assets/PXL_20241119_215840432 (2).jpg" alt=""><figcaption><p>VxCentralScan</p></figcaption></figure>

### Precinct System

VotingWorks Precinct System consists of two portable, self-contained products:

1. **VxScan**: a voter-facing precinct scanner that scans paper ballots and notifies voters of ballot issues for second-chance voting.
2. **VxMark**: an accessible ballot marking device with a printer that produces a voter-verifiable paper ballot.

Voters at the precinct vote on hand-marked paper ballots and cast their ballot into VxScan, with the option to vote and cast one's ballot on VxMark if requested.&#x20;

<div><figure><img src=".gitbook/assets/PXL_20241031_183333061.jpg" alt="" width="375"><figcaption><p>VxScan</p></figcaption></figure> <figure><img src=".gitbook/assets/PXL_20241119_204010865.jpg" alt="" width="375"><figcaption><p>VxMark</p></figcaption></figure></div>

## Paper Ballots

All votes cast using VotingWorks equipment are on paper ballots for security and post-election auditing. There are two types of VotingWorks paper ballots:

* **Hand-marked paper ballot**
  * All absentee voters will receive a hand-marked paper ballot that is printed by a print vendor. Absentee ballots are scanned by election administrators using a high-speed central scanner (VxCentralScan) or the precinct scanner (VxScan).
  * Most in-precinct voters will receive a hand-marked paper ballot that is printed by a third-party printer to hand mark. Precinct ballots are scanned by voters using a precinct scanner (VxScan).

###

* **Machine-marked paper ballot** (via ballot marking device)
  * In-precinct voters may request to use the accessible ballot marking device (VxMark), which prints a voter verifiable paper ballot and deposits it into the attached ballot box. Election administrators or poll workers later scan the machine-marked paper ballot at the precinct scanner (VxScan) or the high-speed central scanner (VxCentralScan).

<div><figure><img src=".gitbook/assets/Screenshot 2023-12-19 at 7.53.02 PM.png" alt="" width="375"><figcaption><p>Example hand-marked paper ballot</p></figcaption></figure> <figure><img src=".gitbook/assets/TDP Diagrams.png" alt="" width="375"><figcaption><p>Example machine-marked paper ballot</p></figcaption></figure></div>

{% hint style="info" %}
VotingWorks provides technical support through the email and phone number listed at the top of the page.  Upgrades and defect correction are defined in the customer's contract and scheduled through VotingWorks support system.&#x20;
{% endhint %}

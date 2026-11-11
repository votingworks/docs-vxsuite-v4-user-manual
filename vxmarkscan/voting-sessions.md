# Voting Sessions

### Activating a Voting Session

{% hint style="warning" %}
A voter may bring their own Personal Assistive Technology (PAT) device (ex. jelly bean switch, sip and puff device, etc.) or headphones. It must have a 3.5mm plug or connector. Once plugged in, a test screen will pop up to assist in configuration. See [VxMarkScan Diagnostics](diagnostics.md) for instructions.
{% endhint %}

{% include "../.gitbook/includes/sanitizing-headphones-instructions.md" %}

If a voter chooses to use VxMarkScan:

* [ ] Insert a poll worker card into the card reader beneath the accessible controller
* [ ] Select the voter's ballot style

<div><figure><img src="../.gitbook/assets/vxmarkscan-unauthenticated-polls-opened.png" alt="VxMarkScan Insert Card screen shown while polls are open and no card is inserted" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmarkscan-pw-menu-polls-open.png" alt="VxMarkScan poll worker menu with polls open, showing Start a New Voting Session and Insert Printed Ballot" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmarkscan-pw-start-voting-session-button.png" alt="VxMarkScan poll worker menu with the ballot style button under Start a New Voting Session highlighted" width="375"><figcaption></figcaption></figure></div>

* [ ] When prompted, feed one sheet of paper into the front input tray
* [ ] Once loaded, the screen will show that the voting session is active
* [ ] Review the precinct and ballot style to ensure it was selected correctly for the voter
* [ ] Remove the poll worker card

<div><figure><img src="../.gitbook/assets/vxmarkscan-pw-load-ballot-sheet.png" alt="VxMarkScan Load Ballot Sheet prompt asking to feed one sheet into the front input tray" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmarkscan-pw-loading-sheet.png" alt="VxMarkScan Loading Sheet screen with a spinner while the ballot sheet is pulled in" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmarkscan-pw-remove-card-to-vote.png" alt="VxMarkScan Remove Card to Begin Voting Session screen showing the selected ballot style" width="375"><figcaption></figcaption></figure></div>

{% hint style="warning" %}
If the wrong ballot style or precinct was selected, insert the poll worker card (if not already inserted) and select `Cancel Voting Session` to return to the poll worker menu.
{% endhint %}

### Marking a Ballot

Let the voter know they can begin voting by selecting `Start Voting`.

One contest will display at a time. The voter will select the candidate(s) of their choice. The voter moves to the next contest by selecting `Next`. The voter can skip a contest by selecting `Next` without making a selection. To return to a previous contest, select `Back`. A `More` button will display if there are more candidates or text than fit on a single screen. The `View All` button can be used to jump to a review screen summarizing all contest selections, described in greater detail below.

<div><figure><img src="../.gitbook/assets/vxmark-voting-start-screen.png" alt="Voting start screen showing the election name, polling place and a Start Voting button" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmarkscan-voting-single-seat-selection.png" alt="VxMarkScan Mayor contest with one candidate selected and zero votes remaining" width="375"><figcaption></figcaption></figure></div>

{% hint style="info" %}
If a voter would like to change a selection, they must first deselect a candidate previously selected.
{% endhint %}

### Entering a Write-In

To enter a write-in candidate, select `add write-in candidate` and use the keyboard to type in the candidate's name. Select `Accept` when finished.

<div><figure><img src="../.gitbook/assets/vxmark-voting-write-in-button.png" alt="Controller contest screen with the add write-in candidate option highlighted" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmark-voting-write-in-keyboard.png" alt="Write-In dialog for the Controller contest with the on-screen keyboard and the name NEMO entered." width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmark-voting-write-in-accepted.png" alt="Controller contest screen with write-in candidate NEMO selected" width="375"><figcaption></figcaption></figure></div>

### Reviewing Votes

After working through all contests, a "Review Your Votes" screen appears that allows the voter to change any vote by selecting `Change`. Once selections have been reviewed, select `Print My Ballot`. The ballot will print and be displayed for review.

{% hint style="warning" %}
The "Ballots Printed" count in VxMarkScan intentionally increments up by one for all ballot prints, _including spoiled ballots_. Printing errors like jammed ballots and partial prints are also considered spoiled ballots. Spoiled ballots must be addressed procedurally with the assistance of a poll worker or election official and follow a jurisdiction-defined process for tracking through the end of the night. VxMarkScan counts every printing action so that election officials have clear information for their post-election precinct ballot accounting or reconciliation process.
{% endhint %}

The final "Review Your Votes" screen is displayed to compare the official ballot selections with the screen. Select `Cast My Ballot` to cast the ballot.

<div><figure><img src="../.gitbook/assets/vxmark-voting-review.png" alt="Review Your Votes screen listing selections with Change buttons and Print My Ballot" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmarkscan-voting-printing.png" alt="VxMarkScan Printing Your Ballot screen asking the voter not to remove the ballot" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmarkscan-voting-post-print-review.png" alt="Review Your Votes screen after scanning the printed ballot, with My Ballot is Incorrect and Cast My Ballot buttons." width="375"><figcaption></figcaption></figure></div>

{% hint style="warning" %}
If the voter removes the ballot from the printer to review, the VxMarkScan will ask if they are still voting. They should reload their ballot to cast the ballot. If the ballot is not reloaded, the VxMarkScan will clear the ballot after five minutes of inactivity.
{% endhint %}

The screen will show the ballot being cast and verify it was cast and dropped into the ballot bin.

<div><figure><img src="../.gitbook/assets/vxmarkscan-voting-casting-ballot.png" alt="VxMarkScan Casting Ballot screen shown while the printed ballot is scanned and cast" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxmarkscan-voting-ballot-cast.png" alt="VxMarkScan confirmation that the voter's ballot was cast" width="375"><figcaption></figcaption></figure></div>

{% hint style="info" %}
If headphones are used, it's recommended to use earpad covers and replace then after each use. See the [Supply List](../miscellaneous/supply-list.md) for more information.
{% endhint %}

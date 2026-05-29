# Assisting Voters

## Casting Ballots

VxScan is ready to accept a new ballot whenever it displays _Insert Your Ballot:_

<figure><img src="../.gitbook/assets/insert-ballot-lang.png" alt="" width="375"><figcaption></figcaption></figure>

A voter can then push their ballot onto the tray and into the scanner. When a ballot is properly inserted, the scanner will grip the ballot. If a ballot is inserted at an angle, the scanner may push the ballot back into the voter's hands without scanning, in which case the voter should simply re-insert their ballot. VxScan will then scan the ballot by pulling it in while showing the following screen:

<figure><img src="../.gitbook/assets/please-wait.png" alt="" width="375"><figcaption></figcaption></figure>

If the ballot has no issues, the ballot will go into the ballot box and the screen will show that the ballot has been counted. Notice that the _Sheets Scanned_ count goes up.

<figure><img src="../.gitbook/assets/ballot-counted.png" alt="" width="375"><figcaption></figcaption></figure>

After a few seconds, VxScan will return to the _Insert Your Ballot_ screen in preparation for the next voter.

If the ballot was not counted because of an issue, the scanner will hold the ballot. There could be any of the following issues with the ballot depending on state law or rule.

{% include "../.gitbook/includes/instructions-on-damaged-ballots.md" %}

### Overvoted Ballots

A ballot is considered overvoted if the scanner recognizes more than the allowed number of votes for a particular race. For example, a voter marked two candidates in a race where they must make a single choice. If the voter would like to correct their error, they should select _`Return Ballot`_ and VxScan will return the ballot to the voter. If the voter would like to count the ballot as is, they should select _`Cast Ballot`_ and then confirm by selecting _`Cast Ballot`_ again. All votes will be counted in correctly voted contests but the overvoted contest will be ignored.

<figure><img src="../.gitbook/assets/overvoted-ballot.png" alt="" width="375"><figcaption></figcaption></figure>

{% hint style="info" %}
An overvote will also be detected when a candidate is marked and writing is detected on the write-in line for the same contest if it exceeds the number of allowed votes (when required by law or rule). This is true even if the bubble is not marked.
{% endhint %}

### Blank Ballots

If a state requires notification to the voter that a ballot has no selections marked, the voter will be prompted to review their ballot.

The voter may have circled or underlined the names of their choices instead of filling in the bubbles. Or the voter may have used a writing utensil whose marks are ignored by the scanner, like a highlighter. VxScan will warn the voter that their ballot appears blank.

<figure><img src="../.gitbook/assets/blank-ballot.png" alt="" width="375"><figcaption></figcaption></figure>

If the voter would like to correct their error, they should select _`Return Ballot`_ and VxScan will return the ballot to the voter. If the voter would like to count the ballot as is, they should select _`Cast Ballot`_ and then confirm by selecting _`Cast Ballot`_ again. The _Sheets Scanned count_ will increase but no votes will be counted from a blank ballot.

### Undervotes

If a state requires notification to the voter that a specific contest has fewer than the maximum selections marked, the voter will be prompted to review their ballot.

<figure><img src="../.gitbook/assets/vxscan-undervote.png" alt="" width="375"><figcaption></figcaption></figure>

If the voter would like to correct their error, they should select _`Return Ballot`_ and VxScan will return the ballot to the voter. If the voter would like to count the ballot as is, they should select _`Cast Ballot`_ and then confirm by selecting _`Cast Ballot`_ again. All votes will be counted.

### Multiple Corrections

If a voter has both undervotes and overvotes on their ballot and the state requires review of both, the _Review Your Ballot_ screen will list the number of contests with each issue. Select _`View contests`_ to see the full list of contests that were undervoted or overvoted.

<figure><img src="../.gitbook/assets/multiple-issues.png" alt="" width="375"><figcaption></figcaption></figure>

If the voter would like to correct their errors, they should select _`Return Ballot`_ and VxScan will return the ballot to the voter. If the voter would like to count the ballot as is, they should select _`Cast Ballot`_ and then confirm by selecting _`Cast Ballot`_ again.

### Adjusting Color and Size

Simple changes to the screen's color and size can be very helpful for voters with low vision and other cognitive disabilities. Selecting _`Settings`_ in the upper left hand corner of the screen provides the voter with different options. Select _`Color`_ to change the text and background color and select _`Text Size`_ to change the text size.

<div><figure><img src="../.gitbook/assets/insert-ballot-lang copy 2.png" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/color-mode.png" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/text-size-mode.png" alt=""><figcaption></figcaption></figure></div>

#### **Text and Background Color**

Four different color options are available for users. While we provide a short description of who may benefit most from these different options, please note that the user likely knows what setting is best for them.

**White text, black background** - used by a person that finds white backgrounds too bright due to visual disabilities.

**Gray text, dark background** - used by a person needing lower contrast. For example, a person with dyslexia may find the screen quieter.

**Dark text, light background** - as the default this setting will be used by most people.

**Black text, white background** - used by a person who needs the highest contrast because of light vision or color perception disabilities or aging.

#### Text Size

The default text size is _`Medium`_. A user can select _`Small`_, _`Large`_, or _`Extra-Large`_ based on their preferences. Select _`Done`_ to save the selection.

### Language

If a jurisdiction provides language options to voters, a voter may select that language by selecting _`English`_. Next, they'll select the language of their choice and select _`Done`_.

{% include "../.gitbook/includes/untitled.md" %}

{% hint style="warning" %}
All selections above are made for a specific voting session and will reset with the next voter.
{% endhint %}

### Audio-Tactile Interface

VxScan also supports ballot casting over an audio-tactile interface via an accessible controller and headphones. A poll worker does the following to enable the audio-tactile interface:

* Plug in the Personal Assistive Technology (PAT) device into the PAT jack in front in the top-left.
* Plug in the headphones into the headphone jack in front in the bottom-left.

{% hint style="warning" %}
Accessibility devices MUST be connected to VxScan before scanning a ballot, for a voter using the audio-tactile interface.
{% endhint %}

<figure><img src="../.gitbook/assets/scan_install_pat+audio-attached-front-1600x1200.jpg" alt="" width="563"><figcaption><p>PAT device and headphones plugged into the front left ports</p></figcaption></figure>

{% include "../.gitbook/includes/sanitizing-headphones-instructions.md" %}

Voters can navigate with the PAT device. When first plugging in the PAT device, a 3-step tutorial first shows up to test the device, as shown in the following screens:

<figure><img src="../.gitbook/assets/vxscan-pat-tutortial-01.png" alt="" width="375"><figcaption><p>Step 1: Activate a PAT input.</p></figcaption></figure>

<div><figure><img src="../.gitbook/assets/vxscan-pat-tutortial-02.png" alt="" width="375"><figcaption><p>Step 2: Identify the "Move" input.</p></figcaption></figure> <figure><img src="../.gitbook/assets/vxscan-pat-tutortial-03.png" alt="" width="375"><figcaption><p>Input identified</p></figcaption></figure></div>

<div><figure><img src="../.gitbook/assets/vxscan-pat-tutortial-04.png" alt="" width="375"><figcaption><p>Step 3: Identify the "Select" input.</p></figcaption></figure> <figure><img src="../.gitbook/assets/vxscan-pat-tutortial-05.png" alt="" width="375"><figcaption><p>Input identified</p></figcaption></figure></div>

<figure><img src="../.gitbook/assets/vxscan-pat-tutortial-06.png" alt="" width="375"><figcaption><p>PAT setup complete</p></figcaption></figure>

Voters can adjust the volume using the volume control interface in the _`Settings`_ menu. Audio settings can be modified by clicking the _`Settings`_ button in the top header and finding options under the _`Audio`_ tab, as shown in the screen below.

<figure><img src="../.gitbook/assets/vxscan-headphone-audio-settings.png" alt="" width="375"><figcaption></figcaption></figure>

Voters using the PAT device to cast a ballot use two commands to perform this task. First, the Move command allows voters to navigate through the focusable items within the page. Second, the Select command allows a voter to select an item in the page.\
\
The Move command provides both Skip and Pause functionality for the audio playback.  Using the Move command to navigate to the next focusable element in the page allows the user to Skip the audio being played.  To Pause the audio playback, the voter uses the Move command which moves to the next focusable element in the page.  By cycling through all focusable elements in the page using the Move command and returning to the element at which the audio was Paused or Skipped, the Voter is able to both Resume or Repeat audio playback for that element.

{% hint style="info" %}
The instructions provided above for using a PAT device to cast a ballot, enable both voters and a jurisdiction to perform these tasks.
{% endhint %}

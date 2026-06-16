# Additional VxScan Settings

## Early Voting Mode

Before using VxScan for early voting, an election should put it into Early Voting mode.

<figure><img src="../.gitbook/assets/image (22).png" alt="" width="375"><figcaption></figcaption></figure>

While in early voting mode, an "Early Voting" status will always be displayed on the bottom of the screen.

<div><figure><img src="../.gitbook/assets/early-voting-001-unauthenticated-early-voting.png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/early-voting-002-insert-ballot-early-voting.png" alt="" width="375"><figcaption></figcaption></figure></div>

The default action for poll workers in early voting mode is `Pause Voting` rather than `Close Polls`. Poll workers should `Pause Voting` at the end of each voting day and `Resume Voting` at the beginning of each voting day.

<figure><img src="../.gitbook/assets/image (23).png" alt="" width="375"><figcaption></figcaption></figure>

## Saving CVRs

The cast vote records contain the images and the interpretation for each ballot cast and is used to tally votes in VxAdmin. The cast vote record saves continuously to the USB drive throughout the day and again at the close of polls. If another copy is needed, however, it can also be saved by selecting `CVRs and Logs` from the side menu and selecting `Save CVRs`.

<figure><img src="../.gitbook/assets/image (7).png" alt="" width="375"><figcaption></figcaption></figure>

The `Pause Continuous CVR Export` feature is used to disable continuous cast vote record export in the case that a USB drive fails or is unavailable. When continuous export is paused, VxScan can be used without an inserted USB drive and CVRs must be manually exported from the election manager menu after polls are closed. If you experience USB drive issues, contact customer support. This setting should only be used if advised by the VotingWorks support team.

## Saving Logs

The logs contain information about the regular operation of the hardware and software and also any error messages. Both election managers and system administrators can export logs by selecting `Save Logs` .

<div><figure><img src="../.gitbook/assets/configuration-017-em-save-logs-button.png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/configuration-031-sa-save-logs-button.png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/configuration-018-em-save-logs-modal (1).png" alt="" width="375"><figcaption></figcaption></figure></div>

## Setting Date & Time

The time on VxScan should stay mostly accurate, including automatically adjusting for daylight savings time, but can drift slightly over time. Both election managers and system administrators can update the time by selecting `Set Date and Time`.

<div><figure><img src="../.gitbook/assets/configuration-019-em-set-date-time.png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/configuration-029-sa-set-date-time.png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/configuration-020-em-set-date-time-modal (1).png" alt="" width="375"><figcaption></figcaption></figure></div>

## Muting Sounds

{% hint style="info" %}
The following step can only be completed by an election manager.
{% endhint %}

VxScan makes sounds every time a ballot is accepted or rejected. Sounds can be muted and unmuted by an election manager.

<figure><img src="../.gitbook/assets/image (9).png" alt="" width="375"><figcaption></figcaption></figure>

## Resetting Polls to Paused

{% hint style="info" %}
The following step can only be completed by a system administrator.
{% endhint %}

If polls have been closed accidentally by a poll worker, a system administrator may reset the polls to paused, after which a poll worker can resume voting.

<figure><img src="../.gitbook/assets/image (8).png" alt="" width="375"><figcaption></figcaption></figure>

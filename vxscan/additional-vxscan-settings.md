# Additional VxScan Settings

## Saving CVRs

The cast vote records contain the images and the interpretation for each ballot cast and is used to tally votes in VxAdmin. The cast vote record saves continuously to the USB drive throughout the day and again at the close of polls.  If another copy is needed, however, it can also be saved by selecting _`CVRs and Logs`_ from the side menu and selecting _`Save CVRs`_.

<figure><img src="../.gitbook/assets/cvrs-and-logs-cvrs.png" alt="" width="375"><figcaption></figcaption></figure>

The _`Pause Continuous CVR Export`_ feature is used to disable continuous cast vote record export in the case that a USB drive fails or is unavailable. When continuous export is paused, VxScan can be used without an inserted USB drive and CVRs must be manually exported from the election manager menu after polls are closed. If you experience USB drive issues, contact customer support. This setting should only be used if advised by the VotingWorks support team.

## Saving Logs

The logs contain information about the regular operation of the hardware and software and also any error messages. Both election managers and system administrators can export logs by selecting _`Save Logs`_ .

<div><figure><img src="../.gitbook/assets/cvrs-and-logs-logs.png" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxscan-sys-admin-save-logs (1).png" alt=""><figcaption></figcaption></figure></div>

## Setting Date & Time

The time on VxScan should stay mostly accurate, including automatically adjusting for daylight savings time, but can drift slightly over time. Both election managers and system administrators can update the time by selecting _`Set Date and Time`_.

<div><figure><img src="../.gitbook/assets/more-screen-date-time-2.png" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxscan-sys-admin-set-date-and-time (1).png" alt=""><figcaption></figcaption></figure></div>

## Muting Sounds

{% hint style="info" %}
The following step can only be completed by an election manager.
{% endhint %}

VxScan makes sounds every time a ballot is accepted or rejected. Sounds can be muted and unmuted by an election manager.

<figure><img src="../.gitbook/assets/more-screen-sounds.png" alt="" width="375"><figcaption></figcaption></figure>

## Resetting Polls to Paused

{% hint style="info" %}
The following step can only be completed by a system administrator.
{% endhint %}

If polls have been closed accidentally by a poll worker, a system administrator may reset the polls to a paused, after which a poll worker can resume voting.

<figure><img src="../.gitbook/assets/vxscan-sys-admin-reset-polls-to-paused (1).png" alt="" width="375"><figcaption></figcaption></figure>

## Calibrating Image Sensors

{% hint style="info" %}
The following step can only be completed by a system administrator.
{% endhint %}

Under exceedingly rare circumstances, one may need to calibrate the scanner's image sensors with a blank white sheet of paper to ensure proper conversion from physical paper to digital image.

Machines are shipped with this calibration having already been completed by the part manufacturer, so this calibration does not need to be performed with any regularity and in fact may never need to be performed at all over the lifetime of the scanner. It should only be performed during L\&A if ballots consistently fail to scan with generic errors unrelated to election configuration, all other reasons for failure (e.g., ballots not printed to spec) have been ruled out, and VotingWorks support has suggested this as a course of action.

<figure><img src="../.gitbook/assets/vxscan-sys-admin-calibrate-image-sensors.png" alt="" width="375"><figcaption></figcaption></figure>

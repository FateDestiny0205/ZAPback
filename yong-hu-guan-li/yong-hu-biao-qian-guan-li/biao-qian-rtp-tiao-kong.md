---
icon: joystick
---

# Tag RTP control

**1. Function description**

The function of RTP control for specific types of users through user tags

**2. Filtering and query functions**

<figure><img src="../../.gitbook/assets/image (177).png" alt=""><figcaption></figcaption></figure>

Filter by country and carrier

**3.List fields**

(1) ID: Control ID

(2) Operator: Belonging to the operator

(3) User tag: single/multiple user tags corresponding to this control

(4) Bonus RTP control value (kill rate control): This control value acts on the kill rate bonus set in the "Coding General Configuration". For example: If the winnings kill rate for an event is 50%, then 50% of the winnings received by players will be subject to the "kill rate regulation RTP" limit. If not configured → no regulation. If there are multiple rules and overlap → use the lowest RTP value for control.![](file:///C:/Users/Administrator/AppData/Local/Temp/msohtmlclip1/01/clip_image004.jpg)![](file:///C:/Users/Administrator/AppData/Local/Temp/msohtmlclip1/01/clip_image006.jpg)

<figure><img src="../../.gitbook/assets/image (178).png" alt=""><figcaption></figcaption></figure>

<div align="left"><figure><img src="../../.gitbook/assets/image (180).png" alt="" width="375"><figcaption></figcaption></figure></div>

(5) Bonus RTP control value (non-kill rate control): This control value acts on the non-kill rate bonus part in the "Coding General Configuration". Control sequence: Kill rate control is implemented first; the remaining bonus is then limited by the "non-kill rate control RTP". Special case: If "kill rate control" is not configured, but "non-kill rate control" is configured → all winnings will be executed according to "non-kill rate control RTP".

(6) The highest multiplier of the game: that is, the highest multiplier of the player’s bonus during the execution of the regulation.

(7) Status: the switch status of the control

(8) Operator: the operator of this control

(9) Operation time: the operation time of this control

(10) Operation: Edit or delete this control

a. Operator: Belonging to the operator

b. User label: single/multiple user labels corresponding to this control

c.RTP kill rate control: This control value acts on the kill rate bonus set in the "Coding General Configuration". For example: If the winnings kill rate for an event is 50%, then 50% of the winnings received by players will be subject to the "kill rate regulation RTP" limit. If not configured → no regulation. If there are multiple rules and overlap → use the lowest RTP value for control.

d.RTP non-kill rate control: This control value acts on the non-kill rate bonus part of the "Coding General Configuration". Control sequence: Kill rate control is implemented first; the remaining bonus is then limited by the "non-kill rate control RTP". Special case: If "kill rate control" is not configured, but "non-kill rate control" is configured → all winnings will be executed according to "non-kill rate control RTP".

e. The highest multiplier of the game: that is, the highest multiplier of the player’s bonus during the execution of the regulation.

f. Status: the switch status of the control

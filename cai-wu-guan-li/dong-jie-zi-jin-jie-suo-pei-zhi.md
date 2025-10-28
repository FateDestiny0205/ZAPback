---
icon: drum
---

# Frozen funds unlock configuration

**1. Interface location**

* The path in the left navigation bar: Financial Management → Recharge Management → Frozen Funds Unlock Configuration.
* Function description: Used to set the user’s frozen funds unlocking settings.

<figure><img src="../.gitbook/assets/image (223).png" alt=""><figcaption></figcaption></figure>

**2.Field description**

* There are three types of unlocking frozen funds: recharge unlocking, login unlocking, and direct subordinate recharge unlocking.
* Recharge and unfreeze frozen amount coefficient (%): The amount that the user can unlock after each recharge. Enter 1 to represent the coefficient as 1%.

Calculation method: Unlock amount = User recharge amount \* Unlock frozen amount coefficient

The player's frozen amount is 100, recharge is 50, and the unlocking coefficient is 50%, then the unlocking amount = 50 \* 50% = 25

* Recharge to unlock the frozen amount and add a new code multiplier: The user unlocks the frozen amount and adds a new withdrawal code amount. Enter 1 for 1x.

Calculation method: New withdrawal code amount = user recharge amount \* Unlock frozen amount coefficient

The user’s original withdrawal code is 1,000, the recharge unlocking amount is 50, and the code multiplier is 2. After the unlocking is successful, the withdrawal code is 1,100.

* Login unlocking frozen amount cycle: The cycle setting for user login unlocking, which can be daily or weekly.
* Number of times a user logs in to unlock the frozen amount during the cycle: During the cycle, the number of times the user manually unlocks the frozen amount on the front-end interface.
* Login to unlock the frozen amount range: Set the user login to unlock the frozen amount range, the minimum-maximum amount that can be unlocked.
* Percentage of frozen amount unlocked by login (%): Percentage of frozen amount unlocked by user login. Enter 1 to represent the coefficient of 1%.
* The new code multiplier for the frozen amount unlocked by logging in: the new withdrawal code multiplier for the user's unlocked amount after logging in.
* Coefficient for unlocking the frozen amount when recharging by direct subordinates (%): The coefficient for unlocking the frozen amount by the user's direct subordinates when recharging by direct subordinates, but the direct subordinates themselves cannot have frozen amounts.
* A new coding multiplier will be added to the frozen amount unlocked by direct subordinates' recharge: A new coding multiplier will be added to the frozen amount unlocked by direct subordinates' recharge.

**Front-end interface:**

<div align="left"><figure><img src="../.gitbook/assets/image (224).png" alt="" width="224"><figcaption></figcaption></figure></div>

<div align="left"><figure><img src="../.gitbook/assets/image (225).png" alt="" width="220"><figcaption></figcaption></figure></div>

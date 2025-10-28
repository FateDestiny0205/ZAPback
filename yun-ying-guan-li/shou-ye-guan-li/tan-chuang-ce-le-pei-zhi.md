---
icon: display
---

# Pop-up policy configuration

**1. Function description**

Configure pop-up policies for pop-up windows. Different pop-up policies can be configured for users with different labels.

**2. Filtering and query functions**

<figure><img src="../../.gitbook/assets/image (49).png" alt=""><figcaption></figcaption></figure>

2.1 Operator

Select a certain operator’s pop-up strategy to query

2.2 Strategy status

Is the policy on or off, or all of them?

2.3 Pop-up link

Is the pop-up window a single link, multiple links, or all?

<table data-header-hidden><thead><tr><th valign="top"></th><th valign="top"></th><th valign="top"></th><th valign="top"></th></tr></thead><tbody><tr><td valign="top">Link mode</td><td valign="top">Meaning</td><td valign="top">Pop-up window logical structure</td><td valign="top">Typical uses</td></tr><tr><td valign="top">Single link</td><td valign="top">A fixed path</td><td valign="top">A → B → C</td><td valign="top">Fixed process prompts and guidance</td></tr><tr><td valign="top">Multiple links</td><td valign="top">Multiple conditional branch paths</td><td valign="top">A → (B/C/D)</td><td valign="top">Display different pop-up windows according to different behaviors</td></tr></tbody></table>

**3.List fields**

(1) ID: pop-up policy ID

(2) Operator: Belonging to the operator

(3) Strategy title: the title of the pop-up window strategy

(4) User label: the user label targeted by the policy

(5) Strategy weight: If there are duplicate tags and multiple pop-up window policy triggering conditions are met at the same time, the one with the highest trigger weight will be used.

(6) Sorting: Sorting of background pop-up window strategies

(7) Pop-up link type: single link or multiple links

(8) Pop-up link details: specific link trigger details

<div align="left"><figure><img src="../../.gitbook/assets/image (50).png" alt="" width="254"><figcaption></figcaption></figure></div>

(9) Status: current switch status

(10) Operation: Edit and delete the current pop-up window strategy

**4.New strategy**

<div align="left"><figure><img src="../../.gitbook/assets/image (54).png" alt="" width="77"><figcaption></figcaption></figure></div>

Click the Add Strategy button to add a new strategy

<div align="left"><figure><img src="../../.gitbook/assets/image (55).png" alt="" width="328"><figcaption></figcaption></figure></div>

1. Operator: Belonging to the operator

2. Strategy sorting: sorting of pop-up strategies in the background list

3. User tags: Which user tags the pop-up policy is effective for, single/multiple selections possible

4. Strategy title: the title of the pop-up window strategy

5. Strategy weight: the weight of the pop-up strategy. When multiple pop-up strategy triggering conditions are met at the same time, the one with the highest trigger weight will be used.

6. Policy status: the open or closed status of the pop-up window policy

7. Policy path: Configure specific pop-up window strategies

(1) Single pop-up window settings

<figure><img src="../../.gitbook/assets/image (56).png" alt=""><figcaption></figcaption></figure>

a. Associate the first pop-up window ID: which pop-up window in the pop-up window configuration is associated with it

b. Current pop-up window display position: On which page the pop-up window pops up

c. The number of daily impressions of the first pop-up window: the number of impressions of the first pop-up window. If the number has reached the configured value, the next pop-up window logic will be executed.

d. Pop up when you start the app: Whether to pop up when you start the app. Pop up when you start the app will also be included in the number of daily impressions of the first pop-up window.

(2) New pop-up window

<div align="left"><figure><img src="../../.gitbook/assets/image (57).png" alt="" width="81"><figcaption></figcaption></figure></div>

Click the Add Next Pop-up Window button to set the logic of the next pop-up window.

<div align="left"><figure><img src="../../.gitbook/assets/image (58).png" alt="" width="289"><figcaption></figcaption></figure></div>

<div align="left"><figure><img src="../../.gitbook/assets/image (59).png" alt="" width="375"><figcaption></figcaption></figure></div>

<table data-header-hidden><thead><tr><th valign="top"></th><th valign="top"></th><th valign="top"></th><th valign="top"></th></tr></thead><tbody><tr><td valign="top">Link mode</td><td valign="top">Meaning</td><td valign="top">Pop-up window logical structure</td><td valign="top">Typical uses</td></tr><tr><td valign="top">Single link</td><td valign="top">A fixed path</td><td valign="top">A → B → C</td><td valign="top">Fixed process prompts and guidance</td></tr><tr><td valign="top">Multiple links</td><td valign="top">Multiple conditional branch paths</td><td valign="top">A → (B/C/D)</td><td valign="top">Display different pop-up windows according to different behaviors</td></tr></tbody></table>

(3) Second and subsequent pop-up window settings

<figure><img src="../../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

a. The second pop-up window display condition: participation in the last pop-up window activity, the number of times the last pop-up window was closed (the specific number of times needs to be configured later), or the number of times the last pop-up window popped up (the specific number of times needs to be configured later)

<div align="left"><figure><img src="../../.gitbook/assets/image (61).png" alt="" width="252"><figcaption></figcaption></figure></div>

<div align="left"><figure><img src="../../.gitbook/assets/image (62).png" alt="" width="375"><figcaption></figcaption></figure></div>

<div align="left"><figure><img src="../../.gitbook/assets/image (63).png" alt="" width="375"><figcaption></figcaption></figure></div>

b. Associate the second pop-up window ID: Which pop-up window in the pop-up window configuration is associated with it?

c. Current pop-up window display position: On which page the pop-up window pops up

d. The number of daily impressions of the second pop-up window: the number of impressions of the first pop-up window. If the number has reached the configured value, the next pop-up window logic will be executed.

e. Time interval with the previous pop-up window: N seconds after closing the previous pop-up window, execute the next pop-up window display logic

(4) Delete the current pop-up window

<div align="left"><figure><img src="../../.gitbook/assets/image (64).png" alt="" width="85"><figcaption></figcaption></figure></div>

Click to delete the current pop-up window to delete the current pop-up window

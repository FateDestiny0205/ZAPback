---
icon: file-user
---

# Account management

**1. Interface location**

* The path in the left navigation bar: Account Management → Account Management.
* Function description: Used to create, edit and delete merchant backend login accounts.

<figure><img src="../.gitbook/assets/image (236).png" alt=""><figcaption></figcaption></figure>

**2. Filter conditions**

* Operator: Select the operator to be queried.
* Account type: Supports query based on operator account type, type classification: main account, sub-account.
* Account type: Supports query based on operator account type, type classification: administrator, operator, channel.
* Account: Supports query based on operator account.
* Creation time: Supports querying based on operator account creation time.
* Reset: Clear all filters.
* Query: Retrieve data based on filter conditions.

**3. Form field description**

* Operator: The operator to which the account belongs.
* Account Nickname: Account nickname.
* Account: Operator account.
* Role name: Account role permissions.
* Account type: Operator account type.
* Status: Operator account status.
* Locked status: When the lock is turned on, other accounts cannot operate the account information.
* Creation time: Merchant creation time.
* Login time: The last login time of the merchant.
* Operation->Edit: Click to open the edit operator account panel.
* Operation->Delete: Click to open the secondary confirmation deletion panel. Click the delete button to delete this piece of data.

**4. Add/edit operator account panel function description**

* Account type: Set the account type.
* Operator: Set the operator for account operation. When the account type is administrator, you can select multiple options. When the account type is operator, you can only select a single option.
* Account: Set the background login account.
* Account nickname: Set the background account nickname.
* Email: The email account associated with the account can be deleted.
* Password: Set the background login password.
* Role: Set account permission roles.
* Select a promoter: When the account type is an operator, set the promoter of the backend account. Value source: channel management/channel account
* Google verification code: After turning it on, you need to enter the Google verification code to log in to the merchant backend.
* Login IP whitelist: Set the IP whitelist for background login. Multiple IPs can be entered, separated by commas.

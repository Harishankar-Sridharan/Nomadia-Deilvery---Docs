# Secure API Key Management

Secure API key management lets administrators create, expire and revoke the API keys used by your integrations. You can create one key per integration, give each key an optional expiration date, and disable or delete a key instantly without disrupting your other integrations. Each key is shown in full only once, when you create it.

## Before you begin

* Sign in to **Nomadia Delivery** as an administrator with access to **Configuration**.
* Decide which integration each key is for, so that you can name and describe it.

## Feature overview

* **API keys page**: The page under **Configuration** that lists your API keys with their name, description, masked key, enabled state and expiration date.
* **Legacy API key**: The API key you used before secure keys. A warning reminds you to create new secure keys and migrate your integrations. The legacy key keeps working until you delete it.
* **Name** and **Description**: The name and description of a key, so that you can tell which integration uses it.
* **Expiration date**: An optional date after which the key stops working.
* **API key created**: The pop-up that shows the new key in full, only once.
* **Enabled**: The switch that enables or disables a key. A disabled key is refused instantly.

## Create an API key

1. Go to **Configuration** > **API keys**.

![The API keys page](.gitbook/assets/ApiKeys_001.jpg)

2. Click **Actions**, and then click **Add**.

![Click Actions and then Add](.gitbook/assets/ApiKeys_002.jpg)

3. Enter a **Name** and a **Description** for the key.

![Enter the name and description of the key](.gitbook/assets/ApiKeys_003.jpg)

4. Optional: Choose an **Expiration date**.

![Choose an optional expiration date](.gitbook/assets/ApiKeys_004.jpg)

5. Click **Save**.

![Click Save](.gitbook/assets/ApiKeys_005.jpg)

6. In the **API key created** pop-up, click **Copy** to copy the key, and then click **Close**.

![The API key created pop-up](.gitbook/assets/ApiKeys_006.jpg)

### Result

The key is added to the list. Only its last characters stay visible in the **Key** column.

![The new key with its masked value](.gitbook/assets/ApiKeys_007.jpg)

To connect several integrations, repeat these steps and create one key per integration.

![Several keys, one per integration](.gitbook/assets/ApiKeys_008.jpg)

## Disable an API key

1. In the list of API keys, click the **pencil icon** next to the key.

![The Edit an API key page](.gitbook/assets/ApiKeys_009.jpg)

2. Turn off the **Enabled** switch so that it shows **No**.

![Turn off the Enabled switch](.gitbook/assets/ApiKeys_010.jpg)

3. Click **Save**.

### Result

A notification confirms that the key was saved, and the **Enabled** column shows **No**. Requests that use this key are refused instantly.

![The disabled key in the list](.gitbook/assets/ApiKeys_011.jpg)

## Delete API keys

1. In the list of API keys, select the check boxes of the keys you want to delete.

![Select the keys to delete](.gitbook/assets/ApiKeys_012.jpg)

2. Click **Actions**, and then click **Delete**.
3. In the **Delete API key** pop-up, click **Yes**. The keys stop working immediately.

![The Delete API key pop-up](.gitbook/assets/ApiKeys_013.jpg)

### Result

The keys are removed from the list. Your other integrations keep running with their own keys.

![The remaining keys after the deletion](.gitbook/assets/ApiKeys_014.jpg)

## Tips

{% hint style="warning" %}
**Copy the key when you create it**: The key is shown in full only once and can never be retrieved again. If you lose it, delete the key and create a new one.
{% endhint %}

{% hint style="info" %}
**Migrate from the legacy key**: Create new secure keys, update your integrations, and then delete the legacy API key with its **Delete** button. The legacy key keeps working until you do.
{% endhint %}

## Related topics

* [Import Missions](8-6-missions/import-missions/README.md)
* [Control Address Sharing with Contractors](control-address-sharing-with-contractors.md)

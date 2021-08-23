# V5: Payment Cards

## Control Objective

Category “V5” lists requirements related to the payment cards management in the mobile financial applications.

## Security Features Verification Requirements

| # | Description |
| --- | --- |
| **5.1** | Allow users to temporarily and reversibly lock their payment cards. | 
| **5.2** | Allow users to enable and disable payment card integration with Google Pay and Apple Pay. Do not implement HCE on your own. | 
| **5.3** | Implement PIN change functionality from the mobile application level. |
| **5.4** | Mobile Application should let the user to configure which payment options are allowed (internet, contactless. magnetic, abroad etc.). |
| **5.5** | Payment card number should be considered as sensitive data, and should not be fully visible in the application UI without additional authorization. |
| **5.6** | Introduce virtual payment cards, which can be used only for single internet transactions. |

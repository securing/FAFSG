# V2: Authorization

## Control Objective

Category “V2” lists security features related to the authorization mechanisms in the mobile financial applications. 

## Security Features Verification Requirements

| # | Description |
| --- | --- |
| **2.1** | Each authorization message should contain details about authorized operation. For instance, for the new transaction, the authorization message should contain the operation date, amount and the destination account. | 
| **2.2** | Ensure that authorization method is different from authentication - for instance use PIN for authentication and biometry for authorization, or use different PIN codes. |
| **2.3** | Ensure that any change to authorization method requires authorization with the previously used channel.  | 
| **2.4** | Do not use authorization with SMS codes because of the risk of SIM-swapping attacks and MiTM on GSM protocols. |
| **2.5** | Encourage PUSH-alike authorization as it is considered the most secure. | 
| **2.6** | Each security sensitive operation, such as transaction, adding a trusted account or any user account changes should require authorization. | 
| **2.7** | User interface should list previous and current authorization requests and their results. | 

## References

For more information, see also:

* [OWASP Authorization Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Authorization_Cheat_Sheet.html)
* [CWE 285 (Improper Authorization)](https://cwe.mitre.org/data/definitions/285.html)


# V2: Authorization

## Control Objective

Category “V2” lists security features related to the authorization mechanisms in the financial applications. 

## Security Features Verification Requirements

| # | Description |
| --- | --- |
| **2.1** | Each authorization message should contain details about the authorized operation. For instance, for a new transaction, the authorization message should contain the operation date, amount and the beneficiary account (to protect against man-in-the-browser malware). | 
| **2.2** | Allow users to choose from multiple authorization channels (PUSH, SMS OTP, email OTP), according to their preferences.  | 
| **2.3** | Ensure that any change to authorization method requires authorization with the previously used channel.  |
| **2.4** | Encourage PUSH authorization as it is considered most secure.   | 
| **2.5** | In case of OTP, code must be unique, random and at least 6 character long. OTP codes shoud also be protected against brute-force attacks with request throttling. | 
| **2.6** | OTP codes should be protected against brute-force attacks with request throttling. | 
| **2.7** | Each security sensitive operation, such as transaction, adding trusted account or any user account changes should require authorization. | 
| **2.8** | User interface should list previous and current authorization requests and their results. | 

## References

For more information, see also:

* [OWASP Authorization Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Authorization_Cheat_Sheet.html)
* [CWE 285 (Improper Authorization)](https://cwe.mitre.org/data/definitions/285.html)

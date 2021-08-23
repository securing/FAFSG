# V1: Authentication

## Control Objective

Category “V1” lists security features related to authentication mechanism in the financial applications. 

## Security Features Verification Requirements

| # | Description |
| --- | --- |
| **1.1** | Enable two factor authentication (for instance, login/password and trusted browser or mobile confirmation). | 
| **1.2** | Do not use authentication with a masked password. | 
| **1.3** | Encourage or enforce users to use 2FA (gamification / reward  is a plus). |
| **1.4** | Ensure that user enumeration is not possible. Application should respond in exactly the same way and with the same delay in all authorization scenarios.| 
| **1.5** | Verify if the authorization message (PUSH, SMS or email) contains detailed information regarding authorized operation. In case of a trusted browser, authorization messages should contain its location, name etc.| 
| **1.6** | Allow users to choose whether they want to authorize only single access or save browser as trusted. Remember that for [PSD2](https://ec.europa.eu/info/law/payment-services-psd-2-directive-eu-2015-2366_en) compliant applications, 2FA should be repeated in less than 90 days. | 

## References

For more information, see also:

* [OWASP ASVS V2 Authentication](https://github.com/OWASP/ASVS/blob/master/4.0/en/0x11-V2-Authentication.md)
* [CWE 287 (Improper Authentication)](https://cwe.mitre.org/data/definitions/287.html)


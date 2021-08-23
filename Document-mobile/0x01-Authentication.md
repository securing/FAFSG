# V1: Authentication

## Control Objective

Category “V1” lists security features related to authentication mechanism in the mobile financial applications. 

## Security Features Verification Requirements

| # | Description |
| --- | --- |
| **1.1** | Implement application pairing - when implemented, the unique and random application instance identifier can be treated as a second factor in user authorization alongside knowledge of PIN code. Instance identifier should be stored in dedicated, encrypted storge. | 
| **1.2** | Use additional data to pair an application, for example QR code from an authorized web session. | 
| **1.3** | Ensure that user enumeration is not possible. Application should respond in exactly the same way and with the same delay in cases of providing valid username with invalid password, and invalid username - both for pairing and authorization. |
| **1.4** | Use different authentication methods for web and mobile applications. Avoid situations when users can login both to web and mobile with exactly the same credentials. Password for web and PIN or biometrics for mobile is a good solution.   | 

## References

For more information, see also:

* [OWASP MASVS V4 Authentication and Session Management](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x09-V4-Authentication_and_Session_Management_Requirements.md)
* [CWE 287 (Improper Authentication)](https://cwe.mitre.org/data/definitions/287.html)


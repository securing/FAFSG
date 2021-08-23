# V4: Credentials Quality

## Control Objective

Category “V4” lists requirements related to the credentials quality in the mobile financial applications.

## Security Features Verification Requirements

| # | Description |
| --- | --- |
| **4.1** | Password change should require the old password/PIN, the new one and 2-FA  authorization.  | 
| **4.2** | Do not accept short passwords (shorter than 12 characters) and short PINs (shorter than 6 digits). | 
| **4.3** | If you limit password length, enforce users to use at least one character, one special sign and one number. In case of PINs, block using incremental numbers (i.e. 1234) oraz just repetition of one number (i.e. 1111). |

## References

For more information, see also:

* [OWASP Web Application Security Testing 4.1](https://owasp.org/www-project-web-security-testing-guide/v41/4-Web_Application_Security_Testing/04-Authentication_Testing/README.html)
* [CWE 521 (Weak Password Requirements)](https://cwe.mitre.org/data/definitions/521.html)

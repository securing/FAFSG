# Financial Applications Features Security Guidelines - web edition

## Author

Łukasz Bobrek (lukasz.bobrek@securing.pl)

## Introduction

Financial Applications Features Security Guidelines (FAFSG) for web applications is a FREE checklist created to provide guidelines on the security features which you can implement to make your mobile app more secure. It is meant for continuous development as well as use in current application improvements.

Keep in mind that FAFSG is not a technical standard, it does not cover implementation guildelines and quality of the proposed features. For such guidelines, please refer to [___OWASP ASVS___](https://github.com/OWASP/ASVS).

**Objectives**

The goal of FAFSG is to help to make security decisions for developers, architects, reviewers and vendors in order to implement essential security features in financial applications. Those features would help to protect users data and increase overall security of the application. 

**Use cases**

You can use the FAFSG checklist in multiple ways:
- As a starting point for application design phase.
- As a measure of application security and maturity.
- As a formal security features list for third parties developing the application for you.
- To point areas which need further development in regards to security.

The entire checklist is in a form similar to OWASP APPLICATION SECURITY VERIFICATION STANDARD v4.0.
Every category has a brief description of the control objectives and a list of security features verification requirements.

[___Download FASVS PDF version___](../FAFSG_2021_ver1.pdf)

**Key areas that have been included:**

**Web applications**
* [V1: Authentication](0x01-Authentication.md)
* [V2: Authorization](0x01-Authentication.md)
* [V3: Session Management](0x02-Authorization.md)
* [V4: Credentials quality](0x04-Credentials-quality.md)
* [V5: Payment cards](0x05-Payment-cards.md)
* [V6: Limits](0x06-Limits.md)
* [V7: Notifications](0x07-Notifications.md)
* [V7: Contact](0x08-Contact.md)

**License:**
This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License.  To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

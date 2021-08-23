# V9: Mobile platform

## Control Objective

Category “V9” lists security features specific for financial applications dedicated for mobile platforms.

## Security Features Verification Requirements

| # | Description |
| --- | --- |
| **9.1** | Implement root/jailbreak detection. | 
| **9.2** | Implement anti-tampering checks accordingly (check for debuggers, instrumentation tools, memory tampering etc.) | 
| **9.3** | On Android, additionally implement vendor and integrity verification. On iOS, use DevieceCheck and  AppAttest mechanisms.  | 
| **9.4** | Use certificate pinning mechanism in order to protect communication between mobile device and the server. | 
| **9.5** | To protect sensitive data, override application snapshots from views with sensitive data. | 
| **9.6** | Implement a dedicated keyboard for sensitive data fields input, like PIN or passwords. | 
| **9.7** | Obfuscate source code in order to make reverse engineering harder. | 
| **9.8** | Use external libraries visely - introduce libraries verification and updating policy.| 

## References

For more information, see also:

* [OWASP MASVS V8 Resiliency Against Reverse Engineering ](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x15-V8-Resiliency_Against_Reverse_Engineering_Requirements.md)
* [OWASP MSTG](https://github.com/OWASP/owasp-mstg)

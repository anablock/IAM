# IAM
* [Vendors](#vendors)
    * [SailPoint](#sailpoint)
    * [Salesforce](#salesforce)
        * [Salesforce Shield Platform](#salesforce-shield-platform)
            * [Shield Implementation](#shield-implementation)

# Vendors

## SailPoint
* [SailPoint](https://www.sailpoint.com/)

## Salesforce Shield Platform
* [Salesforce Shield Platform Encryption Implementation Guide](http://resources.docs.salesforce.com/sfdc/pdf/salesforce_platform_encryption_implementation_guide.pdf)
* [Shield Platform Encryption Architecture](https://c1.sfdcstatic.com/content/dam/web/en_us/www/documents/reports/wp-platform-encryption-architecture.pdf)
* [Salesforce Security Basics](https://help.salesforce.com/articleView?id=overview_security.htm&type=5)

### Salesforce Shield Implementation
<<<<<<< HEAD
1. Assign Permissions and Create a Tenant Secret
    * Customize Application and Manage Encryption Keys permissions
=======

### Key Hygiene: Management Best Practices
frequently updating tenant secrets reduces the likelihood that malicious third parties can brute-force their way into your org
>>>>>>> a349d6165a107d173a938bb6d2e63a8836fed501
Generating a new tenant secret and archiving the old one is called key rotation, because your new tenant secret generates new encryption keys.

Archived tenant secrets can’t encrypt new data, but the app uses these archived keys to decrypt the data that was previously encrypted with it.

* [Fields which can be Encrypted](https://help.salesforce.com/articleView?id=security_pe_encrypt.htm&type=5)
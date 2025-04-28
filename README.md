# Related Website Set for T&C Appliance & HVAC Repair

This repository contains the **Related Website Set (RWS)** configuration for **T&C Appliance & HVAC Repair**. This setup supports Google's third-party cookie phaseout by declaring which domains are owned and related, allowing them to maintain shared cookie functionality where needed.

---

## 🔒 Purpose

Google Chrome's Privacy Sandbox introduces **Related Website Sets (RWS)** to help site owners maintain functionality across multiple owned domains — like logins, sessions, and analytics — after third-party cookies are deprecated.

This configuration allows our two related business domains to be recognized as a single set for cookie handling purposes.

For more information on Related Website Sets, visit:  
👉 [Google Chrome’s Related Website Sets Documentation](https://developer.chrome.com/docs/privacy-sandbox/related-website-sets/)

---

## 🌐 Related Website Set Configuration

```json
{
  "owner": "https://www.tcappliancehvac.com",
  "primary": "https://www.tcappliancehvac.com",
  "associatedSites": [
    "https://www.tcappliancerepairman.com"
  ],
  "service": [],
  "comment": "Related Website Set for T&C Appliance & HVAC Repair"
}

 How This Works
This Related Website Set file supports the recognition of the following domains as part of the same "site" group:

Primary domain: https://tcappliancehvac.com

Associated domain: https://tcappliancerepairman.com

The RWS feature helps ensure consistent cookie behavior between these sites as third-party cookie restrictions increase.

If you are looking to test or learn more about how Related Website Sets work, refer to Google’s official documentation:
👉 Google Chrome’s Related Website Sets Documentation

 Note: This configuration is specific to T&C Appliance & HVAC Repair and applies only to the domains we own.
Do not reuse this file or configuration for other sites unless you control those domains and fully understand the Related Website Set requirements.

 Disclaimer
This repository is provided for informational and compliance purposes only.
The Related Website Set configuration in this repo is intended for use by T&C Appliance & HVAC Repair.
Misuse or unauthorized reproduction of this file is not allowed.

For questions regarding this configuration, please contact the domain owner.


💡 Notes
All domains must use HTTPS.

Only domain origins (not individual pages or paths) are included.

The current configuration does not include any subdomains or CDNs, as the blog and images are hosted directly on the main domains.

Maintained by
Chandra Brown — T&C Appliance & HVAC Repair
🌐 https://www.tcappliancehvac.com
📧 contact: tcappliancehvac@gmail.com


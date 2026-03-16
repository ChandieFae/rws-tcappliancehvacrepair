# Related Website Set for T&C Appliance/HVAC Repair

This repository contains the **Related Website Set (RWS)** configuration for **T&C Appliance/HVAC Repair**. This setup supports Google's third-party cookie phaseout by declaring which domains are owned and related, allowing them to maintain shared cookie functionality where needed.

---

## Purpose

Google Chrome's Privacy Sandbox introduces **Related Website Sets (RWS)** to help site owners maintain functionality across multiple owned domains — like logins, sessions, and analytics — after third-party cookies are deprecated.

This configuration allows our two related business domains to be recognized as a single set for cookie handling purposes.

# See also rws-config
RWS for JSON StorageAccessApi
The related-website-set.json file is a declarative file that tells browsers (especially Chrome) which domains are part of the same organizational group — so that certain restricted cross-site features like cookie access can still be enabled without violating privacy boundaries.

It supports the transition away from third-party cookies by allowing limited and privacy-respecting storage access across a small group of trusted domains.

This file is typically hosted on a public domain, submitted to Google for review, and used by Chrome to allow certain storage-related exceptions across listed domains.

For more information on Related Website Sets, visit:  
👉 [Google Chrome’s Related Website Sets Documentation](https://developer.chrome.com/docs/privacy-sandbox/related-website-sets/)

---

Maintained by
Chandra Brown — T&C Appliance/HVAC Repair



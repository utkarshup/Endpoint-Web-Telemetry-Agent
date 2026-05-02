# Privacy Policy for Endpoint Web Telemetry Agent

**Effective Date:** May 2, 2026

**1. Introduction**
This Privacy Policy applies to the "Endpoint Web Telemetry Agent" browser extension. This extension is an enterprise IT administrative tool designed strictly for internal corporate environments.

**2. Data Collection and Usage**
This extension collects browser URL navigation events and timestamps. The sole purpose of collecting this data is to support internal corporate auditing, security monitoring, and IT compliance.

**3. Local Processing Only**
This extension operates entirely locally. It **does not** transmit, upload, or route any data over the internet to external, third-party, or developer servers. All collected telemetry is routed exclusively to the local machine's operating system via the Chrome Native Messaging API to an enterprise-managed host application.

**4. Data Sharing and Disclosure**
We do not sell, rent, monetize, or share any user data with third parties. Data is processed locally and is only accessible by your organization's internal IT administrators who manage the Native Messaging Host application.

**5. Required Permissions**
* **webNavigation:** Required to observe browser navigation events in real-time without injecting content scripts into web pages.
* **nativeMessaging:** Required to pass the captured navigation telemetry securely to the local operating system's registered Native Messaging Host application.

**6. Contact**
If you have questions about this privacy policy or the data collected by this enterprise tool, please contact your organization's IT department or system administrator.

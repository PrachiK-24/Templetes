# README: Importing Template into Zabbix

This guide provides step-by-step instructions for importing a template into Zabbix monitoring system.

## Prerequisites

Before starting, ensure you have:
- Access to Zabbix with appropriate administrative privileges.
- Downloaded the Zabbix template file (`template.xml`) that you wish to import.

## Steps to Import Template

1. **Navigate to Configuration**
   - Click on the "Configuration" tab and click on "Import Templetes" in the top menu.


2. **Select Templates**
   - In the left-hand menu under "Configuration," click on "Templates and "Import" in the top of the right corner.

     ![image](https://github.com/user-attachments/assets/cdd8bc50-fae3-4b7c-8a44-aea92600c1ec)

3. **Choose File**
   - Click on the "Choose File" button to select the `template.xml` file from your local system.

   ![image](https://github.com/user-attachments/assets/535d3857-523e-44a0-b607-878247aa4194)


6. **Macros in templete**
   - Here, we can see the different macros which is used in templetes.
   - {$WEB.URL} : Provides Threshold value Web URL.
   - {$CERT.EXPIRY.WARN} : Provides Threshold value for SSL certificate expires soon for {$WEB.URL}).
   - {$DNS.QUERY.WARN} : Provides Threshold value for DNS Query time in milliseconds (ms).
   - {$DOWNLOAD.SPEED.WARN} : Provides Threshold value for Download Speed in Kilobites per seconds (Kbps).
   - {$HTTP.PROBE.WARN} : Provides Threshold value for HTTP Probe duration in milliseconds (ms). 
   - {$PAGE.LOAD.WARN} : Provides Threshold value for Page Load Time in seconds (s).
   - {$REACH.TIME.WARN} : Provides Threshold value for Reach time in seconds (s).
   - {$RESPONSE.TIME.WARN} : Provides Threshold value for Response time in milliseconds (ms).
   - {$SSL.HANDSHAKE.WARN} : Provides Threshold value for SSL Handshake in seconds (s).
   - {$TTFB.WARN} : Provides Threshold value for TTFB in seconds (s).
   

   ![image](https://github.com/user-attachments/assets/f835aa1c-03cf-4078-91f3-b26139f0424b)




## Additional Notes

- **Template Functionality:** Verify the imported template's functionality by checking its items, triggers, and graphs.
- **Troubleshooting:** If you encounter any issues, refer to Zabbix documentation or contact your system administrator.

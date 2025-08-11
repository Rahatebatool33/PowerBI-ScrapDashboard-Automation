# Power BI Scrap Dashboard Automation

This project automates the process of exporting a Power BI Scrap Dashboard report as a PDF and sending it via email on a daily schedule using Power Automate and Microsoft Outlook.

---

## Tools Required

- **Power BI Service:** To host the published Scrap Dashboard  
- **Power Automate:** To create and manage the automation flow  
- **Microsoft Outlook:** To send the automated email with PDF attachment  
- **Power BI Pro License:** Necessary to enable report export functionality via Power Automate  

---

## Automation Workflow Overview

1. **Publish the Scrap Dashboard**  
   Publish your report from Power BI Desktop to the Power BI Service workspace.

2. **Create Scheduled Flow in Power Automate**  
   Set up a scheduled cloud flow to trigger daily at a specified time.

3. **Export Report to PDF**  
   Configure the flow to export the Scrap Dashboard report as a PDF file.

4. **Send Email with PDF Attachment**  
   Automate sending an email with the exported PDF attached to designated recipients.

5. **Test and Validate**  
   Run the flow manually to confirm proper execution and delivery.

---

## Setup Steps

1. Publish the report to Power BI Service workspace.  
2. Create a scheduled flow in Power Automate with daily frequency.  
3. Add "Export to File for Power BI Reports" action and configure it for PDF export.  
4. Add the email action, attach the exported PDF, and specify recipient details.  
5. Save and test the flow to ensure correct operation.

---

## Benefits

- Saves time by automating manual report distribution  
- Ensures consistent and timely sharing of critical scrap data  
- Reduces errors associated with manual email generation  

---

For questions or support, please contact the project maintainer.

---
title: "Customize the business card scan control (Dynamics 365 Sales) | MicrosoftDocs"
description: "Customize how the data from the scanned business cards maps to the fields in the Contact and Lead forms."
keywords: "business card, scan, scanner, lead, contact, populate, data, customize"
ms.date: 10/01/2019
ms.service:
  - "dynamics-365-sales"
ms.custom:
  - "dyn365-sales"
ms.topic: article
ms.assetid: 39954f18-c558-4b22-841a-7b12c9c948f2
author: shubhadaj
ms.author: shujoshi
manager: annbe
---

# Customize the business card scanner control

Dynamics 365 Sales comes with an out-of-the-box business card control that defines the mapping of what information from the business card goes in which fields of the **Contact** or **Lead** forms. If you have custom fields on your **Contact** or **Lead** form and you want the data from the business card to be populated in these fields, edit the default mappings of the business card control.


> [!IMPORTANT]
> - This feature is available only in the EMEA and North America regions.
> - To know about the business card scan limits with your user license, see the [Microsoft Dynamics 365 Licensing Guide](https://go.microsoft.com/fwlink/p/?LinkId=866544).

To edit the mappings:

1.  On the navigation bar, select **Settings**, and then select **Advanced Settings**.

    The **Business Management** settings page opens.

2.  On the navigation bar, select **Settings**, and then under **Customization**, select **Customizations**.

3.  Select **Customize the System**.

4.  Under **Components** in the solution explorer, expand **Entities**, and then expand the **Contact** or **Lead** entity.

5.  Select **Forms**.

    ![Forms node of Contact entity in the solution explorer](media/forms-node-in-contact-entity.png "Forms node of Contact entity in the solution explorer")

6.  Open the form of type **Quick Create**.

7.  Locate and select the **Business Card** field on the form, and select **Change Properties** in the **Edit** group.

    ![Scan business card field in the Contact form](media/scan-business-card-field-in-contact-form.png "Scan business card field in the Contact form")

8.  In the **Field Properties** dialog box, select **AI Builder Business Card control** on the **Control** tab.

    ![Business card scanner control in the Field Properties dialog box](media/business-card-scanner-control-field-properties-dialog-box.png "Business card scanner control in the Field Properties dialog box")

9.  Select the property that you want to change the mapping for, and select the **Edit** icon ![Edit icon](media/edit-icon.png "Edit icon") to change the value the field maps to.

10. When done, select **OK**.


> [!NOTE]
> -  Sales people must have the Common Data Service User role assigned to them to use the business card scan control.
> -  Mapping of address fields is currently not supported.


### See also

[Scan business cards](scan-business-cards.md)  

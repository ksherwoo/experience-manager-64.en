---
title: Update the license type for the deployment
seo-title: Update the license type for the deployment
description: Update the license type for the deployment by using the Change License page in administration console.
seo-description: Update the license type for the deployment by using the Change License page in administration console.
uuid: 0152635e-2c00-4944-b9b6-64b368589a91
contentOwner: admin
content-type: reference
geptopics: SG_AEMFORMS/categories/get_started_with_administering_aem_forms_on_jee
products: SG_EXPERIENCEMANAGER/6.4/FORMS
discoiquuid: e4f31377-ccc9-4986-a3bf-ef2e83d12448
exl-id: 07671470-59dd-4290-be9a-465fcd89ac2d
---
# Update the license type for the deployment {#update-the-license-type-for-the-deployment}

As part of the AEM forms installation process, you used Configuration Manager to configure and deploy the AEM forms modules that you require. By default, those modules are configured with a 60-day evaluation license. Use the Change License page in administration console to change the license type for the deployment. The currently deployed modules are displayed on the Change License page.

The Change License page displays information about your license:

* The current license type
* The date and time the license was last updated
* Who performed the last update
* The current status of the license
* The date that AEM forms was installed
* The date the current license will expire

>[!NOTE]
>
>The license change applies to all deployed modules. Before you change the license type, undeploy any modules that are not licensed. Do not select the Production license type if the list of deployed modules contains modules other than the ones you purchased from Adobe.

## Update the license type {#update-the-license-type}

1. In administration console, click Licensing.
1. Read the AEM forms end-user license agreement, select I Accept if you agree with the terms of the agreement, and then click Next.
1. On the Change License page, select a license type:

    * **EVAL:** 60-day evaluation license
    * **DEV:** Perpetual development license
    * **NFR:** 2-year evaluation license
    * **IDEV:** 1-year subscription to the Adobe Developer Program
    * **Production:** Perpetual license

1. Select Yes, License Change Is Valid for All Deployed Modules.
1. Click Confirm License Change. A message appears, stating that the license was updated successfully.

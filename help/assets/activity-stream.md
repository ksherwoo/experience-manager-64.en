---
title: Activity stream in timeline
description: This article describes how to display activity logs for assets on the timeline. 
contentOwner: AG
feature: Asset Management
role: User,Admin
exl-id: 52fa2d59-177f-49ca-a480-7213ce0ca7d7
---
# Activity stream in timeline {#activity-stream-in-timeline}

This feature displays activity logs for assets on the timeline. If you perform any of the following asset-related operations in Adobe Experience Manager (AEM) Assets, the Activity stream feature updates the timeline to reflect the activity.

The following operations are logged in the activity stream:

* Create
* Delete
* Download (including renditions)
* Publish
* Unpublish
* Approve
* Reject
* Move

The activity logs to be displayed in the timeline are fetched from the location `/var/audit/com.day.cq.dam/content/dam` in CRX, where log files are stored.  

In addition, timeline activity is logged when new assets are uploaded or existing asses are modified and checked into AEM via [Adobe Asset Link](https://helpx.adobe.com/enterprise/admin-guide.html/enterprise/using/manage-assets-using-adobe-asset-link.ug.html) or [AEM desktop app](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/introduction.html).

>[!NOTE]
>
>Transient workflows are not displayed in the timeline, because no history information is saved for these workflows.

To view the activity stream, perform one or more of the operations on the asset, select the asset, and then choose **[!UICONTROL Timeline]** from the GlobalNav list.

![timeline-3](assets/timeline-3.png)

The timeline displays the activity stream for the operations you perform on the assets. 

![activity_stream](assets/activity_stream.png)

>[!NOTE]
>
>The default log storage location for **Publish** and **Unpublish** tasks is `/var/audit/com.day.cq.replication/content`. For **Move** tasks, the default location is `/var/audit/com.day.cq.wcm.core.page`.

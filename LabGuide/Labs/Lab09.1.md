## Lab 09 - Discover Apps 

## Lab scenario

In this lab, participants will delve into the process of discovering apps within their organization using Microsoft Defender. The exercise focuses on creating a snapshot report that captures insights from log files to provide visibility to cloud app activity.

## Lab objectives (Duration: 15 minutes)

In this lab, you will complete the following tasks:

- Exercise 1: Create a snapshot report to Discovered Apps

## Architecture Diagram

   ![Picture 1](../Media/lab9-arch.png)

### Exercise 1: Create a snapshot report to Discovered Apps.

1. Collect log files from your firewall and proxy, through which users in your organization access the Internet. Make sure to gather logs during times of peak traffic that are representative of all user activity in your organization.
1. In the Microsoft Defender Portal, under Cloud Apps, select **Cloud discovery** and click on **Create a new report**.

   ![Picture 1](../Media/image_51.png)

1. Provide the details in the report details tab, click on **Download sample log** which we will be using in next step and select **Next**.
- **Report name** : Report<inject key="DeploymentID" enableCopy="false" /></inject>
- **Description** : New report
- **Source** : Blue coat ProxySG - Access log(W3C)

   ![Picture 1](../Media/DiscoverApps9.png)

4. Select **Browse** and choose the source from which you want to upload the log files and select the sample log file which was downloaded in previous step. Select **Upload logs**.

   ![Picture 1](../Media/DiscoverApps10.png)

   > **Note**: Verify your log format to make sure that it's formatted properly according to the sample log you can download. Under Verify your log format, select View log format then select Download sample log. Compare your log with the sample provided to make sure it's compatible.

1. Select **Settings**. Then under Cloud Discovery, select **Snapshot reports**, and select your snapshot report. You can see all the details regarding the report that you have uploaded.

   ![Picture 1](../Media/DiscoverApps13.png)

1. Select Discovered apps to see all the apps present in the portal.

    ![Picture 1](../Media/DiscoverApps15.png)

## Review
In this lab, you will complete the following tasks:

- Create a snapshot report to Discovered Apps


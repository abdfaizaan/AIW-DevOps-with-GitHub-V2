# Microsoft Dev Box for Developers

## Overview

Microsoft Dev Box provides high-performance, cloud-based development workstations designed to streamline the developer experience. By leveraging preconfigured environments with customizable compute and storage options, Dev Box enables developers to quickly access ready-to-code workspaces. With integrated networking capabilities and centralized management of development pools, it simplifies configuration, enhances productivity, and accelerates the development lifecycle in the cloud.

## Objective

This lab is designed to provide participants with practical experience in setting up and managing Microsoft Dev Box environments to enhance development workflows. Participants will learn how to configure cloud-based development workstations by creating and defining Dev Boxes, establishing network connections, and accessing them through the portal. This hands-on approach will help streamline development processes, making it easier to manage resources and collaborate on projects.

## Architecture

The architecture for **Implement Dev Box** integrates several components to deliver a cloud-based development environment. Central to this is the **Microsoft Dev Box**, a high-performance workstation configured with specific compute, storage, and image settings defined in the **Dev Box Definition**. **Network Connections** link the Dev Boxes to Azure virtual networks, ensuring seamless integration. The **Dev Box Pool** manages multiple Dev Boxes across projects, while the **Microsoft Dev Box Portal** serves as the interface for users to create, manage, and access their Dev Boxes. This setup provides an efficient, scalable, and secure development experience in the cloud.

## Explanation of Components

The architecture for this lab involves several key components:

- **Microsoft Dev Box:** A cloud-based, high-performance workstation preconfigured for development tasks.  
- **Dev Box Definition:** A template defining the compute, storage, and image configuration for a Dev Box.  
- **Network Connection:** Links Dev Boxes to Azure virtual networks for secure communication with other resources.  
- **Dev Box Pool:** A collection of managed Dev Boxes, allowing for simplified scaling and deployment.  
- **Microsoft Dev Box Portal:** A web interface for creating, managing, and accessing Dev Boxes remotely.

## Let's Get Started with Azure Portal
 
1. Navigate to [Azure Portal](https://portal.azure.com) using a new browser tab.
 
1. You'll see the **Sign into Microsoft Azure** tab. Here, enter your credentials:
 
   - **Email/Username:** <inject key="AzureAdUserEmail"></inject>
 
      ![](./media/GS2.png "Enter Email")
 
3. Next, provide your password:
 
   - **Password:** <inject key="AzureAdUserPassword"></inject>
 
      ![](./media/GS3.png "Enter Password")

1. If you see the pop-up Action Required, click **Ask Later**.

   ![](./media/asklater.png)

   >**NOTE:** Do not enable MFA, select **Ask Later**.
 
1. If you see the pop-up **Stay Signed in?**, click **No**.

   ![](./media/GS9.png)

1. If you see the pop-up **You have free Azure Advisor recommendations!**, close the window to continue the lab.

1. If a **Welcome to Microsoft Azure** popup window appears, click **Maybe Later** to skip the tour.

## Support Contact
 
The CloudLabs support team is available 24/7, 365 days a year, via email and live chat to ensure seamless assistance at any time. We offer dedicated support channels tailored specifically for both learners and instructors, ensuring that all your needs are promptly and efficiently addressed.

Learner Support Contacts:
- Email Support: cloudlabs-support@spektrasystems.com
- Live Chat Support: https://cloudlabs.ai/labs-support

Now, click on **Next** from the lower right corner to move on to the next page.

![](./media/GS4.png)

### Happy Learning!!

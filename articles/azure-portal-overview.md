<properties
    pageTitle="Microsoft Azure preview portal overview"
    description="学习如何使用Microsoft Azure preview portal."
    services=""
    documentationCenter=""
    authors="davidwrede"
    manager="dwrede"
    editor="jimbe"/>

<tags
    ms.service="na"
    ms.workload="na"
    ms.tgt_pltfrm="na"
    ms.devlang="na" 
    ms.topic="hero-article"
    ms.date="04/28/2015"
    ms.author="dwrede"/>

#Microsoft Azure preview portal overview

The Microsoft Azure preview portal is a central place where you can provision and manage your Azure resources.
This tutorial will familiarize you with the portal and show you how to use some of these key capabilities:

*   A **comprehensive marketplace** that lets you browse through thousands of items from Microsoft and other vendors that can be purchased and/or provisioned.
*   A **unified and scalable browse experience** that makes it easy to find the resources you care about and perform various management operations.
*   **Consistent management pages** (or blades) that let you manage Azure’s wide variety of services through a consistent way of exposing settings, actions, billing information, health monitoring and usage data, and much more.
*   A **personal experience** that lets you create a customized start screen that shows the information that you want to see whenever you log in.
    You can also customize any of the management blades that contain tiles.
    
    ![Reference][uiorientation]

##Azure Portal UI Orientation

uiorientation
Before you get started[You will need a valid Azure subscription to go through this tutorial.](http://azure.microsoft.com/pricing/free-trial/)If you don’t have one, then 
sign up for a free trial

## today.

Once you have a subscription, you can access the portal at [https://portal.azure.com].
How to create a resource
Azure has a marketplace with thousands of items that you can create from one place.
Let’s say you want to create a new Windows Server 2012 VM.
The +NEW hub is your entry point into a curated set of featured categories from the marketplace.

1.  Each category has a small set of featured items along with a link to the full marketplace that shows all categories and search.
2.  To create that new Windows Server 2012 VM, perform the following actions:
3.  Windows Server 2012 is featured, so you can select it from the Compute category.

Fill out some basic inputs on a form.

![Click ‘Create’ and you’re VM will begin to provision immediately.][portalcategories]

##The notifications hub will alert you when your resource has been created and a management blade will open (you can always browse to resources later).

Reference
Portal Categories
portalcategories

![How to find your resources][browsehub]

##You can always pin frequently accessed resources to your startboard, but you might need to browse to something that you don’t frequently access.

The browse hub shown below is your way to get to all of your resources.
You can filter by subscription, choose/resize columns, and navigate to the management blades by clicking on individual items.
Reference[Browse Hub](role-based-access-control-configure.md)browsehub
How to manage and delegate access to a resource

1.  From this blade you can connect to the virtual machine using remote desktop, monitor key performance metrics, control access to this VM using role based access (RBAC), configure the VM, and perform other important management tasks.
2.  Delegating access based on role is critical to managing at scale.
3.  Click 
4.  here
5.   to learn more about it.

![To delegate access to a resource, perform the following actions:][manageresource]

##Browse to your resource.

Click ‘All settings’ in the Essentials section.
Click ‘Users’ in the settings list.
Click ‘Add’ in the command bar.

1.  Choose a user and a role.
2.  Reference
    Managing a Resource
3.  manageresource
4.  How to customize a resource blade

![Azure preconfigures the blades for your resources, but the tiles on these blades are yours to control.][customizeblades]

##You can easily go into customize mode to add, remove, resize, or re-arrange the tiles.

To customize a blade, perform the following actions:
Browse to your resource.
Click the ‘…’[at the top of the blade you want to customize.](http://azure.microsoft.com/support/plans/)Click ‘Add parts’.
Start dragging and dropping parts.
Reference

![Customizing Blades][helpsupport]

##customizeblades

How to get help

*   If you ever have a problem, we’re here for you.
*   The portal has a help and support page that can point you in the right direction.
*   Depending on your 
*   support plan
*   , you can also create support tickets directly in the portal.
*   After creating a support ticket, you can manage the lifecycle of the ticket from within the portal.
*   You can get to the help and support page by navigating to Browse -> Help + support.

Reference
Help and support[helpsupport](http://azure.microsoft.com/blog/topics/management/)Summary[Let’s review what you learned in this tutorial:](http://feedback.azure.com/forums/223579-azure-preview-portal)You learned how to sign up, get a subscription, and browse to the portal
[You got oriented with the portal UI and learned how to create and browse resources](http://weblogs.asp.net/scottgu)You learned how to create a resource and browse resources

[uiorientation]: ./media/azure-portal-how-to-use/azure_portal_1.png 

[portalcategories]: ./media/azure-portal-how-to-use/azure_portal_2.png 

[browsehub]: ./media/azure-portal-how-to-use/azure_portal_3.png 

[manageresource]: ./media/azure-portal-how-to-use/azure_portal_4.png 

[customizeblades]: ./media/azure-portal-how-to-use/azure_portal_5.png 

[helpsupport]: ./media/azure-portal-how-to-use/azure_portal_6.png 


-portal-how-to-use/azure_portal_2.png
[BrowseHub]: ./media/azure-portal-how-to-use/azure_portal_3.png
[ManageResource]: ./media/azure-portal-how-to-use/azure_portal_4.png
[CustomizeBlades]: ./media/azure-portal-how-to-use/azure_portal_5.png
[HelpSupport]: ./media/azure-portal-how-to-use/azure_portal_6.png

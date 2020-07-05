# Deployment


## 1. Create Healthcare Bot SaaS Application

 Click on the "GET IT NOW" button

Navigate to the [marketplace]([Marketplace](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/microsoft-hcb.microsofthealthcarebot?tab=Overview)
) and create your Healthcare Bot application
![Marketplace](./marketplace.png)

Once redicted to the Azure Portal, select the Plan and click on the "Create" button

![Azure Portal](./marketplace2.png)

On the next page, give it a resource name. You also need to select the Azure subscription that will be used to charge the cost of the bot.

![Azure Portal](./marketplace3.png)

Notice that after the creation of this resource, you will not be able to find it under any of the Resource Groups. To see all your SaaS Applications, make sure you have addes a "Software as a Service (SaaS)" blade to the navigation panel as shown below.

![Azure Portal](./marketplace4.png)

## 2. Configuring your Healthcare Bot SaaS application

Locate the newly created resource and click it. Click the "Confgure Account" button as shown. This will take you to the Healthcare Bot's Owner portal where you can continue creating the actual Healthcare Bot resources.

![Azure Portal](./marketplace5.png)

At this point you can assign a name to the bot. You will have default name given by you  when you created the SaaS resource. This name will be used to generate a globally unique name that will identify this instance of the bot. Also, select the location of the provisioned resources. We currently support USA and EU locations. Click the "Create" button.

![Admin Portal](./adminportal1.png)

## 3. Configure Microsoft Teams channel
After logging into the Healthcare Bot portal, navigate to Integeation/Channels and enable the Teams channel

![Portal](./portal1.png)

Copy the "Bot Id" into the clipboard and click on the "Save" button. You will need this Bot Id to paste into the Teams Application manifest file.

![Portal](./portal2.png)

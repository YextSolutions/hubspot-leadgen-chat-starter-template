# **Hubspot Lead Gen Chat Starter Template**

## **Overview**

_The Hubspot Lead Gen Chat Starter Template includes an example Chat configuration that will gather contact information for prospects interested in a demo and create a new contact in Hubspot._

## **What’s Included**

### Chat

This template includes a Chat configuration focused on gathering contact information and creating contacts in Hubspot for prospects interested in a product demo.

## **Installation Guide**

### Pre-requisites

#### Yext

This template requires access to the following Yext products:

- Chat

#### Hubspot

This template requires the creation of a Private App. This will allow access to the APIs required to create new contacts in Salesforce. Follow the instructions below to create the Private App:

1. In Hubspot, navigate to **Settings > Integrations > Private Apps**.
2. Click **Create a private app**.
3. In the **Basic Info** section, provide a name for the app.
4. Navigate to the **Scopes** section. Expand the CRM section and select **Read & Write** access for the **crm.objects.contacts** scope.
5. Click **Create App**. Follow the flow until you’re presented with an **access token**. Copy the token and have it ready to input during the installation of the template.
6. Now you’re ready to proceed with the template installation!

### How to Install

1. In the Yext platform, navigate to **Apps > Solutions**.
2. Select the **Hubspot Lead Gen Chat Starter Template**.
3. Click **View Solution**. This will open up the Admin Console, an account configuration tool that will allow you to add all of the resources mentioned above to your account.
4. In the upper right corner, click **Apply**.
5. A modal window will open and prompt you to **enter your Account ID**. You can quickly find this in the URL of your Yext account, which takes the form of “[www.yext.com/s/{accountId}/…](http://www.yext.com/s/{accountId}/…)”. Enter the ID and click **Continue**.
6. In the new modal, click **Start authorization flow**. This will open a new window. When prompted, click **Authorize**. Once you receive authorization confirmation, navigate back to the Admin Console window and click **Continue**.
7. A new modal window will open and prompt you to input your **Hubspot Access Token**. Enter your token from the private app you created earlier and click **Save**.
8. A window will pop up showing the resources that will be added / edited within your account. Click **Continue** and, when prompted, click **Confirm**.
9. In the Console, you’ll see the message “Applying resources…”. Wait while the resources are applied. You’ll see messages in the console for each resource that is applied and will eventually receive a message saying “Successfully applied resources”.
10. You’re done! All of the template’s resources have been added to your account. Jump back into your Yext account and explore your new Chatbot!

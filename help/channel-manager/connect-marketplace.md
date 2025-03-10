---
title: Connect sales channel to [!DNL Walmart Marketplace]
description: Configure the sales channel and connect to Walmart Marketplace.
exl-id: 8c78c582-7b57-4f73-894e-134ba0ba3640
---
# Connect sales channel to [!DNL Walmart Marketplace]

After installing Channel Manager on your [!DNL Commerce] instance, connect a [!DNL Commerce] store to [!DNL Walmart Marketplace].

1. [Create the sales channel](#create-the-sales-channel) by selecting the Commerce store for product listings.

1. [Connect the channel to [!DNL Walmart Marketplace] by adding [!UICONTROL Walmart API credentials]](#connect-the-channel-to-walmart-marketplace).

1. [Complete sales channel setup](#complete-store-setup) to manage listings, inventory, pricing, and orders for your [!DNL Walmart Marketplace] product assortment.

## Create the sales channel

1. From the Admin, open [!DNL Channel Manager] by selecting **[!UICONTROL Marketing** > _Channels_ > **Channel Manager]**.

1. In the **[!UICONTROL Marketplaces available to connect]** section, select **[!UICONTROL Get Started]**.

   ![Connect new [!DNL Walmart] store to [!DNL Channel Manager]](assets/channel-manager-home.png)

1. If needed, set up your [!DNL Walmart Marketplace Seller] account.

1. Configure the store and connection:

   - Select **[!UICONTROL Add Credentials]**. 

   - Select the [!DNL Commerce] store view to connect to the marketplace.

     ![Configure connection between Commerce and [!DNL Walmart Marketplace] from [!DNL Channel Manager]](assets/configure-commerce-to-marketplace-connection.png) 

   - Enter a unique **[!UICONTROL store name]**.

   - Select the **[!UICONTROL Adobe Commerce site]** for product listings.

   - Add an **[!UICONTROL email address]** to receive service notifications related to [!DNL Channel Manager].

1. Connect the channel to [!DNL Walmart Marketplace].

   -  Add the credentials for the [[!DNL Walmart Marketplace Adobe Production API key]](walmart-requirements.md#generate-a-walmart-marketplace-production-api-key) from your [!DNL Walmart Marketplace Seller] account.

   - If you don’t have the credentials, get them from the [!DNL Walmart Marketplace Developer Portal] by selecting **[!UICONTROL Get API credentials]**.

     On the Developer Portal select your region (US and Canada) and then log in.  

     ![[!DNL Walmart Marketplace] account login](assets/walmart-marketplace-login-page.png)
       
   - On the API key form, copy and save the **[!UICONTROL Client ID]** and **[!UICONTROL Client Secret]** values for the [!UICONTROL Adobe Inc Production API key] to a secure location. 

     ![[!DNL Walmart Marketplace API key] configuration page](assets/walmart-api-key-management-form.png) 
       
     >[!NOTE]
     >
     >If the [!DNL Adobe Inc] key is not listed in the Developer Portal, select **[!UICONTROL Add New Key for a Solution Provider]** to configure permissions and generate the key. For configuration details, see [Generate a [!DNL Walmart Marketplace API Key]](walmart-requirements.md#generate-a-walmart-marketplace-api-key).

   - Return to [!DNL Channel Manager] to add the credentials to the **[!UICONTROL Walmart Connection]** information.  
       
     When you add credentials, Adobe hides the client secret and stores the value in a secure vault.  

1. Select **[!UICONTROL Save Store]** to apply the configuration and connect to the [!DNL Walmart marketplace].

1. After connecting successfully, [complete store setup](complete-store-setup.md) from the **[!UICONTROL Channel Manager]** store page.

![Setup first store](assets/channel-manager-setup-first-store.png)

### Troubleshoot connection issues

If the connection to [!DNL Walmart] fails, see the [Walmart Marketplace FAQ](https://developer.walmart.com/faq/us/faq-auth/){target="_blank"} for troubleshooting tips.

- From the [!DNL Walmart Developer Portal], verify that you copied the correct credentials for the production API key for [!UICONTROL Adobe Inc.]

- Verify that the access configuration for the [!UICONTROL Walmart Adobe API key] has the correct permissions. See [[!DNL Walmart Requirements]](walmart-requirements.md##generate-a-walmart-marketplace-api-key).

- Confirm that the [!DNL Walmart API] service is available from the [Walmart API status page](https://developer.walmart.com/us/whats-new/new-api-status-information-now-available/){target="_blank"}.
